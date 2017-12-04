pipeline {
    agent {
        dockerfile {
            label "white/docker-nginx-static"
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