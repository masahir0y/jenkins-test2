pipeline {
    agent {
         docker { 
              image 'masahir0y/debian:latest'
         }
    }
    stages {
        stage('build') {
            steps {
                sh 'echo hello'
            }
        }
    }
}
