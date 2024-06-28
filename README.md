# WORD-COUNTER-USING-PYTHON
# INTRODUCTION

Data preprocessing is an important task in text classification. With the emergence of Python in the field of data science, it is essential to have certain shorthands to have the upper hand among others. This article discusses ways to count words in a sentence, it starts with space-separated words but also includes ways to in presence of special characters as well.

# FEW METHODS ARE

# Method #1: Using split() split function is quite useful and usually quite generic method to get words out of the list, but this approach fails once we introduce special characters in the list. 

# Method #2 : Using regex(findall()) Regular expressions have to be used in case we require to handle the cases of punctuation marks or special characters in the string. This is the most elegant way in which this task can be performed. 

# Method #3 : Using sum() + strip() + split() This method performs this particular task without using regex. In this method we first check all the words consisting of all the alphabets, if so they are added to sum and then returned. 

# Method #4: Using count() method

# Method #5 : Using the shlex module:

The shlex module provides a lexical analyzer for simple shell-like syntaxes. It can be used to split a string into a list of words while taking into account quotes, escapes, and other special characters. This makes it a good choice for counting words in a sentence that may contain such characters.

Note: The shlex.split function returns a list of words, so you can use the len function to count the number of words in the list. The count method can also be used on the list to achieve the same result.


# Method #6: Using operator.countOf() method

The time complexity of this approach is O(n), where n is the length of the input string. 
The Auxiliary space is also O(n), as the shlex.split function creates a new list of words from the input string. This approach is efficient for small to medium-sized inputs, but may not be suitable for very large inputs due to the use of additional memory.


# Method #7:Using reduce()

**Initialize a variable res to 1 to account for the first word in the string.

**For each character ch in the string, do the following:
a. If ch is a space, increment res by 1.


**Return the value of res as the result.


The time complexity of the algorithm for counting the number of words in a string using the count method or reduce function is O(n), where n is the length of the string. This is because we iterate over each character in the string once to count the number of spaces.

The auxiliary space of the algorithm is O(1), since we only need to store a few variables (res and ch) at any given time during the execution of the algorithm. The space required is independent of the length of the input string.


# Time complexity: O(n)

The time complexity of the ‘char.count()’ method is O(n), where n is the length of the input string. The addition operation takes constant time. Therefore, the time complexity of the code is O(n).


# Auxiliary Space: O(1)

The space complexity of the code is constant, as we are not using any additional data structures or variables that are dependent on the input size. Therefore, the space complexity of the code is O(1).


# FEATURES


# User Input: Prompt the user to enter a sentence or paragraph.

# Word Counting Logic: Implement a function that counts the number of words in the input.

# Output Display: Print the word count to the console.

# Error Handling: Account for potential errors, such as empty input.

# Code Comments: Add comments to explain the purpose of different parts of your code.

# User-Friendly Interface: Ensure a clear and user-friendly interface for input and output.




# IMAGES OF CODE




![NN](https://github.com/vishnuyadav78/WORD-COUNTER-USING-PYTHON/assets/173454005/5027ab1f-fa1f-4ea6-ba65-bccceff30268)









