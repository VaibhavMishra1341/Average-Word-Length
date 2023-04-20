# Average-Word-Length
 Big Data - MapReduce code for finding out the average word length of a text file in Hadoop system
 
 ## MapReduce 
 - It divides the input data into small chunks

 ## Map 
 - Input text file is divided into chunks, each with separate Map function. It reads the input data, extracts each word from the text

 ## Reduce
 - Receives all the values for a given key and calculates the average word length and returns key-value pair.

 ## Key
 - Value pairs are sorted and grouped by key and Reducer aggregates the value of each key.
 
 ## Output
 - List of key-value pairs, where each key represents a length of a word, and value is the average length of all the words of that length.

# Team Members
 - Atharv Deogaonkar
 - Gaytri
 - Ritika
 - Vaibhav Mishra
