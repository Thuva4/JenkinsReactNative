pipeline {
  agent any
  stages {
    stage('install') {
      node {
        checkout scm 
      }
      steps {
        sh 'sudo apt install npm'
        sh 'npm install'
      }
    }
  }
}
