# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:

<img width="1342" height="672" alt="image" src="https://github.com/user-attachments/assets/91b604ea-54c4-4117-be58-0d08b518816f" />

<img width="450" height="553" alt="image" src="https://github.com/user-attachments/assets/a8aae347-f0d4-4877-8c1d-80463ac9bac3" />

<img width="577" height="395" alt="image" src="https://github.com/user-attachments/assets/8436d148-7235-47cf-a1e4-e65682ec81c1" />

<img width="492" height="173" alt="image" src="https://github.com/user-attachments/assets/2dfad6b1-bc6e-4671-85a2-59525254e330" />

<img width="673" height="787" alt="image" src="https://github.com/user-attachments/assets/f47c79c4-d089-47ac-978d-f61e15fbc368" />

<img width="655" height="518" alt="image" src="https://github.com/user-attachments/assets/e88edac8-ec43-43eb-832a-7e2d7004835e" />




## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
