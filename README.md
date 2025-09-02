# task-1.c
Create a python program to enter three numbers and then performs and displays the results of the following Logical operations: and, or, not.
#Taking three numbers as inputs
a=int(input("Enter the First number:"))
b=int(input("Enter the Second number:"))
c=int(input("Enter the Third number:"))

#Performing logical operations
print("\nLogical Operations Results:")
print((a>b) and (b>c))
print((a>b) or (b>c))
print(not(a>b))
print(not(b>c))
