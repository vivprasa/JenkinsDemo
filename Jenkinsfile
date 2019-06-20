pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Gradle', quietPeriod: 10)
      }
    }
  }
}