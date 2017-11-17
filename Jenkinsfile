pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage('Test') {
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}