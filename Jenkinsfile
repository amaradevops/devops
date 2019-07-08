pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        build 'testjob'
      }
    }
    stage('test') {
      steps {
        build 'test1'
      }
    }
  }
}