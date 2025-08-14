def greet_user(name):
    """Prints a personalized greeting message."""
    print(f"Hello, {name}! Welcome to our program.")

if __name__ == "__main__":
    user_name = input("Enter your name: ")
    greet_user(user_name)
