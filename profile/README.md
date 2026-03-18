# Data Science Club

Welcome to the TCC South Data Science Club Git Repo!

## Club Overview

### Mission Statement

## Environment Setup
This section will cover:
- WSL
- Python
- Anaconda Install
- Creating Anaconda Environments
- Common Libraries and Packages
- IDE
- VSCode
- NeoVim
- Git Install

### WSL (Windows Subsystem for Linux)
The [Windows Subsytem for Linux](https://learn.microsoft.com/en-us/windows/wsl/about) (WSL) is a feature on Windows computers that allows you to run a Linux environment on your computer without the need to install a virtual machine / brand new operating system on your system. This may seem pointless right now, but as you progress in your career as a developer, becoming familiar with using Linux is crucial as most server-side applications will be written for and deployed on Linux servers. The Linux environment also comes preinstalled with a host of tools that you will find very useful during your journey as a developer. As such, this step is crucial and is a requirement moving forward.

To install WSL on your machine, I highly recommend following [this](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/) guide. When choosing a distro from the Microsoft store, select the latest LTS release of Ubuntu (24.04 at the time of writing this). Although this guide was written for Windows 10, these same steps will also work on Windows 11.

Once you have WSL installed on your machine, there are a few very big disclaimers that need to be addressd before you continue on with this guide.
1. It is crucial that you understand the difference between installing applications on Windows 10 vs. on Linux Bash.
2. NEVER Modify any Linux files from a Windows application (For example, from VS Code).
3. DO NOT SWITCH TO A DIFFERENT SHELL. You should only be using Bash. Do not try to change this to something like zsh or fish.

If you do not know what the 3rd point means, don't worry about it as it is very unlikely you will do this by mistake. All three of these points will be expaned upon under the Linux guide, here: [Linux and Your Machine](https://github.com/TCC-South-Data-Science-Club/lessons/blob/main/environment/linux-and-your-machine.md)

Speaking of the Linux guide, if you are unfamiliar with the Linux Kernel, I stress that you please look over the guide. At the very least, make sure that you are comfortable with using the command line and know the basic commands. 

### Python
Python is a general purpose, high-level, interpreted programming language developed by Guido van Rossum in 1991. As it is a general puprose language, Python has a large variety of applications, including in web development, automation, artificial intelligence, and data science. Going forward, Python will be the main language you will use as a data scientist, not only in this club, but also in your future career.

If you've ever tried programming on your own before, you might have come across the popular opinion that Python is rather slow, especially when compared to other languages such as C. This notion is not wrong. Compared to C++ for example, Python can run anywhere from 10x - 1000x slower than equivalent C++ code (HUGE generalization as this can depend on various different factors that are beyond the scope of this guide). So why use Python then? If it is truly that slow, what is it that sets Python apart from the multitude of languages that are faster than it? There are several reasons why one might choose Python over another language such as C++, perhaps the biggest of which is the vast ecosystem of libraries that have been written for data manipulation, visualization, and analyzation. These libraries, often written in faster languages such as C or C++, are highly optimized for heavy numerical computation, allowing Python to overcome many of its performance issues. All Python does is act as a high-level interface,allowing programmers to still do computationally intensive work, without the need for implementing complex low-level algorithms.

Python's syntax is also very simple and highly readable. It is one of the easiest languages for beginners to pick up, and one of the fastest languages for developers to write in. 

In our environment, it will not be necessary to install Python by itself, as we will be using Anaconda to manage our python installs and packages through the use of virtual environments.

### Anaconda Install
Anaconda is an open-source distribution of Python and R tailored specifically for data science and machine learning. With the Anaconda distribution comes conda, a Python package and environment manager. Conda allows you to install software packages in isolated environments, allowing you to manage packages on a project by project basis. If this is your first time being introduced to the concept of package management, don't worry if you don't quite understand what that means quite yet or how it can be useful, we will cover it later on during our unit on using packages with Python.

In order to install Anaconda, open a new terminal in the newly installed Ubnutu environment, make sure that you are in your home directory, and copy this command:

'''
curl -O https://repo.anaconda.com/archive/Anaconda3-2025.12-2-Linux-x86_64.sh
'''

After the file is done downloading, install Anaconda by running the following command:

'''
bash ~/Anaconda3-2025.12-2-Linux-x86_64.sh
'''

This will then begin the installer in your terminal. When prompted, enter "yes" to agree to the Anaconda TOS. Then, press "enter" to accept the default installation location of ~/anaconda3. When asked if you would like to initialize conda, type "yes" and hit enter. If all goes well, the Anaconda distribution should be sucessfully installed in your WSL environment. Close and reopen your Ubuntu environment for the installation to take effect. If it was sucessfull, you should see "(base)" before your command line prompt. If the install failed, please drop a message in the Discord or let the organization President know. 

### Creating Ancaonda Evnironments
### Common Libraries and Packages
### IDE
### VSCode
### NeoVim
### Git Install

## Resources
This section contains a list of common resources that we will utilize throughout the course of the club, as well as some extra resources for those who are especially ambitious

