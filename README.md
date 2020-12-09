# Activation-Keys

You are about to make some good money, but first you need to think of a way to verify who paid for your product and who didn`t. You have decided to let people use the software for a free trial period and then require an activation key in order to continue to use the product. The last step before you could cash out is to design a program that creates unique activation keys for each user. So, waste no more time and start typing! 

 

The first line of the input will be your raw activation key. It will consist of letters and numbers only.  

After that, until the "Generate" command is given, you will be receiving strings with instructions for different operations that need to be performed upon the raw activation key. 

There are several types of instructions, split by ">>>": 

Contains>>>{substring} – checks if the raw activation key contains the given substring. 

If it does prints: "{raw activation key} contains {substring}". 

If not, prints: "Substring not found!" 

Flip>>>Upper/Lower>>>{startIndex}>>>{endIndex} 

Changes the substring between the given indices (the end index is exclusive) to upper or lower case.  

All given indexes will be valid. 

Prints the activation key. 

Slice>>>{startIndex}>>>{endIndex} 

Deletes the characters between the start and end indices (end index is exclusive). 

Both indices will be valid. 

Prints the activation key.
