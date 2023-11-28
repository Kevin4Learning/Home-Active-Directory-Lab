# Basic Home Lab Active Directory
This repository provides instructions for setting up a basic home lab with Active Directory. The guide will walk you through the steps using Hyper-V, ensuring active participation to enhance understanding of Active Directory and Windows networking intricacies.

# Diagram
![Screenshot (135)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/3e776ac6-b03e-4d3f-a92a-ed16512f0336)


# Install Windows 11 Home(https://www.microsoft.com/en-us/d/windows-11-home/dg7gmgf0krt0)
 https://www.microsoft.com/en-us/d/windows-11-home/dg7gmgf0krt0


# Check-And-Enable Virtualization in Windows 11
# Enabling HYPER-V for use on Windows 11
![Screenshot (136)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/d37e5739-4d5f-4ebd-8fff-0480ab4f5732)



# Download Windows Server 2019 ISO
https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019


# Create Virtual Hard Disk
![Screenshot (137)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/7de63b63-90a2-4303-bda7-52a04f19476c)


# Installion Options (ISO)-Windows Server-2019iso
![Screenshot (138)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/0e1a17d0-1725-4df8-a8f8-a299a88c8ddd)


Configure the virtual machine by giving it two network adapters: one for connecting to the internet and the other for the internal network.
# External Virtual Switch
![Screenshot (139)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/72fb2ec7-b4f1-451a-a467-fc18ba60a2d2)


# Internal Virtual Switch
![Screenshot (140)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/5897d31f-c447-4248-aabc-ecde80658989)


# Install Server 2019 on the virtual machine and Assigned IP addressing to internal network.
![Screenshot (141)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/70d5fa03-011a-43f1-83c1-fde24c126fbb)


# Name the Server and Install Active Directory to create the domain.
![Screenshot (142)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/795153a4-4655-40b8-b8b5-aef021fdb0ce)



Configure routing so that clients on the private network can access the internet through the domain controller.

# New password prompt/ Log Hours/Exp-Date
![Screenshot (143)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/a79af54e-8ea4-46c4-b65e-322b350ca529)

# Remote Access
![Screenshot (144)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/fe9d44ff-9445-441f-86a5-dd949ef9e27e)


# Routing role services
![Screenshot (174)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/eb641f13-e2cc-430c-bb7b-6c4def10eef0)


# Set up DHCP on the DOMAIN CONTROLLER.
![Screenshot (175)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/47c8fa61-32ac-4174-9f81-67b704ddd329)


# IPv4 Address assignment://Wizard View//
![Screenshot (172)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/3631d69f-afc3-4c8d-bc45-009859af8d6e)


# IPv4 Address assignment://Local Properties View
![Screenshot (173)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/eccac88e-1e8b-47b4-8bb9-884aeee6bf2e)


# Run the Power Shell script to create 360 users in Active Directory.

Note:Power Shell ISE (Admin)
                  CMD: Set_ExecutionPolicy Unrestricted
![Screenshot (148)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/817933fc-b288-4f69-bd66-8ac6247b0c03)


# Create a new virtual machine name "Client-1" and install windows 11 on it.
![Screenshot (149)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/4a5d1943-d049-45fe-bb76-fae572792372)


# Connect the client machine to the private network and join it on the domain.
![Screenshot (150)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/f8ef1cad-13c4-4342-b978-5236a63bd602)


# Joining to Domain
![Screenshot (151)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/c69f17b7-2578-46cb-ae35-de2b6ed15bca)


# Log into the client machine with a domain account.
![Screenshot (152)](https://github.com/Kevin4Learning/Home-Active-Directory-Lab/assets/150920288/1398423b-a31d-41cf-a9a2-37e436f9303a)















