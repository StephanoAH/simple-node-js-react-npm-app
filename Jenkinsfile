pipeline {
  agent {
    docker {
      image 'node:lts-alpine3.17'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    CI = 'true'
  }
}