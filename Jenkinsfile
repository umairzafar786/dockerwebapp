node {

    checkout scm

    docker.withRegistry('localhost:443', 'docker-hub') {

        def customImage = docker.build("umairzafar786:443:/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
