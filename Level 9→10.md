CHALLENGE: The password for this level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

COMMANDS: 
1. ls
data.txt file is present.

2. cat data.txt
OUTPUT: We have quite a few strings.

3. To find the string preceded by several ‘=’ characters, run the following command.

strings data.txt | grep "="

OUTPUT: ![Alt text](<Screenshot 2023-10-28 at 1.11.22 PM.png>)

FLAG: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s