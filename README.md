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
- cp <source path> <target path> -> to copy a file from the source path to target path
- pwd -> show complete path
- cat <path of file> -> output content from a file
- open <path of file> -> open a file using the default application
- less -> to show content limited
- more -> to show content limited to one page per time
- whoami -> to know which user you are using
- ln -> to creat symbolic link
- sort -> to sort the file

## Change permissions

- chmod XYZ <name of the file> -> change permissions using decimal values
- chmod ugo+rwx <name of the file> -> change permissions using links
- chmod -R ugo+rwx -> change permissions recursively
- sudo -> to become root
- chgrp -> change the group from the file
- chown -> change the owner of the file
## The permissions table value
rwx - Binary (octal) -> Represented by a decimal value <br>
000 &nbsp;= 0 =&nbsp; --- <br>
001 &nbsp;= 1 =&nbsp; --x <br>
010 &nbsp;= 2 =&nbsp; -w- <br>
011 &nbsp;= 3 =&nbsp; -wx <br>
100 &nbsp;= 4 =&nbsp; r-- <br>
101 &nbsp;= 5 =&nbsp; r-x <br>
110 &nbsp;= 6 =&nbsp; rw- <br>
111 &nbsp;= 7 =&nbsp; rwx <br>
obs: A 0 means not set, a 1 means set in each position
