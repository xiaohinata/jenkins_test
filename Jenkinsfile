pipeline {
  agent {
    docker {
      image 'python:latest'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
        sh 'uname -a'
        sh 'pip install numpy'
      }
    }

  }
}
