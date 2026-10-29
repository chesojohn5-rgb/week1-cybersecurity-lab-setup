# week1-cybersecurity-lab-setup
This is My Cyber Security Lab Setup 

PROJECT OVERVIEW

The idea of this Project is to set up my virtual cybersecurity and pen-testing lab using 7 zip, virtualBox and Kali Linux downloaded files.

This is intended to create an environment where Cyber security tools, network scanning and other security testing activities can be performed safely and repeatedly.


 Objectives

installation of 7 zip

Installation  VirtualBox.

Installation and importing Kali Linux as a virtual machine.

Creating a private NAT Network.

Configuring network connectivity for Kali Linux.

Assigning an IP address to the Kali VM.

Verify network connectivity and DNS resolution.

Take a clean VM snapshot for recovery.

Document the complete setup process.





 Lab Architecture

Tools

 step 1. Download 7-Zip

 step 2 Install VirtualBox
VirtualBox was installed.

 step 3 Create the NAT Network
A dedicated NAT Network was created in VirtualBox.


RAM: 2048 MB
 A shared folder was also configured for transferring required files between the host operating system and the Kali VM.

Step 4. Configure the Kali Linux Network
The Kali Linux network configuration was checked and configured with a consistent IPv4 address.




Step 5. Create a Clean VM Snapshot
After completing the initial configuration, a VirtualBox snapshot was created.


Problems Encountered & Solutions

After i Downloaded Kali Linux in my browser, it reached 3.6 Gb download and stopped for a while then went back to zero. i Downloaded it again and it did the same. So instead of Direct Virtual machine, which was 3.6Gb, i downloaded installer images, which was about 4.7 Gb. It Downloaded completely then i loaded it directly into my VirtualBox because it needed no extraction.

Then When setting it up, manually using commands, when it started petitioning, it froze at 13%, so i had to stop the task and assign 2000 mb RAM instead of 2048 and 1 bit instead of 2 and it Partitioned Successfully.

Another issue finally was the setting up of the network, which Required running of the provided commands because it was a newer Version of Kali Linux, Which was Successful and Now the Network Configuration is Done.

 What I Learned
Ive Learnt about How to Clearly and Setup Kali Linux and how to successfully troubleshoot issue that come your way along the way.

 Documentation
I learned that documenting commands,  screenshots, problems, and solutions is an important part of a professional cybersecurity project.

