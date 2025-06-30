
# Project 1: Foundational Linux Server & Networking Lab

## Project Overview
This project involved setting up a virtual computer (Ubuntu Linux server) on my main machine using VirtualBox. I configured its network, installed a basic website (Apache2), set up a firewall, and learned how to securely log in using SSH keys. I also practiced fundamental Linux command-line administration, including file management and user administration.

## Technologies Used
* **Operating System:** Ubuntu Server 24.04 LTS
* **Virtualization:** Oracle VirtualBox
* **Web Server:** Apache2
* **Firewall:** UFW (Uncomplicated Firewall)
* **Remote Access:** SSH (Secure Shell) with Key-Based Authentication
* **Networking:** Static IP configuration, TCP/IP, DNS
* **Command Line Interface (CLI)**
* **Git / GitHub** (for documentation and version control)

## Key Features & Skills Demonstrated
* **Virtual Machine Setup:** Successfully provisioned and configured an Ubuntu Server VM.
* **Network Configuration:** Configured dual-network adapters (Host-Only & NAT) and set a static IP.
* **Web Server Deployment:** Installed and verified Apache2 web server functionality.
* **Firewall Management:** Configured UFW to secure access, allowing only necessary ports (SSH, HTTP, HTTPS).
* **Secure Remote Access:** Implemented SSH key-based authentication for enhanced security and convenience.
* **Linux CLI Fundamentals:** Navigated the file system, managed files and directories (`ls`, `cd`, `mkdir`, `rm`, `cp`, `mv`, `cat`, `nano`).
* **User & Permissions Management:** Created new users and managed `sudo` privileges.
* **Troubleshooting:** (You can add specific examples here if you remember any, e.g., "Troubleshot SSH connectivity issues by verifying firewall rules and daemon status.")

## Setup Instructions (High-Level)
To replicate this lab environment:
1.  Install VirtualBox on a Windows host machine.
2.  Download the Ubuntu Server 24.04 LTS ISO.
3.  Create a new VM in VirtualBox, attaching the Ubuntu ISO.
4.  Configure network adapters for Host-Only and NAT.
5.  Install Ubuntu Server, setting up a user with sudo privileges.
6.  Follow steps to configure static IP, install Apache2, set up UFW, and implement SSH key-based authentication.

## Screenshots (Optional but Recommended)
![Apache "It works!" page](https://raw.githubusercontent.com/cdm-projects/Linux-Server-Fundamentals/main/images/apache_it_works.PNG)
![Successful SSH Login](https://raw.githubusercontent.com/cdm-projects/Linux-Server-Fundamentals/main/images/ssh_login.PNG)
![UFW status showing allowed rules](https://raw.githubusercontent.com/cdm-projects/Linux-Server-Fundamentals/main/images/ufw_status.PNG)

---
*This project was completed as part of a structured IT & Cybersecurity learning roadmap.*
