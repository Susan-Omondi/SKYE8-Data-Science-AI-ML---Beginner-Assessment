# SKYE8-Data-Science-AI-ML---Beginner-Assessment
This repository contains my solutions  for Data Science assessment test to evaluate my basic knowledge.
- It contains a function to calculate the mean of a list of numbers.
- A function to load a CSV file and return a Pandas DataFrame
- 
- # My approach
- (The mean calculation)- Here the goal is to calculate the mean of a list of numbers.
- I created a list containing numbers only and used else if 'None'. This would mean that if my list doesn't contain numbers only numbers, then my function will check if it is empty.
- If it's numbers only (like in my example), it will print the mean. If it's empty, then it will print 'None'.
- To test this, I changed my number 1 to be 'one' and it threw me an error. This is because my code went through my list and didn't find numbers, only making the 'else if' to be 'False'
- I found this approach to be simple because it follows the mathematical definition of a mean.
