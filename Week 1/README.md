import random

letters = "abcdefghijklmnopqrstuvwxyz"
input_letter = random.choice(letters)
print(input_letter)

if input_letter in 'aioeu':
    output= "vowle"
elif input_letter=="y":
    output= "it depends"
else:
    output = "consonant"
print(output)
