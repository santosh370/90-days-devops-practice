# AWS Linux Commands

### General commands
  
- `ls`: Show list of contents of current directory or given directory.
- `cd <directory-name>`: Change directory. 
- `cd ..`: Go one directory back from current directory.
- `cd` : Go to home directory.
- `cd ..` : Go one directory back from current directory.
- `mkdir <directory-name>`: Create a new directory/folder with given name at current position.
- `rmdir <dir-name>`: Remove the given directory name.
- `touch <file-name>`: Create a new file with given name.
- `vi <file-name>`: Create a new file if not exist or edit if exist.
- `rm <file-name>`: Remove the give file.
- `cp <source> <destination>` — Copying file(s) from source to destination.
- `mv <source> <destination>` — Move or rename files or directories from source to destination.
- `cat <file-name>`: Display the content of given file name.
- `more`: View the contents of a file one page at a time.
- `less`: View the contents of a file one page at a time, with the ability to scroll back and forth.
- `grep`: Search for a pattern in a file.
- `awk`: Process text files.
- `sed`: Edit text files.
- `sudo <command>`: (Do task using super user) Execute a command as root or super user.
- `pwd`: To Print current working directory.
- `clear`: Clear the terminal display.
- `echo "Hello world"`: Print any text that follows the command.
- `history`: Display list of executed commands.
  

### Directory/folder management
- `mkdir <dir-name>` : Create a new directory.
- `mkdir -p a/b/c` : Create directories in given hierarchy.
- `touch <file-name>` : create a new blank file.
- `pwd` : Display path of current working directory.
- `cat <file-name>` : Display file content.
- `cat > <file-name>` : Create a blank file with given name.
- `cat >> <file-name>` : Append the file
- `cat  <file-name1> >> <file-name2>` : Append the content of the file file-name1 at the end of the file <file-name2>.
- `cat <file-name1> <file-name2> ` : Display both files content at same time.
- `cat <file-name1> <file-name2> > <merge-file-name>` : Merge both of files content in a single one with given name.
- `cat <file-name> | tr > <new-file-name>` : Translate the file.
- `cut -c  1-2 <file-name>` : cut the file column wise
- `echo "Hello" >> <file-name>` : Create a new file with content "Hello".
- `man <command-name>`: Know more about the command usages and options. Its basically display all the syntax, how you will use.
- `cp <source> <destination>`: Make a copy of a file in the current location.
- `mv <file-name> <dir-path>`: Move a file from one dir to another.
- `mv <file-name> <new-fie-name>`: Rename a file.
- `mv -R <dir-name> <dir-path>`: Move Dir
- `rm <file-name>`: Remove a file permanently.
- `rm -R <file-name>`: Delete a folder with dir included.
- `head <file-name>`: Will display first 10 lines of a file.
- `tail <file-name>`: Will display last 10 lines of a file.
    -`-n 2`: will display last 2 lines.
- `diff <file-1> <file-2>`: Show difference between the two given files file-1 & file-2.
- `locate <file-name>`: To find out the file.  
- `find <file/folder-name>`: Find a file/folder.
- `find <dir-name>`: Find files inside the dir


### File system commands
- `df`: Display disk usage.
- `du`: Display the disk space usage of files and directories.
- `mount`: Mount a file system.
- `umount`: Unmount a file system.
- `mkfs`: Format a file system.
- `fsck`: Check and repair a file system.
- `cp`: Copy files and directories.
- `mv`: Move files and directories.
- `rm`: Remove files and directories.
- `find`: Search for files and directories.
- `tar`: Create and extract tar archives.
- `gzip`: Compress and decompress files.
- `bzip2`: Compress and decompress files.

## Process management
- `ps`: List the active/running processes.
- `top`: View a dynamic list of running processes with their system usage.
- `kill`: Terminate a process.
- `nice`: Change the priority of a process.
- `renice`: Change the priority of a running process.
- `bg`: Send a job to the background.
- `fg`: Bring a job to the foreground.
- `jobs`: List the background jobs.
- `disown`: Remove a job from the job list.

## System commands
- `uname`: Linux command to get basic information about the OS.
- `df -h`: Display disk filesystem information. -h is human readable
- `du`: Display disk uses
- `free -m`: Display free

## User and group management
- `sudo useradd <username>`: Add a new user with given username
- `sudo passwd <username>`: Change or set user password of given username
- `sudo userdel <username>`: Delete the user of given username 
- `sudo groupadd <groupname>`: Create new user group
- `sudo groupdel <groupname>`: Delete given user group
- `sudo usermod -g <groupname> <username> `: Assign user <username> into group <groupname>
- `groups`: Print all the groups name associated with the current user.
- `groups <user-name>`: Print all the groups name associated with the given user.
- `id`: Print user id & group id associated with current user
- `id <user-name>`: Print user id & group id associated with given user-name
- `chmod`: Command to change file permissions.
- `chown`: Command for granting ownership of files or folders.

## Networking commands
  - `nslookup <host-name>`: To check the IP address of given domain.
  - `netstat`: To check the network statistics or status.
  - `hostname`: To check the hostname.
  - `whoami`:  To check the current user name.
  - `ping <host-name>`: To check the connectivity or reachability of given host name.
  - `ifconfig`: Display the status of network interfaces.
  - `route`: Display the routing table.
  - `wget`: Download a file from the web.
  - `curl`: Open an URL with Get/Post/PUT etc.. method.
  - `ssh`: Securely connect to a remote host.
  - `scp`: Securely copy files between local and remote hosts.
  - `rsync`: Efficiently transfer files between local and remote hosts.

## Package management
  - `apt-get`:
  - `apt`:
  - `yum`:
  - `dnf`:
  - `rpm`:
  - `dpkg`:
  - `snap`:  

## Version control commands
  #### git: A distributed version control system
  - `git init`:
  - `git config`
  - `git add`
  - `git commit`
  - `git clone`
  - `git pull`
  - `git push`
  - `git revert`
  - `git rebase`
  - `git checkout`
  - `git branch`
	
  #### svn: A centralized version control system

## Other useful commands
