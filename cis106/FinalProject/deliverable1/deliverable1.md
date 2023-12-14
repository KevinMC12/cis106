---
name: Kevin Marcelo-Castillo
semester: Fall 2023
course: CIS 106 Linux Fundamentals
---

# Deliverable 1

## Concepts I don't understand
* systemctl
* systemd
* server block
* chown
  


## What is a web server? Hardware and software side
A web server on the hardware side is a computer that stores web server software and a website's component files (HTML documents, images). It connects to the internet and supports a physical data interchange with other devices connected to the web. 

A web server on the software side include parts that control how web users access hosted files. A HTTP server is software that understands URLs and HTTP (the protocol that browsers use to view webpages) and it can be accessed through the domain names of the websites it stores and delivers the content of those domains to the end user.

## What are some different web server applications?
| Application Name | License            | Website                  |
| ---------------- | ------------------ | ------------------------ |
| Apache           | Apache License 2.0 | https://www.apache.org/  |
| Nginx            | F5 standard EULA   | https://www.nginx.com/   |
| Caddy            | Apache License 2.0 | https://caddyserver.com/ |

### Apache
Apache is a web server that powers most of the websites in the world. It is open-license, which enables everybody to use this web server. It is available on Linux, Windows, MacOS, and other platforms. It also has lots of functionality through modules to fit anybody's needs.

### Ngnix
Ngnix is an open-source software that is used for load balancing, media streaming, caching, and reverse proxying. The advantages of using this web server is having FastCGI caching, static file handling, access control, and error redirection. Some web developers prefer Nginx over Apache due to these features.

### Caddy
Caddy is similar to Nginx, except that it is more simplified. It enables HTTPS by default, has no dependencies, and can be used as a library in other programs.

## What is virtualization?
Virtualization is technology used to make virtual representations of servers, networks, and physical machines. Virtual software emulates the functions of hardware on a server or a client. The main benefits of virtualization is that it allows a computer to run multiple operating systems and reduces costs by lowering the amount of hardware necessary for a network. The computer requires a good CPU and a sufficient amount of RAM and storage in order to virtualize. 

## What is virtualbox?
Virtualbox is an open-source virtualization product that is used for enterprise and for home use. It allows for users to deploy operating systems, desktops, and servers as virtual machines. It runs on Linux, Windows, Solaris, and Macintosh. The benefits of Virtualbox are that web developers can test their websites before deploying them, companies can reduce their costs by using Virtualbox to virtualize, and it allows for users to try out other operating systems without having to purchase new hardware. The snapshot feature also allows for users to return to any state of a virtual machine.

## What is a virtual machine?
A virtual machine (VM) is a computer resource that uses software to emulate hardware to run programs and apps. One or more guest machines run inside the physical host machine. Each virtual machine inside the physical host machine operates separately of each other. VMs are used to run programs that require different operating systems, to test applications in a safe environment, and to perform tasks that might be too risky for a host machine, like accessing files that could contain viruses.

## What is Ubuntu Server?
Ubuntu Server is a server operating system developed by Canonical Ltd that runs on all major architectures (x86, ARM v7). Ubuntu is a server platform that can be used to make websites, email servers, file and print servers, cloud services, and more. It can also be used as a way to make a simple home network and has the ability to assign super user (sudo) tasks, which makes administration easier. 

## What is a firewall?
A firewall is a network security device that monitors incoming and outgoing network traffic and either allows or blocks data packets based on security rules. Its main purpose is to block any malicious traffic, like hackers and viruses. There are different types of firewalls, such as packet-filtering firewalls, where they examine packets and block them if they do not meet a set of security rules, and proxy firewalls, where they monitor traffic for layer 7 protocols, like HTTP and FTP.

## What is SSH?
SSH (Secure Shell) is a protocol used to securely send commands to a computer over an unsecured network. SSH sets up a connection between a user and a server. It encrypts data during the connection so that users outside it cannot understand the data unless it is decrypted. SSH also has the ability to tunnel, which is a method for moving packets across a network using a path that it ordinarily would not use. It is often used for controlling servers remotely, transferring files, and managing infrastructure.