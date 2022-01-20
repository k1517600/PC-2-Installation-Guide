# PC-2-Installation-Guide
Installation Guide for a Single-Site WAN/LAN PC^2 system



This guide is going to thoroughly teach you how to install the PC^2 System on your PC. This guide assumes the computers are connected on the same network either through LAN or WAN. This guide will be split into multiple chapters which can be found in the table of contents below.
____________________________________________________________

# Table of Contents

1. Download and Set-Up 
2. Configuration
3. Server
4. Administrator
5. Team
6. Problems & Judging
7. Common Issues
8. Contact Us
_________________________________________________________

# Guide


## 1. Download and Set-Up ##

Please ensure you have Java JDK/SDK 1.8+ downloaded. If not, please download from https://www.java.com/download/ie_manual.jsp

### Download ###
1. Download the PC^2 software from https://pc2ccs.github.io/ . If you are asked for an admin account, use JHSCS010 with the password "password"
2. Unzip the software into any directory, preferably outside of the downloads directory.

### Set-Up ### 

#### Editing PATH Environment Variable ####

You will need to add two new values to the path environment value in order to run pc^2. Firstly, open your settings app and navigate to settings. Then click the additional option labeled "Advanced system settings".

From here, click on the "Environment Variables" dialogue, click on "Path" variable under "System Variables" and then click the "Edit" button. 

![image](https://user-images.githubusercontent.com/98120580/150407950-121834e2-b0c4-4b01-8246-65a235f50e04.png)

Once the new menu opens, you're going to create 2 new variables. One will be equal to the bin folder of your Java JDK, usually at "C:/Users/(username here)/.jdks/(jdk name)/bin/", and the other will be equal to your pc2's bin folder. To copy a path, simply navigate to the file or directory that you want to copy, click on the top bar, and copy the resulting text. 

![image](https://user-images.githubusercontent.com/98120580/150408679-c69a45a7-b195-45e3-b191-9cd85413a477.png)


![image](https://user-images.githubusercontent.com/98120580/150408581-15823fa3-77be-474c-8e93-788dfe1ddd6e.png)

## 2. Configuration ##

PC^2 has an editable .ini file that allows for configuration. If you're setting up the server, this file does not need to be touched. Simply move it to the bin folder and skip this step.

If you're setting up pc^2 on a machine meant to be used as a client (Admin, participant, judge, etc), follow along.

Edit the 





