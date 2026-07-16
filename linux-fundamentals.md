# Linux Fundamentals

## Overview

This module introduced the fundamentals of the Linux operating system, including filesystem navigation, file management, user permissions, command-line usage, file searching and shell operators.

These skills provide the foundation for Linux system administration, cybersecurity and penetration testing.

---

## Topics Covered

### Linux Basics

- Understanding the Linux operating system
- Navigating the filesystem
- Absolute and relative paths
- Common Linux directories

---

### File and Directory Management

- Creating files and directories
- Copying, moving and deleting files
- Viewing file contents
- Managing permissions

---

### File Searching

- Searching files using `find`
- Searching by filename
- Searching by extension
- Recursive searches

---

### Text Searching

- Searching text using `grep`
- Recursive searches with `grep -R`
- Finding specific values inside files

---

### Shell Operators

- Background execution (`&`)
- Conditional execution (`&&`)
- Output redirection (`>`)
- Append output (`>>`)

---

## Practical Examples

### File searching

```bash
find -name passwords.txt
find -name "*.txt"
```

### Text searching

```bash
grep "81.143.211.90" access.log
grep -R "PRETTY_NAME" /etc/
```

### Shell operators

```bash
echo hello > welcome
echo world >> welcome

command1 && command2

cp largefile backup &
```

---

## Skills Developed

- Linux command-line usage
- Filesystem navigation
- File management
- File searching
- Text filtering
- Shell operators
- Basic Linux administration

---

## Key Takeaways

Linux command-line skills are fundamental for cybersecurity professionals. Understanding how to navigate the filesystem, manage files, search information and use shell operators provides the foundation for more advanced topics such as system administration, digital forensics and penetration testing.

---

## Notes

This module was completed as part of the TryHackMe Cyber Security Learning Path.
