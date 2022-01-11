pipeline {
  agent any
  stages {
    stage('deploy') {
      parallel {
        stage('deploy') {
          steps {
            echo 'Deployment Successful'
          }
        }

        stage('deploy2') {
          steps {
            echo 'Deployment Successful'
          }
        }

      }
    }

    stage('SanityTest') {
      parallel {
        stage('SanityTest') {
          steps {
            bat 'java -version'
          }
        }

        stage('IntegrationTests') {
          steps {
            bat 'java -v'
          }
        }

      }
    }

  }
}