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
When running a Dockers container, the Docker Engine allows Windows to indirectly run Linux based containers. Rather than partitioning
the memory of my machine, the Dockers Engine is able to run the containers. Windows requires a Linux subsystem to be isntalled but the resources 
of the physical machine do not have be be shared. Instead, the Dockers engine runs the containers that contain their own resources allowing for 
more efficient development without having to sacrifice the host resources. The image below shows how the containers are ran:

![dockers](https://github.com/omran-farighi/microservice_architecture/blob/main/Dockers/1756%20(768%C3%97693).png)

Apart from requiring less resources, the containers make development more efficient. Because if their reduced size, containers have less code to transfer and update
on workloads, makign deployment quicker. They can also be started and stopped at anytime. 




