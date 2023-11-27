# Basic Home Lab Active Directory

This repository contains steps on how i set up a basic home lab running Active Directory by Kevin Jackson

# Diagram

![Screenshot (135)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/3e776ac6-b03e-4d3f-a92a-ed16512f0336)


# Install Windows 11 Home
 https://www.microsoft.com/en-us/d/windows-11-home/dg7gmgf0krt0



# Check-And-Enable Virtualization in Windows 11
# Enabling HYPER-V for use on Windows 11
![Screenshot (136)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/d37e5739-4d5f-4ebd-8fff-0480ab4f5732)



# Download Windows Server 2019 ISO
https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019


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











