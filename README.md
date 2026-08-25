# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="841" height="126" alt="image" src="https://github.com/user-attachments/assets/3036df4f-9b3f-4f9e-a329-9c06b4bcb662" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="809" height="69" alt="image" src="https://github.com/user-attachments/assets/9ecef696-0e30-47fd-8fd4-2f9036da6f7f" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="819" height="131" alt="image" src="https://github.com/user-attachments/assets/b8f67174-ff8c-447a-b617-9ac6b7b094f3" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="791" height="48" alt="image" src="https://github.com/user-attachments/assets/35f63fe2-1160-4983-a574-d7e844d66ce6" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="815" height="76" alt="image" src="https://github.com/user-attachments/assets/b99a0017-a5da-487f-82ea-37451ff66e98" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="800" height="157" alt="image" src="https://github.com/user-attachments/assets/120cc65b-3fd6-444d-bdb6-26128e99527e" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="811" height="151" alt="image" src="https://github.com/user-attachments/assets/2a1f532a-5fe1-44b9-a3d1-bfa0a6fb7e84" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="796" height="33" alt="image" src="https://github.com/user-attachments/assets/37911dfa-7b5f-493c-8d93-39ece333c0d9" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="821" height="142" alt="image" src="https://github.com/user-attachments/assets/da0c13cb-f230-44a2-8b26-d09ccfdeb82b" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

<img width="801" height="161" alt="image" src="https://github.com/user-attachments/assets/8ef39651-db4c-49f0-8994-f48e951a2d83" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="801" height="44" alt="image" src="https://github.com/user-attachments/assets/ec7f9cfd-b44f-449c-80c4-b65dbb2374ae" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

<img width="787" height="206" alt="image" src="https://github.com/user-attachments/assets/bbddb48a-dacd-4da4-bc5d-41455e13d4fb" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="816" height="196" alt="image" src="https://github.com/user-attachments/assets/9ae6cca5-705b-4711-b3e6-888f57abfc5f" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="814" height="87" alt="image" src="https://github.com/user-attachments/assets/63bbc611-649e-458a-8876-8acec1c872e0" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="703" height="76" alt="image" src="https://github.com/user-attachments/assets/354697ac-f795-4f83-ab32-10fe315db276" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

<img width="773" height="64" alt="image" src="https://github.com/user-attachments/assets/dfbb8599-f101-405c-a4bd-f9b6f4ead170" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="665" height="83" alt="image" src="https://github.com/user-attachments/assets/6c4316d2-0407-4913-bfbe-cb207c0fef88" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="801" height="127" alt="image" src="https://github.com/user-attachments/assets/f00af9d7-3cea-4ba3-a9f8-ca173803a3ec" />



### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="776" height="88" alt="image" src="https://github.com/user-attachments/assets/08bc15a9-3364-4609-92af-d58253eca815" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="756" height="143" alt="image" src="https://github.com/user-attachments/assets/152e37a8-6e71-4fce-994b-2c199ec77791" />


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="785" height="292" alt="image" src="https://github.com/user-attachments/assets/b3aea4e3-9183-494d-a4cf-1feaad530b32" />


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="774" height="111" alt="image" src="https://github.com/user-attachments/assets/d49aee72-7531-4aad-a5f0-fbc4af4a2899" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

<img width="757" height="131" alt="image" src="https://github.com/user-attachments/assets/fd55fec1-080f-4353-a510-9c554b97ddb7" />


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

<img width="775" height="159" alt="image" src="https://github.com/user-attachments/assets/c69a9ab1-314e-41d1-a888-7148842395b7" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

## Result
