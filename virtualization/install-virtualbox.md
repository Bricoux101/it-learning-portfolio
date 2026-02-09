# Installing VirtualBox

## Objective
Install Oracle VirtualBox to create and manage virtual machines for IT training and lab environments.

## Tools Used
- Oracle VirtualBox
- Windows 11 Host Machine
- Microsoft Windows ISO

## Steps

### 1. Download VirtualBox
Downloaded VirtualBox from the official website:
https://www.virtualbox.org/wiki/Downloads

Selected:
Windows hosts version

Screenshot:
![VM Creation](/virtualization/screenshots/virtualbox-installed.png)


### 2. Install VirtualBox
Ran the installer and completed the installation using default settings.

Note:
If installation fails or virtualization is not available, enable virtualization in BIOS:

BIOS Settings:
- Intel: Enable Intel VT-x
- AMD: Enable SVM Mode

Screenshot:
![VirtualBox Installed](../screenshots/virtualbox.png)


### 3. Download Windows ISO
Downloaded Windows ISO from Microsoft:
https://www.microsoft.com/software-download/

Used Media Creation Tool to download the ISO file.

Screenshot:
![Windows ISO Download](../screenshots/windows-iso-download.png)


### 4. Launch VirtualBox and Create VM
Opened VirtualBox and clicked:

New → Entered VM name → Selected ISO → Allocated resources

Configuration used:
- RAM: 2GB
- Storage: 50GB
- CPU Cores: 2
- OS: Windows 10 / Windows 11

Screenshot:
![VM Creation](../screenshots/vmsetup.png)

Screenshot:
![VM Creation](../screenshots/vmwin10.png)


## Result

Oracle VirtualBox was installed successfully and is ready to create virtual machines for lab environments.

## Skills Learned

- Installing virtualization software
- Understanding BIOS virtualization requirements
- Creating virtual machines
- Preparing IT lab environment



