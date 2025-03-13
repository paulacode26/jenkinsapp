pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker { 
                    image 'node:20.15.1-alpine' 
                    reuseNode true
                }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}