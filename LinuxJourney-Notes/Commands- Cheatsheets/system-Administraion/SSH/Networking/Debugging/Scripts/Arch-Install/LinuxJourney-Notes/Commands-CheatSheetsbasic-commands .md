Basic Linux Commands – Starter Cheat Sheet
These are the first Linux commands I will learn and practice as I begin my Linux journey.


 Navigation
```bash
pwd         # show current directory
ls          # list files
ls -l       # long listing format
ls -a       # show hidden files
cd /path    # change directory
cd ..       # move up one directory
cd ~        # go to home directory

File & Directory Management
Bash
mkdir name        # make directory
rmdir name        # remove empty directory
touch file.txt    # create empty file
cp old new        # copy file
mv old new        # move/rename file
rm file.txt       # remove file

Viewing Files
Bash
cat file.txt      # view file
less file.txt     # scroll through file
head file.txt     # view first lines
tail file.txt     # view last lines

System Info
Bash
whoami            # current user
id                # user/group info
uname -a          # system info
df -h             # disk usage
free -h           # memory usage
