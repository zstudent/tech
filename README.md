
## Videos

https://drive.google.com/open?id=0B29M3sfdctitS3F1MEt0YkhFbm8

## Home work tasks

### Stack class quiz:

Home task:

1.	Write a program that reads in a sequence of characters and prints them in reverse order.  Use a stack.

2.	Write a program that reads in a sequence of characters, and determines whether its parentheses, braces, and curly braces are "balanced."  Hint: for left delimiters, push onto stack; for right delimiters, pop from stack and check whether popped element matches right delimiter.

### Queue class quiz:

Home task:

1.	Implement min() and max() methods

2.	Implement a queue with two stacks

### Recursion:

Home task:

1.	Write a recursive Python function that has a parameter representing a list of integers and returns the maximum stored in the list. Thinking recursively, the maximum is either the first value in the list or the maximum of the rest of the list, whichever is larger. If the list only has 1 integer, then its maximum is this single value, naturally.

2.	We can determine how many digits a positive integer has by repeatedly dividing by 10 (without keeping the remainder) until the number is less than 10, consisting of only 1 digit. We add 1 to this value for each time we divided by 10. Here is the recursive algorithm: 

a.	If n < 10 return 1.

b.	Otherwise, return 1 + the number of digits in n/10 (ignoring the fractional part).
Implement this recursive algorithm in Python and test it using a main function that calls this with the values 15, 105, and 15105. (HINT: Remember that if n is an integer, n/10 will be an integer without the fractional part.)
