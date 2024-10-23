Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

// Jenkinsfile (Declarative Pipeline)
// /* Requires the Docker Pipeline plugin */
// pipeline {
//     agent { docker { image 'node:20.18.0-alpine3.20' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'node --version'
//             }
//         }
//     }
// }

// Jenkinsfile (Declarative Pipeline)
// /* Requires the Docker Pipeline plugin */
// pipeline {
//     agent { docker { image 'python:3.13.0-alpine3.20' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'python --version'
//             }
//         }
//     }
// }
