pipeline {
    agent none
    stages {
        stage('Test') {
            agent {
                label 'white/docker-nginx-static'
                dockerfile true
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}