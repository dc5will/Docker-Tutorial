<h1 align="center">Docker Tutorial</h1>

<p align="center">
  <a href="https://hub.docker.com/">
    <img src="images/Moby-logo.png" alt="Docker Logo" width="320">
  </a>
</p>

## What is this?

Created as a personal reference for learning about Docker. Following the official [Docker Tutorial](https://docs.docker.com/get-started/part2/) for educational purposes.

## Docker Concepts

- What is Docker? 
>- Platform for developers & sysadmins to **build, share, and run** apps with containers. The method of using containers for deploying apps is called *containerization*.
>- Docker separates applications from infrastructure using container technology, similar to how VMs separate the OS from bare metal

- Why should we use Docker?
>- Docker is a useful tool designed to make it easier to create, deploy, and run apps by using containers. Containers allows a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.
>- Build any app in any language using any stack. Dockerized apps can run anywhere on anything. Avoid dependency hell.

- Why is containerization so popular?
>- Flexible: Even the most complex applications can be containerized.
>- Lightweight: Containers leverage and share the host kernel, making them much more efficient in terms of system resources than virtual machines.
>- Portable: You can build locally, deploy to the cloud, and run anywhere.
>- Loosely coupled: Containers are highly self sufficient and encapsulated, allowing you to replace or upgrade one without disrupting others.
>- Scalable: You can increase and automatically distribute container replicas across a datacenter.
>- Secure: Containers apply aggressive constraints and isolations to processes without any configuration required on the part of the user.

- What are core components of Docker?
>- Docker Daemon = Docker engine that runs on the host machine
>- CLI used to interact with the Daemon

- What are the Docker workflow components?
>- Docker Image = Holds the environment & our application
>- Docker Container = Created from images. Start, stop, move, and delete containers.
>- Docker Registry = Public & private repos used to store images and collaborate with others (similar to GitHub)
>- Dockerfile = Automate image construction

What does Kubernetes do with Docker?
>- Tool to automate the scheduling and deployment of Docker containers. Provides framework to run distributed systems resiliently and takes care of scaling and failover for our application, provides deployment patterns, etc.



## Resources
- [YouTube Explanation by CBT Nugget](https://www.youtube.com/watch?v=aLipr7tTuA4)
