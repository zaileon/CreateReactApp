pipeline {
    tools {
        nodejs: 'node8'
    }
    agent any // { docker 'node:6.3' }
    stages {
        stage('Prepare') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}