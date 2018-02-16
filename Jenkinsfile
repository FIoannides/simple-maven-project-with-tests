pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat(script: 'mvn test', returnStatus: true)
      }
    }
    stage('install') {
      steps {
        bat(script: 'mvn install', returnStatus: true)
      }
    }
  }
}