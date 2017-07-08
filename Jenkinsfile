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

    env.PATH = "/Users/junfeng/Library/Group Containers/group.com.docker/bin:${env.PATH}"

    stage('test') {
        sh 'docker -v'
    }
}