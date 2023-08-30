DOCKER STUDY GUIDE

What is a Container?
A way to package applications with all the necessary dependencies and configuration
Portable artifact, easily shared and moved around
Makes development and deployment more efficient
Layer of images
Mostly Linux Base image, because small in size
Application image on top

Where do containers live?
Container repository
Private repositories
Public repository for Docker

Before Containers:
The installation process was different in each OS environment
Many steps where something could go wrong
Developers would have to include a set of instructions on how to configure each package, then Operators would then have to read the instructions to set up the environment
Dependency version conflicts

After Containers
Don't have to install separate packages → Container has own isolated environment
Packages with all needed configuration
One command to install the app
Run the same app with 2 different versions
Developers and Operations work together to package the application in a container
No environmental configuration is needed on the server → except setting up the Docker Runtime

What is Docker?
Docker is a set of platform-as-a-service products that use OS-level virtualization to deliver software in packages called containers

Docker Image
The actual package, the artifact that can be moved around

Docker Container
Container environment is created when you actually start the application

