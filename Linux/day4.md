# Day-4 : Mastering the Linux Prompt

## Understanding the Linux Command Prompt
The Linux command prompt is a powerful interface for interacting with your operating system. It allows users to execute commands, manage files, and perform administrative tasks efficiently. The prompt typically looks like this:
```
username@hostname:~$
```
## set hostname 
```
hostnamectl set-hostname <hostname> 
```
< hostname> --> set your hostname here 



### Key Components:
- **Username**: Your current user account.
- **Hostname**: The name of the computer.
- **Current Directory**: The directory you're working in (e.g., `~` for the home directory).
- **Prompt Symbol**: `$` for standard users and `#` for the root user.

## Decoding the Structure of the Command Prompt
Understanding the elements of the command prompt helps you navigate and operate more effectively:
- **`~`**: Represents the user's home directory.
- **`pwd`**: Displays the current directory.
- **`whoami`**: Reveals the current user.
- **`hostname`**: Shows the machine's name.

## Effective Command Prompt Usage: A Step-by-Step Guide
1. **Navigating Directories**:
   - `cd` to change directories.
   - `ls` to list files and directories.
   - `pwd` to print the working directory.

2. **Managing Files**:
   - `touch filename` to create an empty file.
   - `mkdir dirname` to create a new directory.
   - `rm filename` to delete a file.

3. **Getting Help**:
   - `man command` to view the manual for a command.
   - `--help` for a quick command reference (e.g., `ls --help`).

4. **Running Commands as Root**:
   - Use `sudo` before commands to execute with administrative privileges.

## Introduction to Linux Basic Commands
<img width="1470" height="956" alt="Screenshot 2026-03-13 at 1 35 06 PM" src="https://github.com/user-attachments/assets/f6d7fd76-43c5-4d55-b051-756d5b9623bf" />

Learning the basic commands is essential to mastering Linux:
- **`ls`**: Lists files and directories.
- **`cp`**: Copies files.
- **`mv`**: Moves or renames files.
- **`rm`**: Removes files or directories.


### Tips for Beginners:
- Use `Tab` for auto-completion.
- Use `Up` and `Down` arrow keys to cycle through command history.
