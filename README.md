**Ethical Hacking Lab Setup Using VirtualBox**

**Introduction**

This repository provides a detailed guide to setting up a fully functional Ethical Hacking Lab using VirtualBox. 
The lab is built using a lightweight Windows 10 Superlite Ghost ISO, equipped with essential tools like Python, Java, SQL, and web browsers for ethical hacking practices.

**System Requirements**

Before setting up the lab, ensure your system meets the following requirements:
Host OS: Windows, Linux, or macOS
RAM: Minimum 8GB
Storage: At least 20GB of free space
Software:
  VirtualBox
  Windows Superlite Ghost ISO
  VirtualBox Guest Additions
  Ethical hacking tools (added via a shared folder)

**Installation Guide**

**Step 1: Download Required Files**
Download and install VirtualBox - https://www.virtualbox.org/wiki/Downloads
Download the Windows 10 Superlite Compact Ghost ISO from here - https://archive.org/details/ghost-spectre-windows-10
Download VirtualBox Guest Additions here - https://www.virtualbox.org/manual/ch04.html
Gather all required hacking tools and save them in a Lab Setup Folder.

**Step 2: Create a Virtual Machine**
Open VirtualBox and click New.
Set the name (e.g., EthicalHackingLab), Type: Microsoft Windows, Version: Windows 10 (64-bit).
Allocate RAM (at least 4GB).
Create a Virtual Hard Disk (20GB+ recommended).
Select ISO file (Windows 10 Superlite Compact Ghost ISO) when prompted and start the installation.

**Step 3: Install VirtualBox Guest Additions**
After installing Windows, go to Devices > Insert Guest Additions CD Image.
Open the virtual CD drive and run VBoxWindowsAdditions.exe.
Restart the virtual machine.

**Step 4: Share Lab Tools Folder**
In VirtualBox, go to Settings > Shared Folders.
Click Add New Folder, select the Lab Setup Folder, and enable Auto-mount.
Start the VM, open File Explorer, and access the shared folder.

**Step 5: Install Hacking Tools**
Install each tool from the shared folder:
  Python
  Java
  MySQL
  SSMS
  Notepad
  Browser (Google Chrome, Mozilla Firefox)
  Other penetration testing tools (Kali tools, Wireshark, etc.)

