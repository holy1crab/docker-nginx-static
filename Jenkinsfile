pipeline {
    agent none
    stages {
        stage('Test') {
            agent {
                dockerfile true
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}