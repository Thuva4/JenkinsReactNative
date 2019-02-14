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
        sh 'mkdir ~/.npm-global'
        sh ' npm config set prefix \'~/.npm-global\''
        sh ' export PATH=~/.npm-global/bin:$PATH'
        sh ' export PATH=~/.npm-global/bin:$PATH'
        sh 'npm install -g expo'
        sh 'npm install -g yarn'
        sh 'yarn install'
      }
    }
  }
}