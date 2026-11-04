## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
NAME: Harini S K
REG NO: 21222530092
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
*Machine with Internet access *Minimum 4 GB RAM *Sufficient storage space

## Steps:
1.Download Oracle VM VirtualBox:
*Visit Oracle VirtualBox Official Site
*Download installer for your OS (Windows/macOS/Linux).
2.Install Oracle VM VirtualBox (Example: Windows):
*Launch Installer → Allow Changes → Click Next.
*Choose Installation Options → Click Next.
*Accept Network Interface Warning → Click Yes.
*Click Install.
*Finish Installation and Launch VirtualBox.
3.Configure VirtualBox:
*Open VirtualBox.
*Click New → Name VM → Select Type (Linux/Windows) and Version.
## Allocate:
*Minimum 2 GB RAM *Create Virtual Hard Disk (20 GB recommended). *Start Virtual Machine and provide ISO to install OS.

## Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
*Oracle VM VirtualBox Installed *4 GB RAM and 20 GB Storage Minimum *Kali Linux ISO image

## Steps:
1.Download Kali Linux ISO:
*Visit Kali Linux Official Site *Download 64-bit ISO (Installer version). *Create a New Virtual Machine: *Open VirtualBox → Click New. *Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

## Allocate Memory:
*Minimum 2 GB RAM (recommended 4 GB). *Create Virtual Hard Disk: *Select VDI (VirtualBox Disk Image). *Choose Dynamically allocated. *Set Disk size to 20 GB or more.

## Configure ISO Image:
*Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

## Start Installation:
*Boot Virtual Machine → Choose Graphical Install. *Set Language, Region, Keyboard. *Configure Network → Set Hostname (e.g., kali). *Set root password. *Disk Partitioning: Use entire disk → All files in one partition. *Install System → Install GRUB Bootloader → Finish Installation.

## Login to Kali Linux:
*Use root credentials. *(Optional) Install Guest Additions: *Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox image
Snapshot 2: Kali Running in Virtual image
Result:
Thus, Kali Linux guest OS was installed and configured successfully.

3.c) Execution of Linux Commands in Kali
About Linux:
*Open-source operating system. *Kernel manages communication between hardware and software. *Commands are case-sensitive.

## Linux Commands:
1.ls Command:
The ls command is used to display a list of content of a directory.

##Syntax:
ls
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/b9254813-f6cf-478c-b2b6-887ee5e539d6" />

2.pwd Command:
The pwd command is used to display the location of the current working directory.

Syntax:
pwd
<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/85e9967e-c8b7-4422-8561-0fa44e8fd0ab" />

3.mkdir Command:
The mkdir command is used to create a new directory under any directory.

Syntax:
mkdir <directory_name> 
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/7c35aead-c8bb-474a-bd2a-fe663f674f60" />

4.rmdir Command:
The rmdir command is used to delete a directory.

Syntax:
rmdir <directory_name>
<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/bc9bdbd5-2881-49e1-bb56-d53885452ee0" />

5.cd Command :
The cd command is used to change the current directory

Syntax:
cd <directory_name>
<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/1cec6962-bb0f-4a2d-95e3-dc2a73bc6572" />

6.cat Command:
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
cat [options] [file_name]
<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/1078bfc7-41d3-4615-8f77-138b7bb0416e" />
<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/0eb49b6f-04ac-4852-bde3-158c8b93930e" />

7.cp Command:
The cp command is used to copy a file or directory.

Syntax:
cp [source] [destination]
<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/efd4d33e-a053-4a99-98a8-84d04989250f" />
<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/64e8cc20-0d5c-4635-acb2-51b62a6f64bd" />

8.mv Command:
The mv command is used to move a file or a directory form one location to another location.

Syntax:
mv [source] [destination]
<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/b5067306-c4cd-4280-9a56-23b7bff075df" />
<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/964cb4b6-5b8b-4e6e-93e1-500d331efcab" />

9.touch Command:
Create empty file.

Syntax:
touch [filename]
<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/f2c73e26-8e17-47d3-9bd0-a1f0905f49e1" />

10.vi Command:
Edit file contents using editor.

Syntax:
vi [filename]
<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/0dad00af-4af9-4678-93f2-6c22298af4a6" />

## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
