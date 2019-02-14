pipeline {
  agent {
    node {
      label 'start'
    }

  }
  stages {
    stage('install') {
      steps {
        sh 'npm install'
      }
    }
  }
}