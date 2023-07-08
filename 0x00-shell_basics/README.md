0-current_working_directory prints the absolute path name of the current working directory. the command is echo "$(pwd)".  
1-listit displays the contents in the current directory. The command is ls  
2-bring_me_home changes the working directory to the home directory. The command is cd ~. The ~ returns the user to the home directory.  
3-listfiles lists current directory contents in long format. The command is ls -l. The -l lists all the files in the dirrectory in long format, including the users and permissions, ownership file sizes and modification dates.  
4-listmorefiles lists all files including hidden ones in long format. The command is ls -al. The -a lists all hidden files (files that start with .)  
5-listfilesdigitonly lists all files including hidden ones in long format with user and group IDs displayed numerically. The command is ls -aln. The n lists files by displaying numeric user and group IDs instead of resolving them to their corresponding names.  
6-firstdirectory creates a directory inside the tmp directory. The command is mkdir /tmp/my_first_directory.  
7-movethatfile moves the file betty from /tmp to /tmp/my_first_directory. The command is mv /tmp/betty /tmp/my_first_directory. The first part describes the current location of the file while the second part is the desired destination.  
8-firstdelete deletes the file betty. The command is rm /tmp/my_first_directory/betty. rm is the delete command and the rest is just the location of the file.  
9-firstdirdeletion deletes the directory my_first_directory. The command is rm -r /tmp/my_first_directory. rm -r is used to remove non-empty directories with all the files inside.  
10-back changes working directory to the previous one. The command is cd -. The  - is shorthand for the previous directory.  
11-lists lists all files including hidden ones in the current, parent and /boot directory respectively. The command ls -al . .. /boot is used to list the detailed information of files and directories in the current directory (.), the parent directory (..), and the /boot directory.  
12-file_type prints the type of file of file named iamafile. The command is file /tmp/iamafile. The file command prints the type of file.  
13-symbolic_link creates a symolic link to /bin/ls
14-copy_html copies html files from working directory to parent directory
100-lets_move moves all files beginning with a capital letter
101-clean_emacs removes all files in the working directory beginning with the character ~
102-tree creates the directory welcome/ welcome/to/ and welcome/to/school
103-commas lists files in current directory separeated by commas

