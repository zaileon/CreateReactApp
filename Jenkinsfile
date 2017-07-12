pipeline {
  agent {
    docker {
      image 'node:6.11.1'
      args '-v /var/run/docker.sock:/var/run/docker.sock'
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