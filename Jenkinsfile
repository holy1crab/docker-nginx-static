node {
    checkout scm

    def customImage = docker.build("white/docker-nginx-static:latest", ". --rm")

    customImage.inside {
        sh 'echo hello'
    }
}