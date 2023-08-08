pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'I want to Build'
      }
    }

    stage('Test') {
      steps {
        echo 'I want to text'
      }
    }

    stage('Stages') {
      parallel {
        stage('Stages') {
          steps {
            echo 'i want  to stages '
          }
        }

        stage('Deploy') {
          steps {
            echo 'I want to deploy'
          }
        }

        stage('Operate') {
          steps {
            echo 'I want to operate'
          }
        }

      }
    }

  }
}