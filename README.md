print('''1 - Add
2 - Subtract
3 - Multiply
4 - Divide''')
option = int(input("Choose an operation :"))

if (option in [1,2,3,4]) :
    num1 = int(input("Enter first number :"))
    num2 = int(input("Enter second number :"))
    if(option == 1):
        result = num1 + num2
    if(option == 2):
        result = num1 - num2 
    if(option == 3):
        result = num1 * num2
    if(option == 4):
        result = num1 / num2
else :
    print("Invalid operation entered.")

print("The result of the operation is : {}".format(result))
