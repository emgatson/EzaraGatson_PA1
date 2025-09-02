Programing Assignment #1
# 1. ALPHABET SOUP PROBLEM - In this problem it creates a function that takes a string and returns a string with its letters in alphabetical order
word = input("Enter a word: ")
sorted_word = "".join(sorted(word))
print(f"Original word: {word}")
print(f"Alphabetized word: {sorted_word}")
