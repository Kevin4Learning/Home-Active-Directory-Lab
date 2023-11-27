# Basic Home Lab Active Directory

This repository contains steps on how i set up a basic home lab running Active Directory by Kevin Jackson

# Diagram
![Diagram](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/c639437b-12f1-427d-8573-21183e75209a)


![Diagram](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/c87a2ac0-2ca4-40fe-9ad8-a344cf7fb2a4)


# Install Windows 11 Home
 https://www.microsoft.com/en-us/d/windows-11-home/dg7gmgf0krt0

# Check-And-Enable Virtualization in windows 11


 

# Enabling HYPER-V for use on Windows 11

Download Windows Server 2019 ISO

Create a new virtual machine by clicking "New" in Hyper-V, naming it "Domain Controller," and selecting the "Windows Server" ISO file as the boot media.

# Create Virtual Hard Disk


# Installion Options (ISO)-Windows Server-2019iso

Configure the virtual machine by giving it two network adapters: one for connecting to the internet and the other for the internal network.
# External Virtual Switch


# Internal Virtual Switch

# Install Server 2019 on the virtual machine and assigned IP addressing to internal network.


# Assigned IP Address to Internal Adapter

# Name the Server and Install Active Directory to create the domain.

Configure routing so that clients on the private network can access the internet through the domain controller.

# Remote Access


# Routing role services

# Set up DHCP on the DOMAIN CONTROLLER.











