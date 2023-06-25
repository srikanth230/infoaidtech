import random

def play_game():
    print("Welcome to the Number Guessing Game!")
    print("I'm thinking of a number between 1 and 100.")
    print("You have 10 attempts to guess the number.")

    secret_number = random.randint(1, 100)

    attempts = 0
    while attempts < 10:
        attempts += 1
        guess = int(input("Enter your guess: "))

        if guess < secret_number:
            print("Too low!")
        elif guess > secret_number:
            print("Too high!")
        else:
            print(f"Congratulations! You guessed the number in {attempts} attempts.")
            break

    if attempts == 10:
        print(f"Game over! The number was {secret_number}.")

    play_again = input("Do you want to play again? (yes/no): ")
    if play_again.lower() == "yes":
        play_game()
    else:
        print("Thank you for playing!")

play_game()
