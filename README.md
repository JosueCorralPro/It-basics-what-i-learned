# I.T.
Basic Knowledge
# Introduction to IT - What I Learned 🚀

## Overview 📝
This repository showcases what I have learned in IT. Below are key concepts, practical applications, and useful scripts that I have practiced and implemented.

---

## 1. Understanding the Command Line (CLI) 💻
One of the first things I learned was how to navigate and manage files using the command line, both in **Windows Command Prompt** and **Linux/macOS Terminal**.

### **Windows Command Prompt (cmd) 🖥️**
Some fundamental commands I practiced include:
```batch
:: Display the current directory
cd

:: List files in a directory
DIR

:: Create a new directory
mkdir IT_Files

:: Change directory
cd IT_Files

:: Delete a file
DEL example.txt
```

### **Linux/macOS Terminal (Bash) 🐧**
I also learned the equivalent commands in Unix-based environments:
```bash
# Display the current directory
pwd

# List files in a directory
ls -lah

# Create a new directory
mkdir IT_Files

# Change directory
cd IT_Files

# Remove a file
rm example.txt
```

---

## 2. Networking Basics 🌐
Networking is an essential part of IT, and I explored several commands to check network configurations and troubleshoot connectivity issues.

### **Checking Network Configuration**
#### Windows 🏁:
```batch
:: View IP configuration
ipconfig /all

:: Test network connectivity
ping 8.8.8.8

:: Display active network connections
netstat -an
```

#### Linux/macOS 🐧:
```bash
# View IP configuration
ifconfig   # or 'ip a' on modern systems

# Test network connectivity
ping 8.8.8.8

# Display active network connections
netstat -tulnp
```

---

## 3. System Administration Basics 🛠️
Learning how to manage systems effectively is crucial in IT. Below are some of the commands I practiced for checking system information and managing processes.

### **Windows System Info & Task Management 🖥️**
```batch
:: Display system information
systeminfo

:: List running processes
tasklist

:: Kill a process by name
taskkill /IM notepad.exe /F
```

### **Linux/macOS System Info & Task Management 🐧**
```bash
# Display system information
uname -a

# List running processes
ps aux

# Kill a process by name
killall -9 firefox
```

---

## 4. File Permissions & User Management 🔒
One of the most interesting parts of this journey was learning how to manage user accounts and set file permissions.

### **Windows User Management 🏁**
```batch
:: List user accounts
net user

:: Create a new user
net user NewUser MyPassword123 /ADD

:: Delete a user account
net user NewUser /DELETE
```

### **Linux User Management 🐧**
```bash
# List user accounts
cat /etc/passwd

# Create a new user
sudo useradd -m NewUser

# Delete a user account
sudo userdel -r NewUser
```

---

## 5. Basic Troubleshooting Commands 🛠️
Troubleshooting is an important skill in IT, and I practiced various commands to diagnose and resolve issues.

### **Windows Troubleshooting 🏁**
```batch
:: Check for disk errors
chkdsk C: /f

:: Flush DNS cache
ipconfig /flushdns

:: Restart network adapter
netsh interface set interface "Wi-Fi" admin=disable
netsh interface set interface "Wi-Fi" admin=enable
```

### **Linux/macOS Troubleshooting 🐧**
```bash
# Check disk usage
df -h

# Flush DNS cache
sudo systemd-resolve --flush-caches  # (For most modern distros)

# Restart network service
sudo systemctl restart NetworkManager
```

---

## Conclusion 🎯
Throughout this learning process, I gained a solid foundation in IT fundamentals, including command line usage, networking, system administration, user management, and troubleshooting. Practicing these skills has given me confidence in handling real-world IT tasks.

📌 I will continue building upon this knowledge and refining my technical skills.
