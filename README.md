# List of most used commands in terminal

## Navigating inside terminal

- cd .. -> get back one folder
- cd <path of the folder> -> to enter in a specific folder
- ls -lah -> list directory with all files and hidden folders
- mkdir -> create directory
- touch -> create a file
- echo "Message" -> output text in double quotes in a terminal 
- rm -r -> remove file or folder
- man -> To get manual
- mv <source path> <target path> -> move files
- cp <source path> <target path> -> 
- pwd -> show complete path
- cat <path of file> -> output content from a file
- open <path of file> -> open a file using the default application
- less -> to show content limited

## Change permissions

- chmod XYZ <name of the file> -> change permissions using decimal values
- chmod ugo+rwx <name of the file> -> change permissions using links
- chmod -R ugo+rwx -> change permissions recursively
- sudo -> to become root
- chgrp -> change the group from the file
- chown -> change the owner of the file
## The permissions table value
rwx - Binary (octal) -> Represented by a decimal value 
000 = 0 = ---
001 = 1 = --x
010 = 2 = -w-
011 = 3 = -wx
100 = 4 = r--
101 = 5 = r-x
110 = 6 = rw-
111 = 7 = rwx
obs: A 0 means not set, a 1 means set in each position