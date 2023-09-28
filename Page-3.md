# Ubuntu Linux Basic Commands Tutorial

## Page 3: System and Process Management

Welcome to Page 3 of our Ubuntu Linux Basic Commands Tutorial. In this section, we'll focus on commands related to system and process management, which are crucial for understanding and controlling your Linux system.

### 21. `df` - Disk Space Usage

The `df` command provides information about disk space usage on your system, including available space and filesystems.

Example:
```bash
df -h
```

### 22. `du` - Disk Usage

`du` (disk usage) displays the disk space consumed by files and directories, helping you identify large files or folders.

Example:
```bash
du -sh /path/to/directory
```

### 23. `top` - Monitor System Activity

`top` displays real-time information about running processes, CPU usage, memory, and more.

Example:
```bash
top
```

### 24. `htop` - Interactive Process Viewer

Similar to `top`, `htop` provides a more interactive and user-friendly way to monitor system resources.

Example:
```bash
htop
```

### 25. `ps` - Process Status

`ps` generates a list of currently running processes. You can use it with various options to filter and format the output.

Example (List all processes):
```bash
ps aux
```

### 26. `uname` - System Information

The `uname` command displays system-related information, such as the kernel version and system architecture.

Example:
```bash
uname -a
```

### 27. `hostname` - Display Hostname

`hostname` shows the system's hostname, which can be useful in network configurations.

Example:
```bash
hostname
```

### 28. `time` - Measure Command Execution Time

`time` allows you to measure the execution time of a command, helping you assess performance.

Example:
```bash
time ls
```

### 29. `systemctl` - System Service Management

`systemctl` is used to manage system services and daemons, enabling you to start, stop, and check the status of services.

Example (Start Apache web server):
```bash
sudo systemctl start apache2
```

### 30. `watch` - Repeatedly Execute a Command

The `watch` command runs a specified command repeatedly, providing updates at regular intervals.

Example:
```bash
watch -n 1 date
```

### 31. `jobs` - View Background Jobs

`jobs` lists background jobs associated with your shell session.

Example:
```bash
jobs
```

### 32. `kill` - Terminate Processes

`kill` is used to send signals to processes, allowing you to terminate them gracefully or forcefully.

Example (Terminate a process by PID):
```bash
kill -9 PID
```

### 33. `shutdown` - Power Management

The `shutdown` command enables you to power off or restart your system safely.

Example (Shutdown immediately):
```bash
sudo shutdown -h now
```

### 34. `ping` - Network Connectivity Testing

`ping` tests network connectivity by sending ICMP packets to a host and receiving replies.

Example:
```bash
ping google.com
```

These system and process management commands are essential for monitoring and controlling your Linux system. In the next page, we'll cover network and file transfer commands.

[Next: Page 4 - Networking and File Transfer](Page-4.md)

---

Continue to the next page (Page 4) to learn about Ubuntu Linux commands related to networking and file transfer.