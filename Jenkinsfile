pipeline {
  agent {
    docker {
      image 'node:6.11.1'
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo '"${env.PATH}"'
        sh 'ls -al'
        sh 'docker -v'
      }
    }
  }
}