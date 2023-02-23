pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'i want to development'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'i want to build'
          }
        }

        stage('Test') {
          steps {
            echo 'i want to test'
          }
        }

        stage('Deploy') {
          steps {
            echo 'i want to deploy'
          }
        }

      }
    }

  }
}