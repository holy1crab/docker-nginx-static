pipeline {
    agent {
        dockerfile {
            filename "Dockerfile"
            label "test-2"
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