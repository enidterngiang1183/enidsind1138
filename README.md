# =====================================
# Simple Python Project
# Author: Sinclair
# =====================================

def greet():
    print("Hello! Welcome to my Python project")

def ask_user():
    name = input("What is your name? ")
    age = input("How old are you? ")
    
    print("\nNice to meet you,", name)
    print("You are", age, "years old.")

def main():
    greet()
    ask_user()

# Program start
if __name__ == "__main__":
    main()
