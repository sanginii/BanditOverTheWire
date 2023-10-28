CHALLENGE: The password for this level is stored in the file data.txt and is the only line of text that occurs only once.

COMMANDS: 
1. ls
data.txt file is present.

2. cat data.txt
OUTPUT: We have quite a few lines of text, which we now have to sort to find the password.

3. To sort the text we use "sort" command as the name suggests it sorts lines of text files.

OUTPUT: We have now lines of text sorted in alphabetical order.

4. To report or omit repeated lines we use the "uniq" command.

sort data.txt | uniq -c
-c gives the number of times a line of text is repeated.'

OUTPUT: ![Alt text](<Screenshot 2023-10-28 at 12.58.59 PM.png>)
We can see the line of text which is repeated only once.

FLAG: EN632PlfYiZbn3PhVK3XOGSlNInNE00t