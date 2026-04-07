## Session 1a – Setting Up Linux

### Tasks Completed
- Prepared a GitHub repository for documenting lab activities.
- Downloaded the Ubuntu Desktop ISO from the official Ubuntu website.
- Installed Oracle VirtualBox.
- Downloaded ubuntu-24.04.4-desktop-amd64.iso
- Created a new Ubuntu virtual machine.
- Configured the virtual machine with suitable memory, processor, and storage settings.
- Mounted the Ubuntu ISO and completed the installation.
- Booted successfully into the Ubuntu desktop environment.

### Evidence
![Ubuntu VM](./Lab1/VirtualBox_n7IV5SYyKg.png)
![Ubuntu Desktop](./Lab1/VirtualBoxVM_AviQvEASTN.png)


## Session 1a – Basic Command Line Navigation and Utilities

### Commands Practised
The following commands were used in this lab:
- `pwd` to show the current working directory
- `ls` to list files and folders
- `cd` to move between directories
- `mkdir` to create a new directory
- `touch` to create a new file
- `man` to read the manual page for a command


#### 1. Check the current working directory
The `pwd` command was used to display the current directory in the terminal.

    pwd

#### 2. List files and folders
The `ls` command was used to view the contents of the current directory.

    ls

A more detailed view was also displayed using:

    ls -l

Hidden files were displayed using:

    ls -a

#### 3. Move between directories
The `cd` command was used to move between directories.

    cd /home
    cd ~
    cd ..

#### 4. Create a new directory
A test directory was created using `mkdir`.

    mkdir lab1practice

#### 5. Create a new file
A new file was created inside the folder using `touch`.

    cd lab1practice
    touch testfile.txt
    ls -l

#### 6. View command manuals
The `man` command was used to read the manual page for a Linux command.

    man ls

#### 7. Explore important Linux directories
The following important directories were explored:
- `/home` – stores user files and personal folders
- `/etc` – stores system configuration files
- `/var` – stores variable data such as logs and cache

Example commands used:

    cd /home
    ls
    cd /etc
    ls
    cd /var
    ls

### Evidence
![Screenshot 3](Lab1/3.png)
![Screenshot 4](Lab1/4.png)
![Screenshot 5](Lab1/5.png)
![Screenshot 6](Lab1/6.png)
![Screenshot 7](Lab1/7.png)
