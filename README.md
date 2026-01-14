print("COUNTDOWN PROGRAM")  # Displays the program title

start = int(input("Enter starting number: "))  # Gets the starting number from the user

print("\nCountdown begins:")  # Prints a message before the countdown starts

def countdown(n):  # Defines a function named countdown
    if n > 0:  # Checks if n is greater than 0
        print(n)  # Prints the current value of n
        countdown(n - 1)  # Calls the function again with n decreased by 1

countdown(start)  # Starts the countdown using the user's input

print("Lift off!")  # Prints message after countdown finishes

print("\nCountdown complete.")  # Indicates the countdown is complete
print("Thank you for using this program.")  # Final message to the user
