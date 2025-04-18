# 📡 Linux Administration Task: Access Network-Attached Storage

## Task List

- Configure an **automounter indirect map** on `servera` with **exports from `controller`**.  
- Create the following configuration files:
  - Master map file: `/etc/auto.master.d/shares.autofs`  
  - Mapping file: `/etc/auto.shares`  

- Use `/remote` as the **main mount point** on `servera`.  
- Reboot `servera` to verify that the **`autofs` service starts automatically**.  
