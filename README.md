print("COUNTDOWN PROGRAM")  # Program title

start = int(input("Enter starting number: "))  # Ask user for starting number

print("\nCountdown begins:")  # Tell user countdown will start

def countdown(n):  # Function that counts down
    if n > 0:  # Check if number is greater than zero
        print(n)  # Print the current number
        countdown(n - 1)  # Call function again with smaller number

countdown(start)  # Call the function to start countdown

print("Lift off!")  # Message after countdown ends

print("\nCountdown complete.")  # Countdown finished
print("Thank you for using this program.")  # Goodbye message
