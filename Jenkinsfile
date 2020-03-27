pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    options {
      ansiColor('xterm')
   }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
