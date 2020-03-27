pipeline {
    
    agent {
        docker { image 'node:7-alpine' }
    }
    options {
      ansiColor('xterm')
    }
 
    environment {
      DISABLE_AUTH = "true"
      DB_ENGINE = "sqlite"
    }
 
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                echo "Database engine is ${DB_ENGINE}"
                echo "DISABLE_AUTH is ${DISABLE_AUTH}"
                sh 'printenv'
            }
        }
    }
}
