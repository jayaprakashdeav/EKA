pipeline {
  agent any
  stages {
    stage('Diffrent_Environment') {
      parallel {
        stage('Integ_Env') {
          steps {
            sh 'echo "Integ_Env"'
          }
        }

        stage('QA') {
          steps {
            sh 'echo "QA_Env"'
          }
        }

        stage('Pre_Prod') {
          steps {
            sh 'echo "Pre_Prod"'
          }
        }

        stage('Prod') {
          steps {
            sh 'echo "Prod"'
          }
        }

      }
    }

  }
}