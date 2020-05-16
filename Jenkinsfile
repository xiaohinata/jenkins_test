pipeline {
    agent {
        docker {
            image python
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
