CHALLENGE: To access a file somewhere under the inhere directory and has all of the following properties:
1. human-readable
2. 1033 bytes in size
3. not executable

COMMANDS: 
1. ls 

2. cd inhere/

3. ls
Files in the inhere directory:-
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16 maybehere01  maybehere05  maybehere09  maybehere13  maybehere17 maybehere02  maybehere06  maybehere10  maybehere14  maybehere18 maybehere03  maybehere07  maybehere11  maybehere15  maybehere19

4. Our goal is to find the human-readable, not executable,and 1033 bytes in size file, for this we run the following command.

find . -type f -readable -size 1033c ! -executable

OUTPUT - ./maybehere07/.file2

5. cat ./maybehere07/.file2

FLAG: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
