CHALLENGE: The password for this level is stored in the file data.txt, which contains base64 encoded data.

COMMANDS: 
1. ls
data.txt file is present.

2. cat data.txt
OUTPUT: VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg==

This is base64 encoded, we have to decode it.

3. To decode the above text we use the command "base64" along with "-d" which means decode.

base64 -d data.txt

OUTPUT: The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

FLAG: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM 