## What is this?
If you are a wordle player, you'll know how dishartening it is to type your first word and having 5 grey tiles staring back at you.
Well, *this project was made to help find a ***optimal word**** for first few attempts. The word, which can give us as many clues in the form of yellows and greens.

## The approach
* Every attempt can only be a five letter word, there are six attempts in total. There are 26 alphabets in english, if we find two words without any character repeating in them, we can cover 10 distinct letters. This exhausts **≈38.5%** of all available characters
* There are only limited number of five letter words in english. I'm using a set of 657 words. So we are finding the frequency of occurence of each alphabet from the words present in this dataset. Then use this to find and rank all the letters based on probability of occurance.
* A bonus code in the last cell to find the overall probability score of any given word. This can be used for comparison of two or more words, useful while making decision
