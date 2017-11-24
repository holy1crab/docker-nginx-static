pipeline {
    agent none
    stages {
        stage('Example 1') {
            agent {
                dockerfile true
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}