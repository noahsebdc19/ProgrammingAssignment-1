# Programming Assignment 1
In this assignment, we will learn the fundamental codes and functions used in Python programming. The goal is not just to understand how these codes work, but to put them into practice. We'll use them to create simple Python programs, which will give us a hands-on experience and a deeper understanding. 


# 1. Alphabet Soup Problem

The task is to create a function that takes a string as input and returns a new string with letters arranged alphabetically. 
This code sorts the letters of each word alphabetically and outputs the rearranged version. 
It's like taking a word, scrambling its letters, and then neatly organizing them from A to Z.

# Ask the user to enter a word
word = input("Enter a word: ")

# Sort the letters alphabetically and join them back into a string
sorted_word = ''.join(sorted(word))

# Print the result
print("Alphabetical Order:", sorted_word)


# 2. Emoticon Problem

 The task is to create a function that replaces specific words with emoticons. 
 Given a sentence as a string, the function should replace the phrase "smile," "grin," "sad," and "mad" with their corresponding emoticons. 
 This code processes sentences expressing different emotions and substitutes these words with emoji-like symbols, adding a fun twist 
 to their expressiveness. In summary, it transforms feelings into emojis, making the process engaging and enjoyable.

# Ask the user to type a sentence
sentence = input("Enter a sentence: ")

# Replace certain words with emojis
sentence = sentence.replace("happy", ":)")
sentence = sentence.replace("insane", ":D")
sentence = sentence.replace("sad", ":(")
sentence = sentence.replace("angry", ">:(")

# Print the updated sentence
print("Emoji version:", sentence)


# 3. Unpacking List Problem

 The task at hand is not just a theoretical exercise, but a practical demonstration of how to unpack a list into three variables: 
 `first`, `middle`, and `last`. The `middle` variable represents all the elements found between the first and last elements of the list. 
 The program demonstrates how to extract specific list parts in Python using indexing and slicing. 
 This method allows to easily identify and display the first element, the middle group of elements, and the last element, 
 effectively illustrating how lists can be divided into smaller parts.

# Create a list of numbers from 1 to 6 and store it in variable Ist
Ist = [1, 2, 3, 4, 5, 6]     

# Take the very first element (index 0 → number 1) and store it in 'first'
first = Ist[0]               

# Slice the list from index 1 up to index 4 → [2, 3, 4, 5]
middle = Ist[1:5]             

# Take the element at index 5 (the last number → 6) and store it in 'last'
last = Ist[5]      

# Print: first:  1
print("first: ", first)       

# Print: middle:  [2, 3, 4, 5]
print("middle: ", middle)    

# Print: last:  6
print("last: ", last)         
