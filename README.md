# Guessing-Game-Challenge

import random

# Step 1: Pick a random number
number = random.randint(1, 100)

# Step 2: Print an introduction and rules
print("Welcome to the Guessing Game!") print("I have picked a number between 1 and 100.") print("Rules:") print("- If your guess is out of range, I'll say 'OUT OF BOUNDS'") print("- On your first guess:") print(" * Within 10 of the number → 'WARM!'") print(" * More than 10 away → 'COLD!'") print("- On later guesses:") print(" * Closer than last guess → 'WARMER!'") print(" * Farther than last guess → 'COLDER!'") print("- Guess the number in as few tries as possible!\n")

Step 3: List to store guesses (0 as placeholder)
