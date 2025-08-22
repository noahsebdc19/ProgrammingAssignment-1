# ProgrammingAssignment-1
In this assignment, we will learn the fundamental codes and functions used in Python programming. The goal is not just to understand how these codes work, but to put them into practice. We'll use them to create simple Python programs, which will give us a hands-on experience and a deeper understanding. 


# 1. Alphabet Soup Problem
# The task is to create a function that takes a string as input and returns a new string with letters arranged alphabetically. 
# This code sorts the letters of each word alphabetically and outputs the rearranged version. 
# It's like taking a word, scrambling its letters, and then neatly organizing them from A to Z.

s = "hello"              # Store the word "hello" in variable s
n = ''.join(sorted(s))   # Sort the letters of "hello" alphabetically and join into "ehllo"

k = "noah"               # Store the word "noah" in variable k
l = ''.join(sorted(k))   # Sort the letters of "noah" alphabetically and join into "ahno"

print(n)                 # Print "ehllo"
print(l)                 # Print "ahno"


# 2. Emoticon Problem
# The task is to create a function that replaces specific words with emoticons. 
# Given a sentence as a string, the function should replace the phrase "smile," "grin," "sad," and "mad" with their corresponding emoticons. 
# This code processes sentences expressing different emotions and substitutes these words with emoji-like symbols, adding a fun twist 
# to their expressiveness. In summary, it transforms feelings into emojis, making the process engaging and enjoyable.

s = 'I am happy!'                                   # Store the sentence "I am happy!" in variable s
k = s.replace("happy", ":)")                        # Replace the word "happy" with ":)" → "I am :)"

u = 'You make me go insane!'                        # Store the sentence "You make me go insane!" in variable u
a = u.replace("insane", ":D")                       # Replace the word "insane" with ":D" → "You make me go :D"

n = "I'm really feeling sad these days."            # Store the sentence with "sad" in variable n
p = n.replace("sad", ":(")                          # Replace "sad" with ":(" → "I'm really feeling :( these days."

y = "I was angry with myself for making such a mistake."  # Store the sentence with "angry" in variable y
m = y.replace("angry", ">:(")                       # Replace "angry" with ">:(" → "I was >:( with myself for making such a mistake."

print(k)                                            # Print "I am :)"
print(a)                                            # Print "You make me go :D"
print(p)                                            # Print "I'm really feeling :( these days."
print(m)                                            # Print "I was >:( with myself for making such a mistake."


# 3. Unpacking List Problem
# The task at hand is not just a theoretical exercise, but a practical demonstration of how to unpack a list into three variables: 
# `first`, `middle`, and `last`. The `middle` variable represents all the elements found between the first and last elements of the list. 
# The program demonstrates how to extract specific list parts in Python using indexing and slicing. 
# This method allows to easily identify and display the first element, the middle group of elements, and the last element, 
# effectively illustrating how lists can be divided into smaller parts.

Ist = [1, 2, 3, 4, 5, 6]     # Create a list of numbers from 1 to 6 and store it in variable Ist
first = Ist[0]               # Take the very first element (index 0 → number 1) and store it in 'first'
middle = Ist[1:5]             # Slice the list from index 1 up to index 4 → [2, 3, 4, 5]
last = Ist[5]                 # Take the element at index 5 (the last number → 6) and store it in 'last'

print("first: ", first)       # Print: first:  1
print("middle: ", middle)     # Print: middle:  [2, 3, 4, 5]
print("last: ", last)         # Print: last:  6
