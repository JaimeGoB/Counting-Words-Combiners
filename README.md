# Counting-Words-Combiners

Using Hadoop framework. I will implement a word counting program using combiners. Combiners primary job is to minimize the key value pairs that will be shuffled across network between mappers and reducers. The combiner will aggregate results locally for an individual mapper. Thus, making it faster to count the numbers of words in a file.

Attached is a description of combiner.

![test1](https://github.com/JaimeGoB/Counting-Words-Combiners/blob/master/WordCount/bin/data/combiners.png)
Here is the output of reading an entire history book:
![test1](https://github.com/JaimeGoB/Counting-Words-Combiners/blob/master/WordCount/bin/data/output.png)


