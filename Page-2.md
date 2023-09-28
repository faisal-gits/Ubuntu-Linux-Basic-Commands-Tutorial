# Ubuntu Linux Basic Commands Tutorial

## Page 2: File Management and Navigation

Welcome to Page 2 of our Ubuntu Linux Basic Commands Tutorial. In this section, we'll delve further into file management and navigation commands to enhance your Linux skills.

### 11. `cat` - Concatenate and Display File Contents

The `cat` command is used to display the contents of a file on the terminal. It's often used for viewing small files.

Example:
```bash
cat file.txt
```

### 12. `grep` - Search Text in Files

`grep` is a powerful text-search tool. It searches for a specified text pattern in files and displays matching lines.

Example:
```bash
grep "keyword" file.txt
```

### 13. `sed` - Stream Editor

`sed` is a stream editor that can find, replace, or delete text in files. It's a versatile tool for text manipulation.

Example (Replace "old" with "new" in a file):
```bash
sed 's/old/new/g' file.txt
```

### 14. `head` - Display the First Lines of a File

`head` displays the first few lines of a file. By default, it shows the first ten lines.

Example:
```bash
head file.txt
```

### 15. `tail` - Display the Last Lines of a File

`tail` shows the last few lines of a file. By default, it displays the last ten lines.

Example:
```bash
tail file.txt
```

### 16. `awk` - Text Processing Tool

`awk` is a versatile text processing tool. It's often used for data extraction and manipulation.

Example (Print the second column of a CSV file):
```bash
awk -F',' '{print $2}' data.csv
```

### 17. `sort` - Sort Lines in a File

The `sort` command arranges the lines of a file in alphabetical or numerical order.

Example:
```bash
sort file.txt
```

### 18. `cut` - Extract Sections from a File

`cut` is used to extract specific columns or sections from a file based on delimiters.

Example (Extract the second field from a CSV file):
```bash
cut -d',' -f2 data.csv
```

### 19. `diff` - Compare Files

`diff` compares two text files and shows the differences between them.

Example:
```bash
diff file1.txt file2.txt
```

### 20. `tee` - Redirect Output to a File

The `tee` command allows you to capture command output and save it to a file while still displaying it on the terminal.

Example:
```bash
ls | tee list.txt
```

These file management and text processing commands are essential for working with data and files in Linux. In the next page, we'll cover system-related commands and more.

[Next: Page 3 - System and Process Management](Page-3.md)

---

Continue to the next page (Page 3) to explore Ubuntu Linux commands related to system and process management.