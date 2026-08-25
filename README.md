## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME: RISHI CHANDRAN R
## REG NO:212223043005

## Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
## Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Parrot security OS
## Aim:
To install and configure Parrot security in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Parrot security OS image
## Steps:
Download Parrot security OS:

Visit Parrot security OS 
Download 64-bit OS (Installer version).
Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: " Parrot security OS" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select  Parrot security OS.
Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g.,  Parrot).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
Login to  Parrot security OS:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Parrot.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e1f25324-cf82-413c-b370-a7fd2686c17b" />


Snapshot 2: Parrot security OS Running in Virtual


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/67d644e3-c0df-44e8-9717-b19532c1a852" />


## Result:
Thus, Parrot security OS guest OS was installed and configured successfully.


## 3.Execution of Linux Commands in Parrot OS
## About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
## Linux Commands:
1. ls Command
The ls command is used to display a list of content of a directory.

<img width="955" height="983" alt="image" src="https://github.com/user-attachments/assets/c9c4ba14-b24a-463a-a76a-ad68cfaaeebd" />

2. pwd Command
The pwd command is used to display the location of the current working directory.

<img width="792" height="85" alt="image" src="https://github.com/user-attachments/assets/31f0963a-02d8-41ad-a468-bd1d8bf75892" />

3. mkdir Command
The mkdir command is used to create a new directory under any directory.

<img width="787" height="111" alt="image" src="https://github.com/user-attachments/assets/16e8b7e3-c85d-41b9-8a27-9cad3299524a" />

4. rmdir Command
The rmdir command is used to delete a directory.

<img width="797" height="112" alt="image" src="https://github.com/user-attachments/assets/3d468c9a-e196-4dec-af1d-b2bf93abe99a" />

5. cd Command
The cd command is used to change the current directory.

<img width="575" height="72" alt="image" src="https://github.com/user-attachments/assets/309ef45f-a74e-4be8-b02b-f86e8dee2c29" />

6. cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

<img width="432" height="77" alt="image" src="https://github.com/user-attachments/assets/66b20c28-6adf-4401-b8bd-8713c9bb92d9" />

7. cp Command
The cp command is used to copy a file or directory.

<img width="563" height="115" alt="image" src="https://github.com/user-attachments/assets/4c7e3ee1-603b-4403-b0eb-ac0926cd4715" />

8.mv Command
The mv command is used to move a file or a directory form one location to another location.

<img width="623" height="107" alt="image" src="https://github.com/user-attachments/assets/439e971f-c533-4789-a4f6-4c91934ca345" />

## Result:
Thus, various Linux commands were executed successfully in Parrot security OS virtual machine.
