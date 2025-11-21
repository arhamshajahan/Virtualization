# Virtualization
## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME: ARHAM S

## REG NO: 212222110005

## Aim:

To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:

To install and configure Oracle VM VirtualBox.

## Pre-requisites:

Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

## Steps:

### 1.Download Oracle VM VirtualBox:

* Visit Oracle VirtualBox Official Site
  
* Download installer for your OS (Windows/macOS/Linux).

### 2.Install Oracle VM VirtualBox (Example: Windows):

* Launch Installer → Allow Changes → Click Next.
  
* Choose Installation Options → Click Next.
  
* Accept Network Interface Warning → Click Yes.
  
* Click Install.
  
* Finish Installation and Launch VirtualBox.

### 3.Configure VirtualBox:

* Open VirtualBox.
  
* Click New → Name VM → Select Type (Linux/Windows) and Version.
  
* Allocate:
  
     * Minimum 2 GB RAM
       
     * Create Virtual Hard Disk (20 GB recommended).
       
* Start Virtual Machine and provide ISO to install OS.

## Result:

Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:

To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:

Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

## Steps:

### 1.Download Kali Linux ISO:

* Visit Kali Linux Official Site
  
* Download 64-bit ISO (Installer version).
  
### 2.Create a New Virtual Machine:

* Open VirtualBox → Click New.
  
* Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
  
### 3.Allocate Memory:

* Minimum 2 GB RAM (recommended 4 GB).
  
### 4.Create Virtual Hard Disk:

* Select VDI (VirtualBox Disk Image).
  
* Choose Dynamically allocated.
  
* Set Disk size to 20 GB or more.
  
### 5.Configure ISO Image:

* Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
### 6.Start Installation:

* Boot Virtual Machine → Choose Graphical Install.
  
* Set Language, Region, Keyboard.
  
* Configure Network → Set Hostname (e.g., kali).
  
* Set root password.
  
* Disk Partitioning: Use entire disk → All files in one partition.
  
* Install System → Install GRUB Bootloader → Finish Installation.
  
### 7.Login to Kali Linux:

* Use root credentials.
  
### 8.(Optional) Install Guest Additions:

* Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

<img width="1146" height="591" alt="Screenshot from 2025-10-03 14-09-20" src="https://github.com/user-attachments/assets/54c8fae3-c836-466c-9a4d-31c12b0024dd" />


Snapshot 2: Kali Running in Virtual

<img width="1148" height="696" alt="Screenshot from 2025-10-03 14-09-41" src="https://github.com/user-attachments/assets/2a6bcf1c-fa13-402a-9ae3-9d0806000170" />


## 3.c) Execution of Linux Commands in Kali

## About Linux:

* Open-source operating system.
  
* Kernel manages communication between hardware and software.
  
* Commands are case-sensitive.
    
## Linux Commands:

### 1.ls Command

The ls command is used to display a list of content of a directory.

#### Syntax:

     ls

<img width="1573" height="96" alt="Screenshot from 2025-10-03 19-10-23" src="https://github.com/user-attachments/assets/89450e09-13ec-4f76-8938-4b625e598fc4" />


### 2.pwd Command

The pwd command is used to display the location of the current working directory.

#### Syntax:

   pwd
   
<img width="461" height="51" alt="Screenshot from 2025-10-03 19-11-02" src="https://github.com/user-attachments/assets/a09ed64b-6eba-4222-bd81-0eafc5911aed" />


### 3.mkdir Command

The mkdir command is used to create a new directory under any directory.

#### Syntax:

    mkdir <directory_name>

<img width="1536" height="115" alt="Screenshot from 2025-10-03 19-12-00" src="https://github.com/user-attachments/assets/86a10d2c-018e-47a2-9336-c0641110663d" />


### 4.rmdir Command

The rmdir command is used to delete a directory.

#### Syntax:

  rmdir <directory_name>

<img width="1572" height="115" alt="Screenshot from 2025-10-03 19-13-46" src="https://github.com/user-attachments/assets/ef9f4691-419e-41fe-9442-476d7a275446" />


### 5.cd Command The cd command is used to change the current directory

#### Syntax:

    cd <directory_name>

<img width="527" height="51" alt="Screenshot from 2025-10-03 19-14-23" src="https://github.com/user-attachments/assets/050be5fb-cbe7-4f4a-9f28-79ecfda1a005" />


### 6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

#### Syntax:

    cat [options] [file_name]

<img width="863" height="92" alt="Screenshot from 2025-10-03 19-15-58" src="https://github.com/user-attachments/assets/aba8603d-6c29-4334-a36d-970e5a90fd1c" />


### 7.cp Command

The cp command is used to copy a file or directory.

#### Syntax:

   cp [source] [destination]

<img width="738" height="92" alt="Screenshot from 2025-10-03 19-17-03" src="https://github.com/user-attachments/assets/f6e5e9b5-68f5-4d53-82f3-c799289285a0" />


### 8. gedit Command


#### Syntax:

    gedit [source]

<img width="929" height="250" alt="Screenshot from 2025-10-03 19-18-22" src="https://github.com/user-attachments/assets/f0616b38-3c23-4e27-b62f-84be4c763a05" />


### 9. su Command

#### Syntax :

    su

<img width="528" height="70" alt="Screenshot from 2025-10-03 19-19-11" src="https://github.com/user-attachments/assets/40384276-3b41-431a-895a-cf46ab5774ab" />


### 10.cd Command



## Syntax:

   cd [filename]

<img width="740" height="207" alt="Screenshot from 2025-10-03 19-21-30" src="https://github.com/user-attachments/assets/bc90f197-1dfa-43f2-ac2f-48f6b6220ceb" />


### 11. head Command



#### Syntax:

   head [filename]

<img width="736" height="50" alt="Screenshot from 2025-10-03 19-27-37" src="https://github.com/user-attachments/assets/07609c54-069d-4aab-a4c7-320b7b5031ba" />


### 12. id Command



#### Syntax:

   id

<img width="1428" height="50" alt="Screenshot from 2025-10-03 19-28-00" src="https://github.com/user-attachments/assets/b0e21c04-2e4d-4f62-9c53-02e23f5ae38d" />


### 13. df Command



#### Syntax:

   df

<img width="711" height="229" alt="Screenshot from 2025-10-03 19-29-06" src="https://github.com/user-attachments/assets/a8f668b9-f5ee-46c5-a2b6-01f538084f76" />



### 14. clear Command



#### Syntax:

   clear

<img width="695" height="76" alt="Screenshot from 2025-10-03 19-29-58" src="https://github.com/user-attachments/assets/514beb7a-6aaa-4d7c-a601-dfdcd163e2bc" />



### 15.cal Command



#### Syntax:

   cal

<img width="653" height="191" alt="Screenshot from 2025-10-03 19-30-13" src="https://github.com/user-attachments/assets/0e964339-0c80-4791-bd18-4c7581d59978" />


## Result:

Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
