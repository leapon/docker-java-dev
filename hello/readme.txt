Docker for java development
https://hub.docker.com/_/java/

$docker build -t my-java-app .
Sending build context to Docker daemon  5.12 kB
...
Successfully built b800e9924753

$docker run -it --rm --name my-running-app my-java-app
Hello, World

