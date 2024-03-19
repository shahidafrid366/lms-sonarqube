# CI/CD FOR LMS REACT APPLICATION
## Prerequisites
    > WGET
    > GIT
    > JAVA 11
    > JENKINS
    > DOCKER           	
## Brief review about  project
    1. We need to two instance one for master (jenkins) and Slave (docker container)
    2. Docker installed in  slave  Server(ubuntu)
    3. Jenkins as Master in server (ubuntu)
    4. In Docker slave server install docker, java11 and create a docker network with name lmsnetwork
    5. In Jenkins Master server configure node as docker server as slave
    6. In Jenkins server create pipeline backend pipeline  and test backend it should be up and running.
    7. Once the backend is running Update the backend url in frontend in frontend /webapp .env file.
    8. Now create a Frontend pipeline .

