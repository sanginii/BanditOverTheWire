CHALLENGE: The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.

COMMANDS: the password is stored in a file named "readme" in the home directory. However, there is a modification to the .bashrc file that logs you out upon SSH login. To overcome this, we can use the -t (pseudo-terminal) option to run a specific command. In this case, we'll use cat to read the contents of the "readme" file:

FLAG: awhqfNnAbc1naukrpqDYcF95h7HoMTrC