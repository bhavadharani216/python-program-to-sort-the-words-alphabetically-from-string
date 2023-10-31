# python-program-to-sort-the-words-alphabetically-from-string

str=input("Enter a string:")
words = str.split()
words.sort()

print("The sorted words are:")
for word in words:
    print(word)
