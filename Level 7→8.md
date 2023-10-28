CHALLENGE: The password for this level is stored in the file data.txt next to the word millionth.

COMMANDS: 
1. ls
data.txt file is present.

2. cat data.txt
OUTPUT: We have quite a few strings, which we now have to sort to find the password.

3. To sort the strings we use the "strings" command, it print the strings of printable characters in files. 

Along with 'strings' we use 'grep' command which print's lines that match patterns.

strings data.txt | grep "millionth"

OUTPUT: millionth       TESKZC0XvTetK0S9xNwm25STk5iWrBvP

FLAG: TESKZC0XvTetK0S9xNwm25STk5iWrBvP 