# Setting up Linux Mint and Windows Dual Boot

## **By Parker Jones**

## Introduction
Dual booting is a common practice now a days and its important to know how to utilize it. This is mainly useful to those who are programmers and developers. Linux provides a better environment for programming and web coding (eg. LAMP stack). Linux is especially good at providing an easy to use C/C++ coding environment (in my personal experience). Now knowing some of the basic pros of Linux, I'm going to walk through the steps in order to dual boot both operating systems on your computer. You can also boot from a flash drive if you prefer to not mess with your HDD/SDD partitions, but I have found dual booting to be the preferred method. 

## Target Audience
This tutorial is not terribly difficult, however, it can lead to some unintended consequences if steps aren't followed correctly. That being said I highly suggest you keep a backup of your files and a windows install disk in the event that you accidently wipe a partition that you were using for windows. With those pitfalls, I wouldn't recommend this tutorial to anyone who doesn't have atleast 1-2 years experience of working with/on computers.

**Step 1: Create live USB**
This step requires you create a bootable linux drive from a USB or disk. This step is very easy with no risk, and if you only want to boot from flashdrive instead of dual boot this is pretty much your only required step. To accomplish this you need to download a tool to write the linux .iso image to a disk/flashdrive. I personally use Universal USB Installer. Which can be found here: https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/ Next you need to download your linux mint .iso. This can be found here: https://linuxmint.com/download.php Make sure you download Linux Mint Cinnamon as it is the most popular. Once these are complete, go ahead and run Universal Installer. It will as you to select the OS you want to use and then select the .iso file for that OS to go on your flashdrive. Make sure your flashdrive is empty or backed up, as formatting it will wipe its contents. Next, select your flashdrive from the drive selection drop down. MAKE SURE YOU SELECTED YOUR FLASHDRIVE OR YOU WILL WIPE YOUR HARDDRIVE PARTITIONS. Once your flashdrive is selected go ahead and hit the create button down below.

**Step 2: Create Linux Mint Partition on your HDD/SSD**
This is by far the most "dangerous" step in that if you delete the wrong partition you can wipe your windows OS and consequently your files stored on there. First you want to open the Disk Management tool in windows. Once it is open, select the harddrive you want to install Linux mint on, right click and select the option "Shrink Volume". Linux mint is usually ~10 gb in size, I personally recommend creating a partition about 40-100 GB in size just so you have space to save what ever files or programs you want. Once the partition is made we can move on to the next step. **Important:** remember the name of the partition you created since you will need it to finish this process.

**Step 3: Boot into your created Live USB**


