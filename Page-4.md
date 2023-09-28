# Ubuntu Linux Basic Commands Tutorial

## Page 4: Networking and File Transfer

Welcome to Page 4 of our Ubuntu Linux Basic Commands Tutorial. In this section, we'll explore commands related to networking, file transfer, and system administration.

### 35. `wget` - Download Files from the Web

`wget` is used to download files from the internet using a URL.

Example:
```bash
wget https://example.com/file.zip
```

### 36. `curl` - Transfer Data with URLs

`curl` can be used for transferring data to or from a server using various protocols, including HTTP, FTP, and more.

Example:
```bash
curl -O https://example.com/file.txt
```

### 37. `scp` - Securely Copy Files over SSH

`scp` allows you to securely copy files and directories between different systems using SSH.

Example (Copy a file to a remote server):
```bash
scp localfile.txt user@remote_host:/path/to/destination/
```

### 38. `rsync` - Efficiently Synchronize Files

`rsync` synchronizes files and directories between two locations, efficiently transferring only the differences.

Example (Sync local directory to a remote server):
```bash
rsync -avz /local/directory/ user@remote_host:/remote/directory/
```

### 39. `ifconfig` - Network Interface Configuration

`ifconfig` displays information about network interfaces and their configurations.

Example:
```bash
ifconfig
```

### 40. `netstat` - Network Statistics

`netstat` provides network-related information, including active network connections, routing tables, and more.

Example (List all network connections):
```bash
netstat -tuln
```

### 41. `traceroute` - Trace Packet Routes

`traceroute` traces the route that packets take to reach a destination, showing each hop.

Example:
```bash
traceroute google.com
```

### 42. `nslookup` - DNS Query

`nslookup` is used to query DNS servers to retrieve DNS-related information, such as IP addresses.

Example:
```bash
nslookup example.com
```

### 43. `dig` - DNS Information Tool

Similar to `nslookup`, `dig` provides detailed DNS information, including record types.

Example:
```bash
dig google.com
```

### 44. `history` - Command History

`history` displays a list of previously executed commands, helping you track your command history.

Example:
```bash
history
```

### 45. `man` - Manual Pages

`man` is used to access the manual pages for various commands, providing detailed documentation.

Example (View the manual for `ls`):
```bash
man ls
```

### 46. `echo` - Print Text

`echo` is used to print messages or variables to the terminal.

Example:
```bash
echo "Hello, Linux!"
```

These networking, file transfer, and system administration commands are essential for managing network connections, transferring files, and accessing documentation. In the next page, we'll cover user and file permissions.

[Next: Page 5 - User and File Permissions](Page-5.md)

---

Continue to the next page (Page 5) to explore Ubuntu Linux commands related to user management and file permissions.