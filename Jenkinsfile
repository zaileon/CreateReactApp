pipeline {
    tools {
        nodejs: 'node8'
    }
    agent any // { docker 'node:6.3' }
    stages {
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}