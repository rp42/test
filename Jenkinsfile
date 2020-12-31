pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''echo "Build stage"




'''
          }
        }

        stage('Build B') {
          steps {
            sh 'echo "Build B"'
            sh 'echo "Build C"'
          }
        }

        stage('Build C') {
          steps {
            sh 'echo "Build C"'
          }
        }

        stage('Build D') {
          steps {
            sh 'echo "Build D"'
          }
        }

        stage('Build E') {
          steps {
            sh 'echo "build E"'
          }
        }

      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh '''echo "Test 1"
'''
            sh '''echo "Test 2 ok";


 exit 0'''
            sh '''echo "Test 3"
'''
          }
        }

        stage('Test B') {
          steps {
            sh 'echo "Test B"'
          }
        }

        stage('Test C') {
          steps {
            sh 'echo "Test C"'
          }
        }

      }
    }

  }
}