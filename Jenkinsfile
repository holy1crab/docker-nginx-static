pipeline {
    agent none
    stages {
        stage('Example 1') {
            agent {
                dockerfile true
                docker {
                    label 'docker-nginx-static'
                }
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}