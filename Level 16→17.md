CHALLENGE: The credentials for the level is to be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First we have to find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back whatever we send to it.

COMMANDS: 
1. nmap localhost -p 31000-32000
![Alt text](<Screenshot 2023-10-28 at 7.11.04 PM.png>)
These are ports which have a server listening on them.

2. ncat --ssl localhost <portnumber>
try all the ports above to find out which of those speak SSL and which don't

OUTPUT: port 31790 speaks SSL

after entering the current password we get a RSA private key


