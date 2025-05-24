# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
# Name: Kavi Keerthana R 
# Reg No: 212222100022
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
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/a.png bs=512
```

```bash
mmls ~/a.png  (sleuth-kit)
sudo fdisk -l ~/a.png (GNU)

```
```bash
sudo ls -lh a.png
```
```bash
strings a.png | less

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/4c916937-a02d-4695-a494-041018766219)


![image](https://github.com/user-attachments/assets/3a155bc1-79d0-490e-99b4-f0866387b665)


![image](https://github.com/user-attachments/assets/ef7a056e-d579-4e99-8d47-5ae1a7e2cc73)


![image](https://github.com/user-attachments/assets/5b483978-e4b2-4e75-a4ee-fc45093a4f20)


![image](https://github.com/user-attachments/assets/fbdfc362-84ee-4670-baa3-a8af06c159a5)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
