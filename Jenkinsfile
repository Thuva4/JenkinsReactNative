pipeline {
  agent any
  stages {
    stage('install npm') {
      steps {
        sh '''sudo apt install npm 
'''
        sh 'npm install -g yarn'
        sh 'npm install'
      }
    }
  }
}