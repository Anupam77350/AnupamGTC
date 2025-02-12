# AnupamGTC
import random

def generate_random_number():
    return random.randint(1, 100)

def greet_user(name):
    print(f"Hello, {name}!")

if __name__ == "__main__":
    user_name = input("Enter your name: ")
    greet_user(user_name)
    print(f"Your random number is: {generate_random_number()}")
