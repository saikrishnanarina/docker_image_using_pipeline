node {
    checkout scm

    docker.withRegistry('https://hub.docker.com', 'dockerHub') {

        def customImage = docker.build("sainarina22/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
