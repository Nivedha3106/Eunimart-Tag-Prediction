# Eunimart-Tag-Prediction
<br>
#Problem Statement :<br>
Data Field Explanation:
Id - Unique identifier for each question
Title - The question’s title
Body - The body of the question
Tags - The tags associated with the question in a space-separated format
Example Data point
Id : 1
Title​: How to print Hello World in C language?
Body ​:
#include<stdio.h>
Int main()
{
printf(“Hello World”);
Return 0;
}
Tags ​: CTask - 1 : Data Preprocessing
➢ Remove Duplicate entries
➢ Separate out code-snippets from Body
➢ Remove stop words (Except 'C')
➢ Remove HTML Tags
➢ Convert all the characters into small letters
➢ Use SnowballStemmer to stem the words
Task - 2 : Analysis of Tags
➢ Total number of unique tags
➢ Maximum number of tags per question
➢ Minimum number of tags per question
➢ Avg. number of tags per question
➢ Most Frequent Tags
Task - 3 : Apply suitable model
➢ Split the data into test and train(80:20)

#CSV
 https://bit.ly/2w8eUdX 
 Extract the zip file and use it
