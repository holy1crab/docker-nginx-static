pipeline {
    agent none
    stages {
        stage('Example 1') {
            agent {
                dockerfile true
                label "some-label"
            }
            steps {
                sh 'ls /usr/share/nginx/html'
            }
        }
    }
}