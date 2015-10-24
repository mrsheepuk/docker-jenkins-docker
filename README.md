# docker-jenkins-docker
This is a simple wrapper on the official Jenkins image, adding the docker binaries and moving the UID to 1100.

To use docker commands from inside the Jenkins instance, the docker port will need to be bind-mounted from the host machine.

Part of the [NodeDevEnvInABox](https://github.com/mrsheepuk/NodeDevEnvInABox/).
