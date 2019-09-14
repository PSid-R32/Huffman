# huffman

The purpose of this project was to take an input file 
with a sentence of characters. We were to then find the 
frequencies of each character. With that information, we 
were able to insert the character/frequency pair into a 
priority queue. Then, we combined the two smallest 
frequencies and inserted the new combined node into the 
huffman tree. The process was repeated until we get one 
root node. Afterwards, we assign all of the left children 
0's, and the right children 1's. By doing so, we are able 
to go ahead and traverse the tree and get a huffman code 
table for the characters. The ones with a higher frequency 
had smaller bit values assigned to them and vise versa for 
lower frequencies. Taking the input file and using the 
huffamn code table, we are able to create a bit stream. 
The bit string was then separated and converted to base6, 
and therefore we create an encoded version of the sample 
text. The process was then repeated for decoding the data. 
