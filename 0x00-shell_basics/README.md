0-current_working_directory - pwd
* Write a script that prints the absolute path name of the current working directory
1-listit - ls
* Display the contents list of your current directory
2-bring_me_home - cd
* Write a script that changes the working directory to the user’s home directory.
3-listfiles -ls -l
* Display current directory contents in a long format
4-listmorefiles - ls -la
*Display current directory contents, including hidden files (starting with .)
5-listfilesdigitonly - ls -la
* Display current directory contents.Long format,with user and group IDs displayed numerically,And hidden files (starting with .)
6-firstdirectory - mkdir /tmp/my_first_directory
* Create a script that creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile - mv /tmp/betty /tmp/my_first_directory
* Move the file betty from /tmp/ to /tmp/my_first_directory
 8-firstdelete - rm /tmp/my_first_directory/betty
* Delete the file betty.The file betty is in /tmp/my_first_directory
9-firstdirdeletion - rm -r /tmp/my_first_directory
* Delete the directory my_first_directory that is in the /tmp directory.
10-back - cd -
* Write a script that changes the working directory to the previous one.
11-lists - ls -la . .. /boot
* Write a script that lists all files with hidden folders and with parent working directory and /boot
12-file_type - file /tmp/iamafile
* Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script 
13-symbolic_link - ln /bash/ls __ls__
*Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14-copy_html- cp -u *.html ..
* copy all HTML files in  from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
100-lets_move -mv [[:upper:]]* /tmp/u
* Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script
101-clean_emacs - mv [[:upper:]]* /tmp/u
* Create a script that deletes all files in the current working directory that end with the character ~.
102-tree - mkdir -p welcome/to/school
* Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more.
103-commas - ls -xamp
* Write a command that lists all the files and directories of the current directory, separated by commas (,).
school.mgc -


