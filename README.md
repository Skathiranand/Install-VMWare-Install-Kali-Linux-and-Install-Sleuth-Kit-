## Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### AIM:
To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

### DESIGN STEPS:
### Step 1:
Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

### Step 2:
Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

### Step 3:
Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

### PROGRAM:
### Step 1: Install VirtualBox
 1. Download the Windows hosts .exe file from the official VirtualBox website.
 2. Run the installer and follow the on-screen instructions.
 3. Once installed, launch VirtualBox to verify the installation.

![output](https://github.com/user-attachments/assets/5fedb8ec-14b8-4f2f-8b09-1021c6f162b4)


### Step 2: Install Kali Linux on VirtualBox
 1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
 2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
 3. Go to Settings > Storage, click Empty under Controller: IDE.
 4. Select Graphical Install, follow the prompts to set language, location, username, and password.
 5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

![output](https://github.com/user-attachments/assets/164e139b-179c-4e82-bacf-1593948a8f42)

### Step 3: Install Sleuth Kit (CLI-based Forensic Tools)
 1. Download the Windows ZIP package from the official website.
 2. Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
 3. Add the bin folder to Windows PATH:
    * Open Control Panel → System → Advanced System Settings.
    * Click Environment Variables → Edit Path.
    * Add the Sleuth Kit bin folder path and save changes.
 4. Verify installation by running:
  ```
 fls -V
  ```
![output](https://github.com/user-attachments/assets/15712c10-c261-4a0c-beaf-865608486af3)


### OUTPUT:
### Virtual Box:
![output](https://github.com/user-attachments/assets/e1d08ebf-f831-4a0d-b171-14043d7db425)

### Virtual Machine (Kali Linux):
![output](https://github.com/user-attachments/assets/ca05f94e-d58f-4d4a-ac4f-1ac6ad251d70)

### Sleuth Kit:
![output](https://github.com/user-attachments/assets/dda80bec-4e2f-430a-8032-2de7e76cba4a)

### RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
