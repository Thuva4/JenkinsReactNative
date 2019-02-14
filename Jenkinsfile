pipeline {
  agent any
  stages {
    stage('install npm') {
      steps {
        sh '''echo 'admin' | sudo -S apt install npm'''
        sh 'npm install -g yarn'
        sh 'npm install'
      }
    }
  }
}