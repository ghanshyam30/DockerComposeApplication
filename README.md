# DockerComposeApplication
An application of you tube tutorial where we will create a web application frontend being PHP and backend being python flask platform.
Video url - https://www.youtube.com/watch?v=Qw9zlE3t8Ko

Goal -
    1. Learn to create containers for different purposes
        FrontEnd - PHP container
        Backend  - Python container
    2. Create compose file to deploy both of them and add a dependency.
    3. PHP container will not need a docker file, we will write everything about it in docker-compose itself
    4. Python container will have its own docker file and we will use it in docker-compose. This container will have dependency on Frontend container.
