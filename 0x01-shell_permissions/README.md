This is a project to write scripts that perform the following functions
1. su betty is to switch the current user to the user betty
2. whoami is to print the name of the current user
3. chmod --reference=olleh hello is to copy the permissions for ololeh and use it for hello
4. chown -R vincent:staff * is to change the current owner and group owner to vincent and staff for all files and directories
5. chown -h vincent:staff _hello is to change the owner and group of the symbolic link which is a directory to vincent and staff
6. chown --from=guillaume betty hello is to change the owner of the file if the file belongs to a particular user
7. telnet towel.blinkenlights.nl is to play the starwars vi episode in the terminal
8. chmod -R a+X * is to add the execute permission to all subdirectories of the current working folder without changing that of the files
9. mkdir -m 751 my_dir is to create a new directory with the permissions 751
10. chgrp school hello to change group owner
11. id -Gn prints all the groups the current user is part off
12. chown betty hello changes the owner of a fileto betty
13. touch hello creates an empty file
14. chmod u+x hello adds the execute permission to the owner of the file only
15. chmod ug+x,o+r hello adds the execute permission to the owner and group owner and the read permissions to others
16. chmod ugo+x hello adds the execute permission to the owner,group owner and others
17. chmod 007 hello adds gives others all the permissions and nothing to the owner and group owner
18. chmod 753 hello gives all the permissions to the owner, the read and execute permission to the group owner and the write and execute permission to others.
