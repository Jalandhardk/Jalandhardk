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

    stage('monitor') {
      steps {
        bat 'mvn -v'
      }
    }

  }
}