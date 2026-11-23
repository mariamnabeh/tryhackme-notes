
# Linux Terminal – Basic Commands

## 1. User Information
```bash
whoami          # Displays the current logged-in username
id              # Displays user ID, group ID, and groups
```

## 2. Navigation & Directories
```bash
pwd             # Prints the current working directory
ls              # Lists files and directories
ls -a           # Lists all files, including hidden files
ls -l           # Lists files with detailed information
ls -a -l        # Lists all files in detailed format
ls -al          # Same as ls -a -l
ls -alf         # Lists all files in detailed format with file type indicators
cd pictures     # Moves into the pictures directory
cd ..           # Moves one directory up
cd /            # Moves to the root directory
cd ~            # Moves to the user's home directory
cd              # Also moves to the user's home directory
clear           # Clears the terminal screen
```

## 3. Help & History
```bash
ls --help       # Displays help and available options for ls
history         # Displays previously executed commands
```

## 4. Creating Files & Directories
```bash
mkdir mariamnabeh   # Creates a new directory
touch mariam        # Creates an empty file
touch file          # Creates an empty file
```

## 5. Displaying Text & File Content
```bash
echo "Hello world"  # Prints text to the terminal
cat /etc/hosts      # Displays the contents of the hosts file
cat hosts           # Displays the contents of hosts
```

## 6. Copying & Removing Files
```bash
cp /etc/hosts /home/vega/   # Copies hosts into the vega directory
rm file                    # Deletes a file
```

## 7. Administrator Commands
```bash
sudo touch file       # Creates a file with administrator privileges
sudo apt install vim  # Installs the Vim text editor
```

## 8. Text Editor
```bash
vi hosts        # Opens hosts using the Vi editor
vim hosts       # Opens hosts using Vim
```

## 9. Processes
```bash
ps              # Displays currently running processes
```

## 10. Network Information
```bash
ip address      # Displays network interfaces and IP addresses
```

## 11. Important Linux Paths
```bash
/etc/           # System configuration files
/dev/           # Device files
/home/          # Users' home directories
/root/          # Root user's home directory
```
