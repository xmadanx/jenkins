pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/xmadanx/jenkins', branch: 'main')
      }
    }

    stage('Build') {
      steps {
        sh 'ls'
      }
    }

  }
}