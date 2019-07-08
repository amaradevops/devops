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
        build(job: 'test1', quietPeriod: 1)
      }
    }
  }
}