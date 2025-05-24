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
![image](./images/a1.png)

![image](./images/a2.png)

![image](./images/a3.png)

![image](./images/a4.png)

![image](./images/a5.png)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
