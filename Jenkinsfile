pipeline {
   agent any
    stages {
        stage('Build docker image') {
            steps {
                sh 'docker build -t djawed22/repo:latest .'
            }
        }
       
    }

}