// pipeline {
//     agent any // { docker 'node:6.3' }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'java --version'
//             }
//         }
//     }
// }

node {
    checkout scm

    env.PATH = "${tool 'docker'}/bin:${env.PATH}"

    stage('test') {
        sh 'docker -v'
    }
}