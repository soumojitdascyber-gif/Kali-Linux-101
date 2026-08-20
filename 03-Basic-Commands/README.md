# 💻 Essential Kali Linux Commands Cheat Sheet

Here are the most common commands you will need daily as a cybersecurity student/analyst, including system management, file operations, and user permissions.

### ⚙️ System & Terminal Basics
```bash
CTRL + ALT + T    # Open a new terminal window
whoami            # Check currently logged-in user
uname -a          # Check complete system information
history           # View the history of executed commands
sudo su           # Switch to super user (root)
sudo apt update && sudo apt upgrade # Update and upgrade the system
```

### 📁 Directory & File Management
```bash
pwd               # Print Current Directory (Where am I?)
ls                # List files in the current directory
ls -la            # List all files with details (including hidden files)
cd <folder_name>  # Move to a specific folder
cd ..             # Move one directory up
mkdir <folder>    # Create a new folder/directory
touch file.txt    # Create a new empty file
rm <file>         # Remove/Delete a file
rm -r <folder>    # Remove a folder and its contents
rm -rf <folder>   # Force remove a folder (Use with caution!)
cp file1 file2    # Copy a file
mv file1 file2    # Move or rename a file/folder
```

### 📝 Viewing & Editing Files
```bash
cat file.txt             # View file contents
cat > file.txt           # Create a file and type content (Press CTRL+D to save)
cat >> file.txt          # Append text to an existing file (Press CTRL+D to save)
echo "hello" > file.txt  # Write "hello" directly into a file
nano file.txt            # Edit a file using the Nano text editor
vim file.txt             # Edit a file using the Vim text editor
```

### 👤 User & Group Management
```bash
id                       # Show user ID (UID) and group ID (GID)
adduser <username>       # Create a new user
passwd <username>        # Set or change a user's password
deluser <username>       # Delete a user
usermod -aG sudo <user>  # Give sudo (admin) access to a user
groupadd <groupname>     # Create a new group
groups <username>        # Show groups of a specific user
usermod -aG <group> <user> # Add user to a specific group
groupdel <groupname>     # Delete a group
```

### 🔑 File Permissions & Ownership
> **Permissions breakdown:** r (read), w (write), x (execute). 
> **Format:** User | Group | Other (e.g., `rwx r-x r--`)

```bash
ls -l                    # Show files with their permissions
chmod 777 file.txt       # Give all permissions (read, write, execute) to everyone
chmod u+x file.txt       # Add execute permission for the User (u+r, u+w, u-x to remove)
chmod g+x file.txt       # Add execute permission for the Group
chown user:group file.txt # Change the file owner and group
```
