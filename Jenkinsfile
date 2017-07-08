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

    env.PATH = "${tool 'Maven 3.5.0'}/bin:${env.PATH}"

    stage('test') {
        sh 'mvn -version'
    }
}