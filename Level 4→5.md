CHALLENGE: To access the only human readable file in the inhere directory.

COMMANDS: 
1. ls 
to view all the files and directories present

2. cd inhere/
to change the present directory to inhere.

3. ls 
Files present in the inhere directory:-
-file00  -file01  -file02  -file03  -file04  -file05  -file06  -file07  -file08  -file09 

4. find . -type f | xargs file
to find the only human readable file.

![Alt text](<Screenshot 2023-10-28 at 11.31.37 AM.png>)

5. cat ./-file07

Flag: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR