Programing Assignment #1
# 1. ALPHABET SOUP PROBLEM - Creates a function that takes a string and returns a string with its letters in alphabetical order
    word = input("Enter a word: ")  // Get input from user
    sorted_word = "".join(sorted(word)) // Convert the word to a sort character list using string
    print(f"Original word: {word}") // Displays original word
    print(f"Alphabetized word: {sorted_word}") // Displays alphabetized word

# 2. EMOTICON PROBLEM -  Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon
Smile :), Grin  :D, Sad :(, Mad >:(

    msg = input("Enter a sentence: ") // Get input from user
    emoji_map = {
        "smile": ":)", // Mapping emotions to their emojis
        "grin": ":D",
        "sad": ":(",
        "mad": ">:("
    }
    for word, emoji in emoji_map.items(): // Replace emotion words to their emojis
        msg = msg.replace(word, emoji)
    print("Converted sentence:", msg) // Displays the converted sentence

# 3. UNPACKING LIST PROBLEM - Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

    numbers = [1, 2, 3, 4, 5, 6] // Input list of numbers
    first, middle, last = numbers[0], numbers[1:-1], numbers[-1] // Extracting first to last elements
    print("First element:", first) // Displays first element
    print("Middle elements:", middle) // Displays second element
    print("Last element:", last) // Displays the last element
