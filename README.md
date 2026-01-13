# Basic-Python
# Ask user for their name
name = input("What is your name? ")

# Remove whitespace from str
name = name.strip()

# Capitalize the user's name
name = name.title()

# Say hello to the user
print("Hello, ",name)

# Ask the user for their name
name = input("What's your name?").strip().title()

# split user first and last name
first, last = name.split(" ")
# Say hello to the user
print("Hello, ", first)
# def
def hello(to = "world"):
  print("hello,", to)

hello()
name = input("What's your name? ").strip().title()
hello(name)

#Return values
def greet(input):
  if "hello" in input:
    return "hello, there."
  else:
    return "I'm not sure what you mean?"

greeting = greet("how's going")
print("Hm", greeting)
