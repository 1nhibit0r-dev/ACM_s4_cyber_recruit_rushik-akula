Description: Someone from the Hogwarts send this file given below to the voldemort.I don’t know who it is and what is the information in it. What ever the information is but it will definitely harm harry so find the person who send it. The flag lies there.


- I manually pluck the topsecret.png file out and use ghex to inspect the meta data 
- I carve out the hidden folders inside the top_secret.png. I manually carved the file out by referencing the header and the end markers of a zip file to get a zip file
- In that zip file there was a directory with a text file in it which suggests that there is a hidden directory within the folder. 
- I use the command ls -la to list out the directories and manually go to that particular directory from terminal and use exiftool to check for comments 
- I find a base64 encoded string which when decoded i got the flag

tools/commands used:
- ghex
- exiftool -sf
- ls -la

flag: potter{7h15_15_D010r35_Um8r1dg3}