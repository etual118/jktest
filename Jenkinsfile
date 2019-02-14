pipeline {
  agent any
  stages {
    stage('getRaw') {
      steps {
        sh '''echo test
'''
      }
    }
    stage('parseRaw') {
      steps {
        sleep 1
      }
    }
    stage('sendMail') {
      steps {
        sh 'ls'
      }
    }
  }
  environment {
    Test1 = 'aa'
  }
}