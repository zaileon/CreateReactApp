pipeline {
    agent any // { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                echo "${env.PATH}"
                sh 'docker -v'
            }
        }
    }
}