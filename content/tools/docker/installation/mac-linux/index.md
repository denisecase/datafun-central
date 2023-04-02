---
title: "Docker: Mac/Linux"
---

The best way to install Docker for Mac and Linux is by using Docker Desktop 
(for Mac) and Docker Engine (for Linux). Docker provides a complete development 
environment for containerized applications.

**Warning:** Docker is a resource-intensive application that may consume a significant amount of disk space, memory, and CPU resources. Installing and running Docker on your system may slow down your machine, especially if it has limited resources. Make sure your system meets the [minimum requirements](https://docs.docker.com/get-docker/) before installing Docker, and consider monitoring resource usage to ensure optimal performance.

Follow these steps to install Docker on Mac and Linux.

### For Mac:

1. Ensure your system meets the requirements:

   - macOS 10.14 (Mojave) or later

2. Download Docker Desktop for Mac from the [official Docker website](https://www.docker.com/products/docker-desktop).

3. Run the installer:

   - Double-click the downloaded Docker Desktop Installer.dmg file and follow the on-screen instructions.

4. Start Docker Desktop:

   - After the installation is complete, Docker Desktop should start automatically. If it doesn't, you can launch it from the Applications folder.
   - You will see the Docker icon in the menu bar, indicating that Docker is running.

5. Verify the installation:

   - Open a Terminal window.
   - Run the following command to check the Docker version.

    `docker --version`


6. Run a test container to ensure that Docker is working correctly.

    `docker run hello-world`


### For Linux:

1. Choose the appropriate installation instructions for your Linux distribution from the [official Docker Engine documentation](https://docs.docker.com/engine/install/).

2. Follow the provided instructions to install Docker Engine on your system.

3. Verify the installation.

   - Open a Terminal window.
   - Run the following command to check the Docker version.

    `docker --version`

4. Run a test container to ensure that Docker is working correctly.

    `docker run hello-world`


### Save Resources

Docker takes a lot of resources.
You may want to stop Docker when you are not using it.

#### For Mac

1. Locate the Docker icon in the menu bar, which is typically located in the upper-right corner of the screen.
2. Click on the Docker icon to open the dropdown menu.
3. Click on "Quit Docker Desktop" or "Exit" to stop Docker Desktop.

#### For Linux

1. Open a Terminal window.
2. Run the following command to stop the Docker daemon.

`sudo systemctl stop docker`

To start Docker again, simply launch the application from the Applications folder (Mac) or run the following command in a Terminal window (Linux):

`sudo systemctl start docker`
