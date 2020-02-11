pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'Salam'
          }
        }

        stage('Test') {
          steps {
            sh 'sh \'echo "Hello"\''
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        echo 'NY'
      }
    }

    stage('error') {
      steps {
        echo 'VOVA'
      }
    }

  }
}