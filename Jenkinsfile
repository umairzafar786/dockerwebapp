node {

    checkout scm

    docker.withRegistry('https://umairzafar7864c:443', 'docker-hub') {

        def customImage = docker.build("umairzafar7864c:443/dockerwebapp1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
