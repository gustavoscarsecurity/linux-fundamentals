 Linux Fundamentals – File System & Permissions

📅 February 12, 2026  
First day studying Linux.

## Overview

Today I started learning Linux as part of my journey toward a career in Cybersecurity.

In this session, I focused on:

- Navigating the Linux file system
- Understanding the directory structure
- Creating and editing files
- Managing file permissions with `chmod`
- Understanding basic access control concepts

---

## File System Navigation

I learned how to check my current location in the system:

```bash
pwd
List directory contents:

ls
ls -l
ls -la
And navigate through the system, including the root directory:

cd /
This helped me understand the Linux hierarchy, such as:

/home – User directories

/root – Administrator directory

/etc – Configuration files

/var – Logs and system data

Understanding where files are stored is important when thinking about system security.

Creating and Editing Files
I created directories and files using:

mkdir studies
touch objective.txt
Edited files with:

nano objective.txt
And verified content with:

cat objective.txt
This gave me hands-on experience with how Linux handles file management.

File Permissions & chmod
Using:

ls -l
I analyzed permission structures like:

-rw-r--r--
Linux permissions are divided into:

Owner | Group | Others
Each can have:

r (read = 4)

w (write = 2)

x (execute = 1)

Example:

chmod 600 objective.txt
This makes the file readable and writable only by the owner:

-rw-------
Security Perspective
Improper file permissions can lead to security vulnerabilities.

If sensitive files are accessible to unauthorized users, it may allow data exposure or privilege escalation.

Understanding permission management is essential for:

Secure system configuration

Identifying misconfigurations

Preventing unauthorized access

Conclusion
Today I built my foundation in:

Linux navigation

Directory structure

File creation and editing

Basic access control

This is the beginning of my Linux journey toward cybersecurity.
