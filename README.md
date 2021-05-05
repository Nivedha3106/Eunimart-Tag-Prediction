# Eunimart-Tag-Prediction
<br>
#Problem Statement :<br>
Data Field Explanation:<br>
Id - Unique identifier for each question<br>
Title - The question’s title<br>
Body - The body of the question<br>
Tags - The tags associated with the question in a space-separated format<br>
<br>
Example Data point<br>
Id : 1<br>
Title​: How to print Hello World in C language?<br>
Body ​:<br>
#include<stdio.h><br>
Int main()<br>
{<br>
printf(“Hello World”);<br>
Return 0;<br>
}<br>
Tags ​: CTask - 1 : Data Preprocessing<br>
➢ Remove Duplicate entries<br>
➢ Separate out code-snippets from Body<br>
➢ Remove stop words (Except 'C')<br>
➢ Remove HTML Tags<br>
➢ Convert all the characters into small letters<br>
➢ Use SnowballStemmer to stem the words<br>
<br>
Task - 2 : Analysis of Tags<br>
➢ Total number of unique tags<br>
➢ Maximum number of tags per question<br>
➢ Minimum number of tags per question<br>
➢ Avg. number of tags per question<br>
➢ Most Frequent Tags<br>
<br>
Task - 3 : Apply suitable model<br>
➢ Split the data into test and train(80:20)<br>
<br>
#CSV<br>
 https://bit.ly/2w8eUdX <br>
 Extract the zip file and use it
