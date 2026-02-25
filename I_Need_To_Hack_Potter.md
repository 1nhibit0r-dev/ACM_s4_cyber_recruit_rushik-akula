Description: I captured professor quirrell network activity though capturing the packets. Help me to solve it.

- The challenge gave a pcap file which contained the logs of communication between two entities.
- I filtered through the http communications and extracted and downloaded the files from those communication.
- After receiving some images, I used exiftool on the images and I got the first part of the flag in ron.jpg. Alternatively I also used Ghex to analyze the metadata of the images and found it.
- The second part of the flag was in hermoine.jpg. I got it when I looked for any data which was after the EOI marker and I found the second part of the flag there.

flag: ACM{w3_4r3_cyb3rw1tch3s_$nd_w1z4rds}