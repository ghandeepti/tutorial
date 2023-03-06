
/* Requires the Docker Pipeline plugin */
// pipeline {
//     agent { docker { image 'maven:3.9.0-eclipse-temurin-11' } }
//     stages {
//     environment {
//                       HOME="."
//                     }
//         stage('build') {
//             steps {
//                 sh 'mvn --version'
//             }
//         }
//     }
// }
//
pipeline {
        agent { docker { image 'maven:3.9.0' } }
        stages {
            stage('build') {
                environment {
                  HOME="."
                }
                steps {
                    bat 'mvn --version'
                }
           }
        }
    }