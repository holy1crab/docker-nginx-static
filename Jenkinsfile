pipeline {
    agent {
        dockerfile {
            filename "Dockerfile"
        }
    }
    stages {
        stage('Test Stage') {
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}