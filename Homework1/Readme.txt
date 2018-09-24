README:

author: Jessica May
date: 9/05/2018


How to run:
	cd into the respective cipher folder. Type "make" and the program will run. The output of the cipher decoded will be in a file called "Decoded_Cipher.txt".


How I got the key for Cipher text 1:
	
	I first looked at any letters that were by themselves, as I knew those would have to be "i" or "a". I found "g" and "h" by themselves, so I substituted the corresponding letters in. I then used frequency anaylsis to see the most common letters in the cipher text and replace them with their respective most common in the English language. After printing it out, with decoded letters being capitalized and encrypted letters being lower case, it was easy to see some patterns. The first word looked like 'TNEmE'. I can see that that looks like "there" so then I substitued "r" for "m" and fixed what was writing "N" to write "H", and continued to do this with the whole text.

How I found the key for Cipher text 2:

I found an online resource that showed me the steps of finding the key for a Vignere cipher. Using the Index of Coincidence, I discovered the key is 5 characters long. I then removed all punctuation and spaces from the text and split it up by chunk. This was to help me see the freqeuncy of each individual letter in the key. I used that to start decrypthing the chunks. If "v" in chunk 4 had the highest frequency out of all, I assigned it "E" and see if that made sense and found the difference and used that number for the subtraction.
