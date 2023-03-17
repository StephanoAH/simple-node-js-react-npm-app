pipeline {
  agent {
    node {
      label 'ubuntu-node1'
    }
  }
  environment {
    CI = 'true'
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo this'
      }
    }
  }
}