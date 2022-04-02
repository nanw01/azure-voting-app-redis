pipeline {
  agent any
  stages {
    stage('Hello Jenkins') {
      parallel {
        stage('Hello Jenkins') {
          steps {
            echo 'Hello Jenkins'
          }
        }

        stage('multiple') {
          steps {
            echo '123'
          }
        }

      }
    }

  }
}