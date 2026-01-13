# Basic-Python
# Ask user for their name
name = input("What is your name? ")

# Remove whitespace from str
name = name.strip()

# Capitalize user's name
name = name.title()

# Say hello to user
print("Hello, ",name)

# Ask the user for their name
name = input("What's your name?").strip().title()

# split user first and last name
first, last = name.split(" ")
# Say hello to user
print("Hello, ", first)
