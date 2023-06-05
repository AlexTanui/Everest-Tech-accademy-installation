# Installation Guide for React, JavaScript, Ruby, and Ruby on Rails

This guide provides step-by-step instructions for setting up your development environment to start coding in React, JavaScript, Ruby, and Ruby on Rails on Windows using WSL 2, Linux, and macOS.

## Prerequisites

Before proceeding with the installation, make sure your system meets the following prerequisites:

- Operating system: Windows (WSL 2), Linux, or macOS
- Internet connectivity
- Sufficient disk space for the installations

## Windows (WSL 2) Setup

1. Install Windows Subsystem for Linux (WSL) and update it to WSL 2 by following the instructions provided in the official Microsoft documentation: [WSL Installation Guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
2. Install a Linux distribution from the Microsoft Store, such as Ubuntu 20.0/22.0.
3. Launch the installed Linux distribution and complete the initial setup process by providing a username and password.

# Download and Install Windows Subsystem for Linux (WSL) 2

To download and install Windows Subsystem for Linux (WSL) 2 on Windows, follow these steps:

1. Open the **Start** menu and search for "Turn Windows features on or off".
2. Select the option **Turn Windows features on or off**.
3. Scroll down the list and locate **Windows Subsystem for Linux**.
4. Check the box next to it and click **OK**.
5. Windows will start enabling the feature, and you may be prompted to restart your computer. If so, save any unsaved work and proceed with the restart.
6. After the restart, open the Microsoft Store application.
7. Search for "Linux" or the specific Linux distribution you want to install, such as "Ubuntu" or "Debian".
8. Select the desired distribution and click **Install**.
9. Wait for the installation process to complete. This may take a few minutes.
10. Once the installation is finished, you can launch the installed Linux distribution from the Start menu or by typing its name in the search bar.
11. The first time you launch the distribution, it will perform an initial setup process. Follow the on-screen instructions to create a new user account and set a password.

Congratulations! You have successfully downloaded and installed Windows Subsystem for Linux 2 (WSL 2) on your Windows system. You can now use Linux distributions within Windows and enjoy the benefits of a Linux environment.
## Git installation
# Link Git in WSL 2 and Linux

To link Git in WSL 2 and Linux, follow these steps:

1. Open your Linux distribution terminal (e.g., Ubuntu) within WSL 2 or open a Linux terminal if you're using a native Linux distribution.


# Update package lists
sudo apt update
Install Git by running the following command:
bash
Copy code
# Install Git
sudo apt install git
Configure your Git username and email by running the following commands:

# Set Git username
``git config --global user.name "Your Name"``

# Set Git email
``git config --global user.email "youremail@example.com"``
Replace "Your Name" with your desired name and "youremail@example.com" with your actual email address.

Verify the Git installation by running the following command:

# Verify Git installation
``git --version``
You should see the Git version information displayed in the terminal.

Congratulations! You have successfully linked Git in WSL 2 or Linux. You can now use Git commands to manage your repositories within the Linux environment.

## Linux Setup

1. Open your terminal.
2. Update the package lists by running the following command:
   ```bash
   ``sudo apt update``

##macOS Setup
##Open your terminal.
##React and JavaScript Setup

Install Node.js and npm (Node Package Manager) by following the installation guide provided earlier in this document: Installation Guide for Node.js.
Verify the installations by running the following commands:


``node --version``
``npm --version``

Ruby and Ruby on Rails Setup
Install Ruby by running the following commands:

Windows (WSL 2):


``sudo apt install ruby``
Linux:


``sudo apt install ruby``
macOS (using Homebrew):


``brew install ruby``
Verify the Ruby installation by running the following command:


``ruby --version``
Install Ruby on Rails by running the following command:


``gem install rails``

Verify the Ruby on Rails installation by running the following command:


``rails --version``

Congratulations! You have successfully set up your development environment for React, JavaScript, Ruby, and Ruby on Rails on Windows using WSL 2, Linux, or macOS. You are now ready to start coding!

## Additional Resources

- [React Documentation](https://reactjs.org/docs)
- [Node.js Official Website](https://nodejs.org)
- [Ruby Language Website](https://www.ruby-lang.org)
- [Ruby on Rails Official Website](https://rubyonrails.org)

**Author**: Alex Tanui (Software Engineer Everest tech Hub)#
