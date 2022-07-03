pipeline {
    agent {
         docker { 
              image 'debian:latest'
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
