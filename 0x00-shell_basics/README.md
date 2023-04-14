The following are the scripts written in this project and what they do
 1. pwd to list the current working directory
 2. ls to list the files in a directory
 3. cd to move between directories
 4. ls -l to list the longer version of the files
 5. la -la to list all files including hidden files in their long format
 6. ls -la |sort -k6 to sort the listed files alphabetically using the names of the files
 7. mkdir /tmp/my_first_directory to create a directory inside tmp directory
 8. mv /tmp/betty /tmp/my_first_directory to move the file betty to the my_first_directory
 9. rm /tmp/my_first_directory/betty to delete the file betty
 10. rm -r /tmp/my_first_director to delete the directory my_first_directory
 11.cd - to move to the previous directory
 12. ls -la . .. /boot to list the files in the current directory, parent directory and boot directory
 13. file /tmp/iamafile to know the type of file oof iamafile
 14. ln -s /bin/ls __ls__ to create a link from the current directory to the /bin/ls directory
 15. cp -u *html .. to copy all html files form working directory to parent. if the file is available in the parent it only copies if the file is outdated
 16. mv [[:upper:]]* /tmp/u to move al files that begin with a capital letter to tmp/u
 17. rm *~ to remove all files that end with ~
 18. mkdir -p welcome/to/school to create a multi level directory
 19. ls -amxp --format=comma to list files and directory horizontally seperated by commas with the directories having a / 
 20. 0 string SCHOOL School date !:mime School gets saved into school.mgc to compile it use file -C -m school.mgc.
