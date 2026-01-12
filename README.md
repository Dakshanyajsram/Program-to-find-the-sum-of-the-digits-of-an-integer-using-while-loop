# Program-to-find-the-sum-of-the-digits-of-an-integer-using-while-loop

sum = 0
number = int(input("Enter an integer: "))
while(number!=0):
    digit = number%10
    sum = sum+digit
    number = number//10
print("Sum of digits is: ", sum)

OUTPUT:

Enter an integer: 2
Sum of digits is:  2
