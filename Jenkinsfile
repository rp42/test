pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Build stage"




'''
      }
    }

    stage('Test') {
      steps {
        sh '''echo "Test 1"
'''
        sh '''echo "Test 2 failed";


 exit 42

'''
        sh '''echo "Test 3"
'''
      }
    }

  }
}