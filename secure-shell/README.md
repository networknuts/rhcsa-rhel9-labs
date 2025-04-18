# 🔐 Linux Administration Task: Configure and Secure SSH

## Task List

1. From the controller machine, log in to the `servera` machine as the `root` user.  
2. Switch to the `production1` user on the `servera` machine.  
3. Generate passphrase-less SSH keys for the `production1` user on the `servera` machine.  
4. Send the public key of the SSH key pair to the `production1` user on the `serverb` machine.  
5. Verify that the `production1` user can successfully log in to the `serverb` machine using the SSH keys.  
6. Configure the `sshd` service on `serverb` to prevent users from logging in as the `root` user.  
