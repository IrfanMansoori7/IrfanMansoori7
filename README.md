1. Hadoop MapReduce helps us count words in large text files by splitting the work into 

smaller parts. 

2. HDFS (Hadoop Distributed File System) stores our input files across multiple computers 

for faster processing. 

3. The Word Count program has two main parts - Mapper (splits and counts) and Reducer 

(combines counts). 

4. Mapper takes text input and breaks it into individual words, giving each word an initial 

count of 1. 

5. Reducer receives word counts from all mappers and adds them together to get total count 

for each word. 

6. Input files are stored in HDFS using commands like 'hdfs dfs -put' to upload local files. 

7. The program runs using a JAR file that contains our MapReduce code for word counting. 

8. Output is stored in HDFS and can be viewed using 'hdfs dfs -cat' command. 

9. The entire process happens automatically and in parallel across multiple machines. 

10. Final output shows each unique word and how many times it appears in the input text.
