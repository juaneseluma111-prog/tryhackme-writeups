# Linux Fundamentals — TryHackMe

**Platform:** TryHackMe  
**Path:** Pre-Security  
**Difficulty:** Easy  
**Category:** Operating Systems  
**Status:** Completed  
**Date:** April 2026  

---

## Objective
Learn essential Linux commands for navigating the filesystem,
managing files, and understanding permissions.

---

## Key Commands Learned

### Navigation
```bash
pwd          # show current directory
ls -la       # list files with permissions
cd /path     # change directory
```

### File Management
```bash
cat file.txt       # read file content
cp file dest       # copy file
mv file dest       # move or rename file
rm file            # delete file
mkdir folder       # create directory
```

### Permissions
```bash
chmod 755 file     # set permissions
chown user file    # change owner
sudo command       # run as administrator
```

### Network Commands
```bash
ifconfig           # show network interfaces
ping host          # test connectivity
ssh user@host      # connect remotely
```

---

## Key Learnings
- Linux filesystem structure and navigation
- File permissions and how to modify them
- Running commands with elevated privileges using sudo
- Essential commands for cybersecurity work

---

## How This Applies to Security
- All penetration testing tools run on Linux
- Understanding permissions is critical for privilege escalation
- SSH is the primary way to manage remote servers securely

---
*Write-up by Juan Esteban Umana Machado — linkedin.com/in/juanesumaa11*