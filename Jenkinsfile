node {

    checkout scm

    docker.withRegistry('https://localhost:443', 'docker-hub') {

        def customImage = docker.build("umairzafar7864c:443/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
