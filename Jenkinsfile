pipeline {
    agent any // { docker 'node:6.3' }
    environment {
        PATH = "${PATH}:/usr/local/bin"
    }
    stages {
        stage('build') {
            steps {
                echo "${env.PATH}"
                sh 'docker -v'
            }
        }
    }
}