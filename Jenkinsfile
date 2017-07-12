pipeline {
    agent any // { docker 'node:6.3' }
    environment {
        PATH = "${PATH}:/usr/local/bin"
    }
    stages {
        stage('build') {
            steps {
                sh 'docker -v'
            }
        }
    }
}