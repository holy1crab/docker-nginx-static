node {
    checkout scm

    def customImage = docker.build("white/docker-nginx-static:latest")

    customImage.inside {
        sh 'echo hello'
    }
}