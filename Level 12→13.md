CHALLENGE: The password for this level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. 

COMMANDS: 
1. ls
data.txt file is present.

2. cat data.txt
OUTPUT: hexdump data.

3. mkdir - to make a directory
mkdir /tmp/sangini

4. cp - to copy data.txt file into the directory.
cp data.txt /tmp/sangini

5. cd /tmp/sangini 
changing directory to tmp

6. xxd - make a hexdump or do the reverse.
adding -r to revert.
xxd -r data.txt > data

7. file - to check the file type
file data 
![Alt text](<Screenshot 2023-10-28 at 5.19.15 PM.png>) 

8. mv - to rename the filename
mv data data.gz

9. gzip - to compress and expand files.
gzip -d data.gz

Repeat the steps again 
a) check the filetype
b) rename the file
c) decompress it 

for bzip2 compressed data run the command: bzip2 -d data.bz2
for tar archive: tar xf data.tar 

at last we get data: ASCII text

10. cat data

FLAG: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw 