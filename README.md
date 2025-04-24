# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
Name:Vimala Rani A

Reg No:212223040240
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
bash
lsblk


bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512


bash
mmls ~/disk.img

bash
sudo ls -lh disk.img

bash
strings disk.img | less



## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![Screenshot 2025-04-24 232158](https://github.com/user-attachments/assets/b34d8517-6495-4e40-8d87-eb94523277da)
![Screenshot 2025-04-24 232207](https://github.com/user-attachments/assets/39879a32-3e18-4f54-a4ce-df3a321c0aff)
![Screenshot 2025-04-24 232216](https://github.com/user-attachments/assets/3cea9d94-3048-4c17-817a-47c0478021c0)
![Screenshot 2025-04-24 232227](https://github.com/user-attachments/assets/5d01655e-cf95-4c45-a2c8-de111dc6e7f6)
![Screenshot 2025-04-24 232244](https://github.com/user-attachments/assets/97690304-3284-47d7-8125-d7a1df3d267e)




## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
