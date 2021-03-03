# Dockers Part I

## Set Up
Setting up Dockers on Windows was a much more involved process unlike a Mac which is Linux based. After installing Dockers, I had to install the 
Windows Subsystem for Linux. Because I am a Windows Insider, all I had to do was run the command prompt: wsl --install.

Once the subsystem was installed, I was able to successfully boot up Dockers. Following the tutorial, the first thing I did was clone the "Getting Started" repository.
This repository contains everythign I need to create an image and run it as a container.

![step one](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/Screenshot%20(94).png)

Once the repository was cloned, the next step was to build and image. This would provide any files or code I'd need to run a container. This process would take a few minutes
beacuse there is so much data required to build the image.

![step two](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/Screenshot%20(95).png)

Based on the image I just created from the sample, I could now run a container.

![step 3](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/Screenshot%20(96).png)

If I wanted to run the container again, the images tab would show all the images I have created. All I have to do is run it and the container will start up.

![run part 1](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/Screenshot%20(100).png)
![run part 2](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/Screenshot%20(101).png)


## What is going on?
When I am running a Dockers container, the Docker Engine allows Windows to natively run Linux based containers. Rather than partitioning
the memory of my machine, Dockers uses lightweight containers that have their own private resources. Instead of a virtual machine, the containers
are a small virutal environment which allows for more efficient software development.




