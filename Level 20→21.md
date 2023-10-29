CHALLENGE: There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).

COMMAND: 
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

Just read the cronjob_bandit22.sh script executed by cron. You’ll see where the password will be stored

FLAG: NvEJF7oVjkddltPSrdKEFOllh9V1IBcq