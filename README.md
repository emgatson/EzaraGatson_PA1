Programing Assignment #1
# 1. ALPHABET SOUP PROBLEM - It creates a function that takes a string and returns a string with its letters in alphabetical order
    word = input("Enter a word: ") 
    sorted_word = "".join(sorted(word))
    print(f"Original word: {word}")
    print(f"Alphabetized word: {sorted_word}")

# 2. EMOTICON PROBLEM -  Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon
Smile :), Grin  :D, Sad :(, Mad >:(

    msg = input("Enter a sentence: ")
    emoji_map = {
        "smile": ":)",
        "grin": ":D",
        "sad": ":(",
        "mad": ">:("
    }
    for word, emoji in emoji_map.items():
        msg = msg.replace(word, emoji)
    print("Converted sentence:", msg)

# 3. UNPACKING LIST PROBLEM - It Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

    numbers = [1, 2, 3, 4, 5, 6]
    first, middle, last = numbers[0], numbers[1:-1], numbers[-1]
    print("First element:", first)
    print("Middle elements:", middle)
    print("Last element:", last)
