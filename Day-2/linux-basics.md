# 📅 Day 2 — Linux Basics

## 📂 Linux File System Overview

| Directory | Description |
|----------|-------------|
| `/` | The root directory; top of the file system hierarchy. |
| `/home` | Contains home directories for all users. |
| `/root` | Home directory for the root (admin) user. |
| `/etc` | Stores system configuration files. |
| `/var` | Contains variable data like logs, cache, and spool files. |
| `/usr` | User-installed programs and libraries. |
| `/bin` | Essential command binaries (ls, cp, mv, etc.). |
| `/sbin` | System binaries (administrative commands). |
| `/opt` | Optional third-party applications. |
| `/tmp` | Temporary files; cleaned on reboot. |

---

## 🧰 Essential Commands Practiced

### 🔷 Navigation Commands
| Command | Purpose |
|---------|----------|
| `pwd` | Show current directory |
| `ls -l` | List files in long/permission format |
| `ls -a` | Show hidden files |
| `cd path/` | Change directory |

---

### 🔶 File Operations
| Command | Purpose |
|---------|----------|
| `touch file.txt` | Create an empty file |
| `mkdir folder` | Create directory |
| `cp file1 file2` | Copy file |
| `mv file1 file2` | Move or rename file |
| `rm file.txt` | Delete a file |
| `rm -r folder` | Delete folder + contents |
| `cat file` | View file contents |
| `head -n 10 file` | First 10 lines |
| `tail -n 10 file` | Last 10 lines |

---

### 🔑 Permissions & Ownership
| Command | Purpose |
|---------|----------|
| `chmod 755 file` | Change permissions (rwxr-xr-x) |
| `chmod u+x script.sh` | Give execute permission to user |
| `chown user:group file` | Change owner/group |

---

### 🔍 Search Utilities
| Command | Purpose |
|---------|----------|
| `grep "text" file` | Search text within a file |
| `find /path -name "*.log"` | Find files by name/pattern |

---

### 🖥️ System Info Commands
| Command | Purpose |
|---------|----------|
| `uname -a` | Kernel + system information |
| `df -h` | Disk usage |
| `du -sh *` | Size of folders/files |
| `free -m` | Memory usage |

---

## 🧪 Practice Task Output (Commands Used)

```
mkdir devops-day2
cd devops-day2
touch file1.txt file2.txt
echo "Hello DevOps" > file1.txt
cp file1.txt copy-file.txt
chmod 755 copy-file.txt
```

---

## 🎯 Summary of Learning

- Understood Linux directory structure and its importance.
- Practiced 20+ essential commands used daily in DevOps.
- Created and managed files, folders, permissions.
- Created a cheat sheet for future reference.

---

