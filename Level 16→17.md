CHALLENGE: The credentials for the level is to be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First we have to find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back whatever we send to it.

COMMANDS: 
1. nmap localhost -p 31000-32000

![Alt text](<Screenshot 2023-10-28 at 7.11.04 PM.png>)

These are ports which have a server listening on them.

2. ncat --ssl localhost <portnumber>

try all the ports above to find out which of those speak SSL and which don't.

OUTPUT: port 31790 speaks SSL

after entering the current password we get a RSA private key

![Alt text](<Screenshot 2023-10-28 at 7.29.55 PM.png>) 

use the vim command to store it for further use on Desktop. Give the private key 400 permissions.

3. ssh -i key bandit17@bandit.labs.overthewire.org -p 2220

Display the contents of /etc/bandit_pass/bandit17.
cat /etc/bandit_pass/bandit17

FLAG: VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e


