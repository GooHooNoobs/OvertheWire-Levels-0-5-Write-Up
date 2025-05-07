# OvertheWire-Levels-0-5-Write-Up
A brief overview of my experience completing Overthewire labs 0 - 5.


Hi, I'm GooHooNoobs I started my Google Cybersecurity Certificate in August of 2024, and completed it in Decemeber, 2024. While it was very intuitive I learned soon after there were a couple of skills that I was lacking. So for the past few months I have been surfing the internet using various sites to help me develop new skills and gain a greater understanding of cybersecurity.


From the top, Level 0.

This level introduces the most basic commands of the linux shell ls, which lists your current directories content. And cat which is use to open files. 

This level is a quick snap for people with basic experience in linux but it does a good job of introducing two of the most basic commands in linux.


Moving on, Level 1.

This next level is a little more advanced and it took me some time to figure out a solution.

In this level the goal is to open a file named "-" in the home directory.

While it seems like a quick "cat -" would solve this issue, because of the file name this format cannot be used.

The point of this level is to show you have to interact with files that have operators that could run a syntax error.

To solve this I used ./ to tell the ssh that whatever was coming after this wasnt a command but a string.



Moving on, Level 2

This level is similar to its predecessor but this time the file name has spaces in its name.

Seeing this I instantly knew from previous programming experience what was needed and that even with "./" the spaces would run an error.

From my prespective I believe this level aims to broaden your view point on file names and show you that tossing "./" isn't just a cureall and sometimes there need to be other parameters.

As stated I instantly knew what needed to be done and proceeded to "" after "./" as to tell the shell Hey whats coming after this is a string not seperate files.



Next up, Level 3

This Level is a little more trickey, it introduced a somewhat new concept to me. Hidden files, when searching through directories sometimes using ls is not enough.

This level is a excellent introduction to that. For this level you need to enter the inhere directory and search for the file containing the password.

Upon entering the directory and listing out the contents you see nothing. Surprise! Because the point of this level is to teach you how to search for hidden files.

After seeing it turned up nothing I was confused for a second, then I remembered learning of the concept of hidden files. This reminded me one of the most important thing when searching directories in linux.

You can use parameters -a which list all files in a directory, -A which list almost all files in a directory and there are many more commands. With this I found the password quite easily.




Next up, Level 4

This level is where the challenge truly began for me at least. In this level your looking for the only human-readable file in the inhere directory

This level challenged me because at first I was confused because once you are in the correct directory and list out the contents.

What you should have is 9 files which I just went through manually for the answer. Let me say that is NOT the point of this level.

This level teaches you to use the type command, which displays the type of file you enter. Do it that way not the way I did it. My way is not entirely incorrect but it would consume more time in a real world scenario.




Lastly, Level 5

This level is more in depth than the first 4 levels. It teaches you how to use commands in depth. Not just putting commands alone like ls, cat, grep, etc. etc.

In this level you are required to search for a file with thse parameters "human-readable, 1033 bytes in size, not excuteable".

To find this you'll need to use a command to search for all these parameters specifically. I beileve the hardest part of this is the syntax and the correct to use the commands otherwise it is relatively simple.






Closing Statement -

So far I've truly enjoyed using overthewire, it has helped me brush on skills I had learned prior as well as learning new skills.

Each level brought a new topic that connected perfectly to the previous segement and brought new knowledge as well.

Overall I truly enjoyed these couple of levels and I intend to complete every level and do a right up every 5 levels.





