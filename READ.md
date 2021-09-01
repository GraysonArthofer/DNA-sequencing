## Examining the Data
- I use the head function to examine the first 5 nucleic acid sequences
- Then I used a for loop to determine how many sequences were in the data set. There are 25,000 nucleic acid sequences. 
- Then I created a function that converts DNA into RNA
## Examining Quality Score of DNA
- I create a function that determines the quality score of a DNA sequence bases. This is on a scale from 0 to 1. The closer to 1 the higher likelihood that that the base is called correctly. 
- Then I created a new function that iterated through each DNA sequence and then returned the average quality score of that sequence. 
- After this I examine which sequence out of the 25,000 sequences has the lowest and highest quality scores. 
## Quality Score of each DNA Base
- I create a function that returns the average quality score of each DNA base. I also included the base "N" which is not a nitrogenous base. I believe N stands for a base that could not be read.
## N-gram frequency
- I create a function that determines the n-gram frequencies of a sequence. 
- Then I create a function which examines the correlation between 2 n-gram sequences.
## Looking for patterns
- After this I iterate through all 25,000 sequences to find which sequences most closely follows certain patters. 
