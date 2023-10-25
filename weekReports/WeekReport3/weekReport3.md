---
name: Kevin Marcelo-Castillo
semester: Fall 23
course: cis106
---
# Week Report 3

# Summary of presentation

### Introduction to Linux

* **What is an operating system?**
 An operating system provides all fundamental software features of a computer. An OS allows you to use the computer's hardware, providing you with the basic tools that make a computer useful.
* **Aside from a kernel, what other parts make an operating system?**
  Command-line shells, graphical user interfaces, utility and productivity programs, and libraries are other things that make an operating system.
* **What is a Linux distribution?**
 A Linux distribution is a complete Linux system package with a Linux kernel, core Unix tools, supplemental software, startup scripts, and an installer.
* **What is Ubuntu?**
 Ubuntu is a Linux distribution that is freely available with both community and professional support.
* **Define the following terms: Open Source, Closed source, free software**
    Open source software may be distributed either for a fee or for free. The source code is distributed with the software. Closed source software is not distributed with the source code and the user is restricted from modifying the code. Free software is distributed with the source code and the software can be obtained for free or a fee.
* **What are the 4 freedoms defined by the free software foundation?**
 The four freedoms defined by the free software foundation is that the software can be used for any purpose, the source code can be examined and modified any way seen fit, the software can be redistributed, and the modified software can be redistributed.

### The Basics of Virtualization


* **What is virtualization?**
  Virtualization is creating virtual versions of something and is often used to run multiple OSs in the same machine.
* **List 3 benefits of virtualization**
  * Allows a machine to run multiple OSs without dual booting
  * Reduces costs by decreasing the physical hardware required to run a network
  * Allows applications to be tested before installing them in a host machine.
* **What is a hypervisor?**
 A hypervisor is a software or hardware in charge of creating, managing, and running virtual machines.
* **What is virtualbox**
 Virtualbox is a x86 and AMD64/Intel64 virtualization product for enterprise and home use. It is also open source.

 ### Exploring Desktop Environments


* **What is a desktop environment? (Provide 3 examples)**
A desktop environment is an implementation of the desktop metaphor made up of a bundle of programs running on top of a computer's operating system, which shares a common GUI.
**Examples:** GNOME, Cinnamon, Fluxbox
* **List 4 common elements of desktop environments**
  * Desktop settings
  * Display managers
  * File managers
  * Icons  

*    **What is Ubuntu’s default desktop environments?**
Ubuntu's default desktop environments are GNOME 3, Debian, Fedora, Red Hat Enterprise Linux, and Oracle Linux.    
*    **What are the official flavors of Ubuntu?**
GNOME, Xubuntu, and Ubuntu Mate are the official flavors of Ubuntu.

### What is a Shell?


* **What is Bash?**
Bash is a program that provides interactive access to the Linux system 
* **How do you access the Linux CLI?**
You access the Linux CLI by using either a terminal emulator or the Linux console. 
* **What is a console terminal?**
A console terminal is a CLI that is accessed by taking the Linux system out of graphical desktop mode and putting it in text mode.
* **What is a terminal emulator?**
A terminal emulator is a program that allows for the access of the Linux CLI. 
* **Provide 3 examples of Linux commands**

`clear` clears the screen

`date` displays the current time and date

`free` displays the amount of free memory

### Managing Software

The `update` command updates ubuntu

**Command for updating Ubuntu:** `sudo apt update; sudo apt upgrade -y`

The `install` command installs the specified package for Ubuntu

**Example:** `sudo apt install blockwars`

The `remove` command removes specified package for Ubuntu

**Example:** `sudo apt remove blockwars`

The `search` command searches for packages that matches the text in quotes

**Example:** `apt search "games"`

Packages are archives that contain the binaries of software, configuration files, and information about dependencies.

A library is reusable code that can be used by more than one function or program.

A repository is a large collection of software available for download.