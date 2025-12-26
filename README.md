# Python-program
items = input("Input comma separated sequence of words: ")
words = [word for word in items.split(",")]
print(",".join(sorted(list(set(words)))))

output:
Input comma separated sequence of words: red,white,pink,blue
blue,pink,red,white
