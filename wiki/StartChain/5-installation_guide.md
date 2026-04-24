---
Distros: Linux Mint
---

To follow this guide, you will need:
- A working system
- A USB Flash Drive you are willing to clean (around 8GB should be enough)
This article is primarily written for people who are switching **from** Windows 8.1 through 11 to Linux.

## Before you begin (important)
This guide is specifically for people who will *only* be using Linux from here on out. Your Windows, and all the contents involved with it, will be *gone* after this. Make sure to export any documents, IDs, passwords, work, or anything else to a cloud storage such as [Google Drive](https://drive.google.com), [OneDrive](https://onedrive.live.com/login), or [DropBox](http://dropbox.com/)

## Linux Mint

### *1* Setup

#### *1.1* **Acquire an installation image**

Visit the [download](https://www.linuxmint.com/download.php) page on the official Linux Mint site. There are a few options to choose from, but this guide will use the Cinnamon Edition. Click on the big "Download" near "Cinnamon Edition", scroll down, and download it from any of the Locations. They all provide the exact same file, but if you have trust issues, you can select the 2nd "Linux Mint" option.

#### *1.2* **Preparing installation media**

This guide recommends using [Rufus](https://rufus.ie/en/) to write to the USB. It's completely free and has no ads.

To use Rufus:
- Open Rufus
- Plug in the USB drive you wish to use
- Select it in the "Device" dropdown menu at the top
- Select your Linux Mint file by pressing 'Select' and going to the folder you downloaded it to and selecting the file
- Skip the rest of the options, press start and accept any popups (**This WILL erase ALL data on the Flash Drive.**)

### *2* Installation

#### *2.1*
Plug in the Flash Drive and shut down the computer.
#### *2.2* Enter the computer's BIOS

Getting into the BIOS will vary depending on your hardware. The general method is to (with your installation media plugged in) turn off the machine and when turning it on again spamming the key to enter the BIOS setup. The hard part is knowing which key to press. Common BIOS keys are: Del, F1, F2, F10, F11, F12 or Esc. Some start-up screens will display it or you could find your motherboard or manufacturers manual, however brute force will eventually work.

#### *2.3* Disabling secure boot

Many Linux distributions do not setup secure boot keys especially not during installation so it must be disabled. The process described here will be different depending on BIOS.

To do this navigate to the 'Boot' tab in your BIOS and disable secure boot.

#### 2.4 Change boot order or enable boot menu

If your BIOS has the open for a dedicated boot menu I recommend using that. If it needs to be enabled then enable it and spam the key needed at start-up to open it.

If your BIOS does not have a boot menu or you do not want to use it then you can change the boot priority order. To do this scroll down in the list to your install media and use the keys (often outlined at the bottom of the screen) to move it up to the top. If you aren't sure what your installation media is many BIOS will say what the device is and the vendor name (e.g Sandisk). Once you have moved the install media up, ensure your install media is still plugged in and then reboot.

#### *2.5* First run

Once you have launched from the USB Flash Drive, you will be prompted with 6 options. You should choose the top option, titled "Start Linux Mint".
![[5-installation_guide_firstboot.png]]

Here, you will be launched into the environment of Linux Mint. If you wish to "try before you buy", metaphorically speaking, you can give it a whirl, but everything you do will be erased after you are done. From here, you can start the installation process with the "Install Linux Mint" app in the top left.

#### *2.6* The installation

**THIS IS THE POINT OF NO RETURN FROM WINDOWS.**

Double click the "Install Linux Mint" application in the top left. Select your language and keyboard (remember to test it in the text box just below to make sure it's the right one), and click continue to keep going. You want to tick the box to Install multimedia codecs and continue. From here, select "Erase disk and install Linux Mint". Once again, **this will destroy everything on your Windows setup. Say goodbye to it all unless you have it on another storage.** Select "Install Now" and click Continue. Then, select your map (this automatically sorts out your time zone) and continue.

Add your name (this can be your real name, or something else), leave the "Your Computer's Name" box, and pick a username. This is what you will be called in your files, similar to Windows. Choose a good password. We won't judge you, but it's good for security reasons to have a good password.
It is not too important to encrypt your home folder unless you're storing a lot of private info. It slows down your device a bit, but it won't slow you to a crawl. After you've decided, click continue and wait. Feel free to scroll the slideshow to learn some of what you can do.

Once it is done, click the "Restart now" button. Disconnect your USB flash drive and click enter once you are at the screen with the logo.

You are done. 


## Continuing
[[6-first_login|First login]]