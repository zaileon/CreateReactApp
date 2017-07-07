pipeline {

    agent { docker 'node:6.3' }
    stages {
        stage('Checkout'){
            checkout scm
        }

        stage('Test'){

            env.NODE_ENV = "test"

            print "Environment will be : ${env.NODE_ENV}"

            sh 'node -v'
        }

    //    stage('Cleanup'){

    //      echo 'prune and cleanup'
    //      sh 'npm prune'
    //      sh 'rm node_modules -rf'

    //      mail body: 'project build successful',
    //                  from: 'zaileon@gmail.com',
    //                  replyTo: 'zaileon@gmail.com',
    //                  subject: 'project build successful',
    //                  to: 'zaileon@gmail.com'
    //    }
    }
}
