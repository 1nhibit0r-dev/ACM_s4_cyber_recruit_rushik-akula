Description:
 I got the letter from hogwarts but it was password encrypted help me to find, lets try until we get the password the password for the pdf. In that pdf u can get the flag.

- first i extracted the hash of the pdf given
- next i run a dictionary attack on it using the rockyou.txt file which is already available with kali linux which contains all fairly probable passwords possible 
- the attack will be successful and will generate the password with which i unlocked to get the flag

commands/tools used:
- pdf2john.py challenge.pdf > hash.txt
- john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt

flag: potter{w3lc0m3_70_h0gw4r75}