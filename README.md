# Ubuntu Workstation Installation Guide 
This guide provides detailed instructions for installing Ubuntu on your workstation efficiently and correctly.

## Introduction
Welcome to this comprehensive guide on installing Ubuntu on your workstation. Whether you're setting up a development environment, or a personal workstation this document will walk you through each step of the process, ensuring a smooth and successful installation. Follow these instructions carefully to get Ubuntu up and running on your system. 
## System requirements 

 -   A laptop or PC with at least 25GB of storage space.
 - A flash drive (12GB or above recommended).
 ## Download Ubuntu 
You'll need to download the latest LTS version of Ubuntu. Visit the [official Ubuntu website](https://ubuntu.com/download) and choose the appropriate version for your workstation. For most users, the "Ubuntu Desktop" version is recommended. Click the download link and save the ISO file to your computer. This ISO file will be used to create a bootable USB drive or DVD for the installation process.
## Creating a Bootable USB Drive 
To install Ubuntu Desktop, you need to write your downloaded ISO to a USB stick to create the installation media. This is not the same as copying the ISO, and requires some bespoke software. 

We'll be using [balenaEtcher](https://etcher.balena.io/), as it runs on Linux, Windows and Mac OS. Choose the version that corresponds to your current operating system, download and install the tool.
![enter image description here](https://assets.ubuntu.com/v1/a40f15d2-select-iso.png) 
## Installation Process 
 ###  Boot from the USB Drive 
 -   Insert the bootable USB drive into your workstation.
-   Restart the computer and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, DEL, or ESC during startup).
-   Set the USB drive as the primary boot device.
-   Save the changes and exit the BIOS/UEFI settings. Your computer should now boot from the USB drive.

### Installation setup 
 You'll be prompted to choose between **Interactive installation** and **Automated Installation**. The interactive option is the standard route, but more advanced users can use the automated installation option to import a configuration file from a web server to standardise multiple installs and add further customisations. An example tutorial for Automated installation is available [here](https://blog.local-optimum.net/getting-started-with-autoinstall-on-ubuntu-desktop-24-04-lts-147a1defb2de).  We'll be using the  **Interactive installation**.  
 For more detailed Setup follow this link [Here](https://ubuntu.com/tutorials/install-ubuntu-desktop#5-installation-setup).
 ### Types of Installation 
 Ubuntu allows two different types of installation method 
 -  **Erase disk and install Ubuntu**. 
 -  **Installing Ubuntu alongside another operating system** 

For setting up a workstation it is best to go with first option **Erase disk and install Ubuntu**.  For mored detailed information follow this link [Here](https://ubuntu.com/tutorials/install-ubuntu-desktop#6-type-of-installation).
### Follow the On-Screen Instructions 
During the installation process, carefully follow the on-screen instructions presented by the Ubuntu installer. These instructions will guide you through each step, including selecting your location , preferred language, configuring installation settings, partitioning your disk (if necessary), setting your time zone, choosing your keyboard layout, and creating a user account. Pay close attention to these prompts to ensure a smooth and successful installation of Ubuntu on your workstation.  You can also follow this entire instructions [Here](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview).

### Caveats During Installation and Turning Off BitLocker
When installing Ubuntu on a machine that previously ran Windows, you may encounter the need to disable BitLocker encryption, particularly when opting for the **Erase disk and install Ubuntul** method. To disable BitLocker encryption, navigate to **Settings > Privacy & Security**, then proceed to **Device Encryption**. Here, toggle off Device Encryption. Following this, restart the booting process to ensure a smooth transition. 

![Turn off bitlocker](https://res.cloudinary.com/dlg5xuebc/image/upload/v1716191604/snap_ubuntu_bitlocker_b4qkhl.png) 

# Additional Resources 

 - [Step by Step guide by Official Ubuntu website](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) 
 
 # Conclusion
Congratulations on installing Ubuntu! You've entered a world of open-source computing with endless possibilities. Enjoy the versatility, performance, and community support that Ubuntu offers. Welcome to the Ubuntu family!

# More 

 -  Setting up Nodejs in Ubuntu [Here](#) 
 - Setting up React Native in Ubuntu [Here](#)
