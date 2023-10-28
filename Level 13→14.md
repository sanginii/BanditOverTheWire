CHALLENGE: The password for this level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, we don’t get the next password, but we get a private SSH key that can be used to log into the next level. 

COMMANDS:
1. ls
OUTPUT: sshkey.private

2. exit 

3. Here, we download the private key to login to the next level.

ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220

after the confirmation we enter yes

we are logged into bandit14.

4. To get the password for this current level we run the command
cat /etc/bandit pass/bandit14

FLAG: fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq