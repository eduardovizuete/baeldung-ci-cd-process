# baeldung-ci-cd-process

Applying CI/CD With Spring Boot
    https://www.baeldung.com/spring-boot-ci-cd

In this tutorial, we'll take a look at the Continuous Integration/Continuous Deployment (CI/CD) process and implement its essential parts.

First, we prepared a Git repository in GitHub and pushed our application there. Then, we used Travis CI as a build tool to build our application from that repository.

After that, we created a Docker image and pushed it to DockerHub.

Next, we added a service that's responsible for static code analysis.

Lastly, we deployed our application to PaaS and accessed it.

## Technologies

- Spring Boot Application
- GitHub Version Control Source
- Travis CI Build Automation
- DockerHub Docker Images
- Codecov Code Analysis
- Heroku Platform as a Service Deploy Application

## URL test app
    https://edviz-baeldung-ci-cd-process.herokuapp.com/actuator/health
