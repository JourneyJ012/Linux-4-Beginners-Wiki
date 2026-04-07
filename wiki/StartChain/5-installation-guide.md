While the process of installing Linux is different for every distribution and piece of hardware the process is similar enough for most beginner distros. For this guide we will be using Linux Mint a distro based upon Ubuntu.

To follow this guide effectively you will need:
A working system
A USB you are willing to format (around 8GB should be enough)


## *1.* Pre-installation

*1.1* **Acquire an installation image**

Visit the [download](https://www.linuxmint.com/download.php) page on the official Linux Mint site. There are a few desktop environments to choose and this guide will use the Cinnamon Edition.

*1.2* **Prepare installation media**

Using the working system you have you will need to create a installation media using a piece of software. This guide recommends using [Rufus](https://rufus.ie/en/) if the machine is on Windows. It's FOSS (Free and Open Source) and lightweight.

If your machine is not running Windows and is running Linux or MacOS then [BalenaEtcher](https://etcher.balena.io/) is a good alternative.

To use Rufus:
Plug in the USB drive you wish to use
Select it in the dropdown menu at the top
Select your installation .ISO file by pressing 'Select'
Press start and accept any popups

**This WILL erase ALL data on the drive**

## *2* Installation

*2.1* Enter the target machine's BIOS

This will vary depending on your hardware. The general method is to (with your installation media plugged in) turn off the machine and when turning it on again spamming the key to enter the BIOS setup. The hard part is knowing which key to press. Common BIOS keys are: Del, F1, F2, F10, F11, F12 or Esc. Some start-up screens will display it or you could find your motherboard or manufacturers manual, however brute force will eventually work.

*2.2* Disable secure boot

Many Linux distributions do not setup secure boot keys especially not during installation so it must be disabled. The process described here will be different depending on BIOS.

To do this navigate to the 'Boot' tab in your BIOS and disable secure boot.

2.3 Change boot order or enable boot menu

If your BIOS has the open for a dedicated boot menu I recommend using that. If it needs to be enabled then enable it and spam the key needed at start-up to open it.

If your BIOS does not have a boot menu or you do not want to use it then you can change the boot priority order. To do this scroll down in the list to your install media and use the keys (often outlined at the bottom of the screen) to move it up to the top. If you aren't sure what your installation media is many BIOS will say what the device is and the vendor name (e.g Sandisk). Once you have moved the install media up, ensure your install media is still plugged in and then reboot.

*2.4* Starting the installation

Once you have launched the installation media you will be prompted with 6 options in the Grub bootloader. We are the most interested in the top option 'Start Linux Mint {version} Cinnamon 64-bit' if you need troubleshooting information then choose the 'Compatibility mode' option or if this is an OEM Install choose the 'OEM Install option'.

*2.5* The installation

The installation is very visual and detailed so will not be extensively covered here.

If you wish to dual boot then make sure you select the option to and then resize the partitions as you wish to using the UI at the bottom of the screen. Alternatively you can erase the entire drive and install just Mint. **Be warned this will erase EVERYTHING.**

