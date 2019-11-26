node {

    checkout scm

    docker.withRegistry('http://localhost:8091/testreg', 'portainer') {

        def customImage = docker.build("umairzafar786/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
