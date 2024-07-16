# Basic Linux Commands

## Listing Commands

The general syntax for listing commands is:

```
ls [option_flag] [arguments]
```

This command lists the sub-directories and files available in the present directory.

### Examples:

1. List files and directories in long list format with extra information:
   ```
   ls -l
   ```

2. List all files and directories, including hidden ones:
   ```
   ls -a
   ```

3. List all files with a specific extension (e.g., .sh):
   ```
   ls -l *.sh
   ```

4. List files and directories with their inode numbers:
   ```
   ls -i
   ```
   Note: Inodes are unique within the filesystem, helping to uniquely identify files or directories at a filesystem level.

## Directory Commands

1. Print current working directory:
   ```
   pwd
   ```

2. Change directory:
   ```
   cd [directory_name]
   ```
   Example: `cd dev` changes to the 'dev' directory

3. Change to home directory:
   ```
   cd ~
   ```
   or simply
   ```
   cd
   ```

4. Go to the last working directory:
   ```
   cd -
   ```

5. Move one directory level up:
   ```
   cd ..
   ```

6. Move two directory levels up:
   ```
   cd ../..
   ```

7. Create a new directory:
   ```
   mkdir [directory_name]
   ```
   Example: `mkdir dev2` creates a new directory named 'dev2'
