pipeline {
  agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
    }
  stages {
    stage('install npm') {
      steps {
        sh 'npm install -g yarn'
        sh 'npm install'
      }
    }
  }
}