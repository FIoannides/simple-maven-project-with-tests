pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat(script: 'mvn test', returnStatus: true)
      }
    }
  }
}