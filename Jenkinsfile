pipeline {
    agent none
    stages {
        stage('Example 1') {
            agent {
                dockerfile {
                    label 'white/docker-nginx-static'
                }
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}