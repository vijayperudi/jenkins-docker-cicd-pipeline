pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t flask-jenkins-app .' 
            }
        }
        stage('Run') {
            steps {
                sh 'docker run -d -p 5000:5000 flask-jenkins-app'
            }
        }
    }
}