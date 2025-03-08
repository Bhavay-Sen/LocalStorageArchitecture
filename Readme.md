# Data Organization Guide

## Folder Structure

### 00_Miscellaneous
This will hold the data which falls under the miscellaneous category. The miscellaneous category includes data that does not belong to any of the categories mentioned below.

### 01_Study
This folder contains all the data and material related to study. This includes videos, photos, PDFs, software, and any other study-related materials.

**Subfolders :**

**00_Miscellaneous :** This folder contains all type of file.

**01_Software Applications :** This folder contains all the software applications used for learning (include Cracks)

**02_Software :** This folder contains all the software related projects. (For ex, C-programming revision, QL Embedded Revision, Java Core etc)

**03_Hardware :** This folder contains all the hardware design related projects.

**04_Study Notes and Material :** This folder contains all the pdf and notes related to the above mentioned topics - Software, Hardware etc.

**05_media-photos&Videos :** This folder contains all the media files, photos, videos, screenshot of study and learning related stuffs.

### 02_Personal
This folder contains all personal data, such as: Personal documents, IDs, photos, mobile data, personal media backup, music, and other media.

**Subfolders :**

**00_Miscellaneous :** This folder contains all type of file.
**01_Documents :**
**02_Softwares :**
**03_Innovations & designs :**

### 03_Work
This folder contains all data related to professional work, including:
- Documents, work-related data, work photos, media, and other relevant files.
- Data from organizations such as Aartech, DRMZ, and Wipro will be stored here.

**Subfolders :**

---

## Data Sorting/Selection Algorithm

1. **Determine the High-Level Category**  
   - Identify whether the data belongs to:  
     **STUDY | PERSONAL | WORK**
   - If it does not fit into any of these categories, move it to **Miscellaneous**.
#
2. **Check the File Type**
   - Identify the type of file:
   **PDF | Zip | Software Application | Code File | Hardware Design File | Video/Photo**
#
3. **Move the File to the Respective Category**

| Level_0               | Level_1                       | Level_2                           |
|-----------------------|-------------------------------|-----------------------------------|
| 00_Miscellaneous  	   |                               |                                   |
| 01_Study         	   | 01_Software Applications      | folders with data (00_<name>)     |
|                       | 02_Software                   |                                   |
|                       | 03_Hardware                   |                                   |
|                       | 04_Study Notes and Material   |                                   |
| 02_Personal           |                               |                                   |
| 03_Work               |                               |                                   |
