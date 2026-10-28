# Ubuntu Nginx Web Server

My first Linux server administration project.

## Project Goal
Install and configure an Ubuntu Server with Nginx
to host a website and learn basic Linux administration.


### Virtual Disk Configuration

I created a 25 GB virtual hard disk using the VDI format.

I chose dynamically allocated storage so the virtual disk
only uses the space it needs on my actual computer,
instead of reserving all 25 GB immediately.

![Virtual Machine Setup](Screenshots/1-VM-setup.png)


## Network Configuration
Ubuntu automatically received the IP adress 10.0.2.15/24 thought DHCP.

The server uses a virutal network adapter provided by te VirutalBox with NAT networking.

This allows the server to access the internet for updates and software installations.

![Network Configuration](Screenshots/2-Network-configuration.png)


## Storage Configuration

For this server I'll be using the full capacity of our virutal disk of 25 GB for my Ubuntu server.

I picked LVM (Logical Volume Manager) because it makes it easier to manage and resize storage volumes later.

I kept the default guided storage layout because
this is a local web server lab.

![Storage Configuration](Screenshots/3-Storage-configuration.png)


## Text here
