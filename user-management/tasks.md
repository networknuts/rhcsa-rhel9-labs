# 🐧 Linux Training Lab: User, Group & Password Management

Welcome to your Linux system administration lab. Complete the following tasks to practice group management, user management, password policies, and advanced account handling.

---

## 📁 1. Group Management Tasks

### 🔹 1.1
Create a group named `operations`

### 🔹 1.2
Create a group named `development` with the GID of `1008`

---

## 👤 2. User Management Tasks

### 🔹 2.1
Create a user named `john` with primary group as `operations`

### 🔹 2.2
Create a user named `jane` with secondary group as `development`

### 🔹 2.3
Create a user named `tom` with UID `1010` and secondary group as `operations`

### 🔹 2.4
Assign all three users the password `p@55w0rd`

---

## 🔒 3. Password Management Tasks

### 🔹 3.1
Do NOT allow the users to change their password for 7 days after a password change

### 🔹 3.2
Set the maximum age of the password to 30 days for the above-created users

### 🔹 3.3
On the 20th day, the users should start receiving a warning to change their password

### 🔹 3.4
Set an inactivity period of 14 days for the above users

---

## 🛠️ 4. Advanced User Management

### 🔹 4.1
Lock the `john` user immediately

### 🔹 4.2
Lock the `jane` user on **1st July 2023**

### 🔹 4.3
The user `tom` is under investigation, thus change the user's shell to `nologin`

---
