pipeline {
  agent any
  stages {
    stage('Launch second Pipeline') {
      steps {
        build job: 'secondPipeline'
      }
    }
  }
}