# 💽 Linux Administration Task: Manage Basic Storage

## Task List

- On the `controller` machine (as `root`):
  - Create a **1 GB MBR partition**.  
  - Identify its **UUID**.  
  - Format the partition with an **XFS** file system.  
  - Persistently mount it using its UUID to the `/mnt/freespace` directory.  

- On the `serverb` machine:
  - Use the **first unused disk** to create a **2 GB MBR backup partition**.  
    - A size between **1.8 GB and 2.2 GB** is acceptable.  
  - Configure the backup partition with an **XFS** file system.  
  - Persistently mount the partition to the `/backup` directory.  

- On the same disk:
  - Create **two 512 MB MBR partitions** named `swap1` and `swap2`.  
    - A size between **460 MB and 564 MB** is acceptable.  
  - Set both partitions as **swap** type.  
  - Initialize both partitions as **swap spaces** and configure them to **activate at boot**.  
  - Set the **`swap2`** partition to be **preferred** over the other.  
