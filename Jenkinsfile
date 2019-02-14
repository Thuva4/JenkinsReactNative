pipeline {
  agent {
    node {
      checkout scm 
    }
  }
  stages {
    stage('install') {
      steps {
        sh 'sudo apt install npm'
        sh 'npm install'
      }
    }
  }
}
