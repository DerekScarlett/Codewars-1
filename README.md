# Codewar 1

Question:
It's pretty straightforward. Your goal is to create a function that removes the first and last characters of a string. You're given one parameter, the original string. You don't have to worry with strings with less than two characters.

Solution:

function removeChar(str){
var first = str.slice(1,str.length-1)
return first;
};

So I have a function here called removeChar that has an argument (str). In my function a have a variable called first that is assigned a value str.slice(1,str.length). .slice() is a javascript method that extracts the text from one string and returns a new string. Using that method I take my argument str and do str.slice(). Now I only want the exclude my first and last characters and return a new string with only the middle ones, so I go str.slice(1,str.length-1). All this is doing is slicing my string starting from index 1 all the may to the second to last index in my string. Then I return first.

For example:

function removeChar(str){
var first = str.slice(1,str.length-1)
return first;
};
removeChar("string");// trin 
