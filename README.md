# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/bb846afa-f60d-4cd9-80c5-a7005ca1a49a)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/ec41e1d7-d355-4a5d-ac99-06d3022148ba)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/24272597-da31-4605-9b3f-38308b4c1c5a)


- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/ce2135ef-2792-4ba4-b436-79194567b234)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/79e9d500-9a12-41c6-bb30-2ed4b9dc4b10)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/196f2db5-6a50-4277-a613-e74b45b7de68)
![image](https://github.com/user-attachments/assets/c0ec2e18-bbb7-43f2-be24-18d0172cece8)




- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/646205e3-b393-409c-92b8-b5da1e6bf8c8)



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.



## Output :
### Folder before deleting the files
![Screenshot 2025-03-20 141943](https://github.com/user-attachments/assets/4cf1c400-c023-4dde-b4ed-5c542bbd112e)

## Folder after deleting the files
![image](https://github.com/user-attachments/assets/f8f95886-15d7-4bc2-bde7-33d9aca7bb2e)




### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-20 141943](https://github.com/user-attachments/assets/30a36a23-bd77-4120-9107-478255a5a155)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
