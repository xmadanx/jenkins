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
        sh 'docker build -t madan1742/hellomylove .'
      }
    }

    stage('Deploy') {
      steps {
        sh 'docker run -ti madan1742/hellomylove'
      }
    }

  }
}