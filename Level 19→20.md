CHALENGE: To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

COMMAND: 
1. ls -l
We see that we have a setuid binary file called bandit20-do. Let's execute it. ./bandit20-do
A setuid binary file allows one to execute commands with elevated priviledges. In this case, we get the priviledges of the user "bandit20".

2. cat /etc/bandit_pass file.

./bandit20-do cat /etc/bandit_pass/bandit20

FLAG: VxCazJaVykI6W36BkBU0mJTCM8rR95XT