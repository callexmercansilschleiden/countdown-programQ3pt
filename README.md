print("COUNTDOWN PROGRAM")

start = int(input("Enter starting number: "))

print("\nCountdown begins:")

def countdown(n):
    if n > 0:
        print(n)
        countdown(n - 1)

countdown(start)

print("Lift off!")

print("\nCountdown complete.")
print("Thank you for using this program.")
