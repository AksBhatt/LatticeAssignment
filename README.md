# LatticeAssignment
Assignment for Lattice

I have attached the zip folder for the assignment to this repository.

Questions:

read from alice_in_wonderland.txt, make sure you read from 1-1000.txt and ignore the banned words from this .txt file, then output it in a certain manner in the increasing order of their occurances, pass an integer value as an argument and get the top n values from the list.

Approach:

1)Using readAllBytes fetch the content from both the files.
2)Push them into string arrays and loop over them to check for banned words and ignore them
3)I have used a HashMap to store the words and their simultaneous occurances.
4)Then using Java 8 streams and comparators I have made sure that the output is in the form of increasing order of the values.
5)Then get the top n values from integer passed as the param.

