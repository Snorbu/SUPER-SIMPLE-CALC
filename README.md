# SUPER-SIMPLE-CALC

while True:
    N1 = int(input("Enter first number (or 0 to quit): "))
    N2 = int(input("Enter second number: "))
    syntax = input("Choose +, -, *, /  (or q to quit): ")

    if syntax == "q" or N1 == 0:
        print("Goodbye!")
        break

    if syntax == "+":
        print("Result:", N1 + N2)
    elif syntax == "-":
        print("Result:", N1 - N2)
    elif syntax == "*":
        print("Result:", N1 * N2)
    elif syntax == "/":
        print("Result:", N1 / N2)
    else:
        print("Wrong symbol, try again.")

