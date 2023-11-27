<h1 Home-Active Directory-Lab h1>
< img src= "Screenshot(135).PNG"


This repository contains steps on how i set up a basic home lab running Active Directory.

# Diagram

 Install windows 11 Home

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











