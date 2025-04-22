# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command(Kali Linux) or GUI application (windows)

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## PROGRAM:
### **Install Autopsy for Windows (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.

### ** Autopsy for Linux **
1. Open Terminal.
2. Update your package list: sudo apt update
3. Install Autopsy: sudo apt install autopsy
4. Launch Autopsy using: autopsy
5. Open http://localhost:9999/autopsy in a web browser.

### **Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.


## OUTPUT:
## Analysing the disk file and configuration:
![image](https://github.com/user-attachments/assets/a4377b18-14e7-4daa-98f4-a6eb9e85f6b6)

![Screenshot 2025-04-22 215750](https://github.com/user-attachments/assets/461a6099-f23a-4e51-b1be-34e9c5409f10)

![image](https://github.com/user-attachments/assets/6253905b-c769-421f-8e94-5a4953f458a7)

### Timeline:
![image](https://github.com/user-attachments/assets/a75f3d66-685b-4883-b3b7-ad8140072d96)


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
