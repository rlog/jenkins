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
        sh 'pm2 start bin/www -i 0 --name "jenkins"'
      }
    }
  }
}