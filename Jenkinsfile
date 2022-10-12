pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed '
      }
    }

    stage('Test Stages') {
      parallel {
        stage('Test Stages') {
          steps {
            echo 'test '
          }
        }

        stage('Test1') {
          steps {
            echo 'Run Test 1'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }

  }
}