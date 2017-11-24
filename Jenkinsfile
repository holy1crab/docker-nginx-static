pipeline {
    agent none
    stages {
        stage('Build Image') {
            agent {
                filename "Dockerfile"
                label "docker-label"
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}