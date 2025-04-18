# 🧱 Linux Administration Task: Manage Storage Stack

## Task List

- Create a new **logical volume** with the following specifications:
  - Name: `database`  
  - Volume Group: `datastore`  
  - Size: **50 extents**  
  - Extent size for the `datastore` volume group should be set to **16 MiB**  

- Format the logical volume with an **ext3** filesystem.  
- Configure it to be **automatically mounted** under `/mnt/database` at **system boot**.  

- Resize the `database` logical volume so that its size is **approximately 900 MB**.  
  - Note: Only sizes between **870 MB and 890 MB** are accepted.  
