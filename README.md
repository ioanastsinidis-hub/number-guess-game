[Python17.py](https://github.com/user-attachments/files/29142916/Python17.py)
🎯 Number Guessing Game

A simple Python game where the player tries to guess a randomly generated number between 0 and 100.

The game provides hints after each guess, telling the player whether the secret number is higher or lower. Keep guessing until you find the correct number and see how many attempts it took!

✨ Features
Random number generation
Numbers range from 0 to 100
Helpful "Too High" and "Too Low" hints
Tracks the number of attempts
Beginner-friendly Python project
Fun way to practice logical thinking
📝 Example
Guess a number between 0 and 100: 50
Too low!

Guess a number between 0 and 100: 75
Too high!

Guess a number between 0 and 100: 63
Congratulations! You guessed the number in 3 attempts.
🚀 What You'll Learn
Using Python's random module
Working with loops and conditions
Handling user input
Creating interactive console applications
Basic game development concepts
🎮 Challenge Yourself

Try to guess the number in as few attempts as possible. The optimal strategy is to use a binary search approach, which can find any number from 0 to 100 in at most 7 guesses!

"The best way to predict the future is to create it." — Peter Drucker<img width="138" height="142" alt="Screenshot 2026-06-08 172402" src="https://github.com/user-attachments
code:
import random
count=random.randint(1,100)
#print(count)
for i in range(5):
    guess=int(input("mantepse"))
    if guess>count:
        print("kateva")
    elif guess<count:
        print("aneva")
    elif guess==count:
        print("bravo")
if guess==count:
    print("to vrikes")
else:
    print("den to vrikes")





/assets/c912e2b6-b92b-4865-a5d9-c54a99a2e0a2" />
