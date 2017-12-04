pipeline {
    agent {
        dockerfile {
            label "TestDockerImage"
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