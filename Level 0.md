CHALLENGE: The goal of this level is to log into the game using ssh.
GIVEN: The host to which we need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0.
FLAG: bandit0
STEPS TAKEN: To connect to a ssh server we write the command as
ssh <username>@<host> -p <portnumber>
In this case it's ssh bandit0@bandit.labs.overthewire.org -p 2220
After entering the command it asks for confirmation, enter yes
Now enter password which is bandit0.
We have now logged into the game
