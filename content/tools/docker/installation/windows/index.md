---
title: "Docker: Windows"
---

The best way to install Docker for Windows is by using Docker Desktop. 
Docker Desktop is an easy-to-use application that allows you to run 
containers on your Windows machine. It includes both Docker Engine and Docker 
Compose, providing a complete development environment for containerized applications.

**Warning:** Docker is a resource-intensive application that may consume a 
significant amount of disk space, memory, and CPU resources. 
Installing and running Docker on your system may slow down your machine, 
especially if it has limited resources. Make sure your system meets 
the [minimum requirements](https://docs.docker.com/get-docker/) before 
installing Docker, and consider monitoring resource usage to ensure optimal performance.


Follow these steps to install Docker Desktop for Windows.

1. Ensure your system meets the requirements:

  - Windows 10 64-bit: Pro, Enterprise, or Education (Build 16299 or later) or Windows 11.

  - Virtualization must be enabled in the BIOS. You can usually find this setting under "CPU Configuration," "Virtualization," or "VT-x" settings.

2. Download Docker Desktop for Windows from the official Docker website. (600+ MB).

3. Run the installer:

  - Double-click on the downloaded Docker Desktop Installer.exe file to start the installation process.
  - Follow the on-screen instructions, accepting the default settings or customizing them as needed.

4. Start Docker Desktop:

  - After the installation is complete, Docker Desktop should start automatically. - If it doesn't, you can launch it from the Start menu.
  - You will see the Docker icon in the system tray, indicating that Docker is running. 
  - Right-click on the icon and select "Dashboard" to open the Docker Desktop dashboard.
 
5. Verify the installation:

  - Open a command prompt or PowerShell window.
  - Run the following command to check the Docker version:

  `docker --version`

6. Run a test container to ensure that Docker is working correctly:

  `docker run hello-world`


### Save Resources

To stop Docker Desktop when you are not using it:

1. Locate the Docker icon in the system tray, which is typically located in the lower-right corner of the screen.

1. Right-click on the Docker icon to open the context menu.

1. Click on "Quit Docker Desktop" or "Exit" to stop Docker Desktop.
