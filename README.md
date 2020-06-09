# HCL_Assignment

##### Question 1 - Design a binary tree and then write an algorithm to print the least(nearest) two common parent(if 2 parents exist otherwise 1  common parent) node between 2 nodes of a binary tree for given 2 key values which are present in binary tree.

class Node - For creating a new node
Methods - LCP, printFun1, printFun2

##### Question 2 - Design a system (Python/Java) and write the  code  which can download hundreds  of csv files and parse and put them in Database(You can choose mySQL or MongoDB etc). You have been given only one Machine with Linux ( with Multi-core CPU – 8 vCPU)  installed. File should be downloaded from remote server at some IP using SFTP.  And remote server allows maximum only one SFTP connection at a time from any remote machine(One IP only One SFTP  connection allowed).The format of data  in CSV File is given below. And like below there will be thousands of different files. Cell Id and Timestamp would be unique for each row.

Library used-
pysftp
glob
pandas
sqlalchemy - create_engine, types

##### Question 3 - Design a  binary tree and then print the breadth first order traversal of this tree. In breadth first order traversal, we visit the nodes of same height first then go to nodes of next height or level.

class NOde - For creating the new node of tree
Methods - BFO - for get the desired order and print it one by one

##### Question 4 - Encoding a string the below format to reduce the size of the string. A string of lowercase characters in range ascii[‘a’..’z’]. We want to reduce the string to its shortest length by doing a series of operations. In each operation we select a pair of adjacent lowercase letters that match, and delete them. For instance, the string aab could be shortened to b in one operation. Now we have to delete as many characters as possible using this method and print the resulting string. If the final string is empty, print Empty String

Method - MaxReducedString - for getting reduced length string.


Thank You!!!
