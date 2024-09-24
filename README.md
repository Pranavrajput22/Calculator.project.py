# Calculator.project.py

print('''
+ add
- subtract
* multiply
/ divide''')
num1=int(input("enter a value1:="))
num2=int(input("enter a value2:="))
oprator=input("enter the opr..")

if oprator== "+":
    print(num1+num2)
elif oprator== "-":
    print(num1-num2)
elif oprator== "*":
    print(num1*num2)
elif oprator== "/":
    print(num1/num2)
else:
    print("invalid input")
    
