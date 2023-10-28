CHALLENGE: The password for this level can be retrieved by submitting the password of the current level to port 30000 on localhost.

COMMAND: nc localhost 30000
enter the password for current level 
i.e. fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

we get the password

Explanation: After login to bandit14 with the private key, we can redirect the content of /etc/bandit_pass/bandit14 to netcat using the 'nc' command.

FLAG: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt 