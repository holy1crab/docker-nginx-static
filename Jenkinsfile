node {
    checkout scm

    docker.withRegistry('http://localhost:5000') {
        def customImage = docker.build("white/docker-nginx-static:latest")
        customImage.push()
    }

//    customImage.inside {
//        sh 'echo hello'
//    }
}