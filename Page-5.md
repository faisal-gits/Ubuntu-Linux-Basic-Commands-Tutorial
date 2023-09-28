# Ubuntu Linux Basic Commands Tutorial

## Page 5: User and File Permissions

Welcome to Page 5 of our Ubuntu Linux Basic Commands Tutorial. In this section, we'll cover commands related to user management, file permissions, and system security.

### 47. `chmod` - Change File Permissions

`chmod` allows you to change file permissions, controlling who can read, write, and execute files.

Example (Give read and write permissions to the owner of a file):
```bash
chmod u+rw file.txt
```

### 48. `chown` - Change File Ownership

`chown` changes the ownership of files and directories, allowing you to transfer ownership between users.

Example (Change the owner of a file to a different user):
```bash
chown newowner file.txt
```

### 49. `useradd` and `userdel` - User Account Management

`useradd` is used to create new user accounts, while `userdel` is used to delete user accounts.

Example (Create a new user):
```bash
sudo useradd newuser
```

### 50. `passwd` - Change User Password

`passwd` allows users to change their passwords or administrators to modify other users' passwords.

Example (Change the password for a user):
```bash
passwd username
```

### 51. `su` - Switch User

`su` lets you switch to another user's session, typically the superuser (root).

Example (Switch to the root user):
```bash
su -
```

### 52. `sudo` - Execute Commands as Superuser

`sudo` allows authorized users to execute commands as the superuser (root), granting temporary administrative privileges.

Example (Run a command as root):
```bash
sudo apt-get update
```

### 53. `alias` and `unalias` - Create and Remove Command Aliases

`alias` is used to create custom command shortcuts, while `unalias` removes them.

Example (Create an alias for a long command):
```bash
alias ll='ls -l'
```

### 54. `cal` - Display a Calendar

`cal` displays a calendar in the terminal.

Example:
```bash
cal
```

### 55. `apt-get` - Package Management (Debian-based Distros)

`apt-get` is used to manage packages on Debian-based Linux distributions like Ubuntu.

Example (Install a package):
```bash
sudo apt-get install package_name
```

These user and file permission commands are vital for managing users, securing your system, and controlling access to files and directories. In the next page, we'll cover miscellaneous and helpful Linux commands.

[Next: Page 6 - Miscellaneous and Helpful Commands](Page-6.md)

---

Continue to the next page (Page 6) to explore additional Ubuntu Linux commands that can be helpful in various situations.