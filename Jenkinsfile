pipeline {
  agent any
  stages {
    stage('dev1') {
      parallel {
        stage('dev1') {
          steps {
            echo 'hello'
          }
        }

        stage('dev2') {
          steps {
            echo 'hi'
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

  }
  environment {
    name = 'bhoopathi'
  }
}