pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'yarn'
      }
    }
    stage('start server') {
      steps {
        sh 'yarn start'
      }
    }
  }
}