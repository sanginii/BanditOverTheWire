CHALLENGE: To access a file stored somewhere on the server and has all of the following properties:
~owned by user bandit7
~owned by group bandit6
~33 bytes in size

COMMANDS: 
1. Our goal is to find the file owned by user bandit7,
owned by group bandit6 and 33 bytes in size, for this we run the following command.
find / -type f -user bandit7 -group bandit6 -size 33c
'/' is used beacause we are searching for the file in the entire filesystem.

OUTPUT - among various files there is one file named as /var/lib/dpkg/info/bandit7.password

2. cat /var/lib/dpkg/info/bandit7.password
FLAG: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S 