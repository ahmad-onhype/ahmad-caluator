# ahmad-caluator
A simple command-line calculator built using Python.
# Ahmad Calculator
a=input("""
        which operation do you want :
        1: Add
        2:Subtract
        3:Multiply
        4:Divide
        enter your choice
""")
if a =="1":
    print("enter your values:")
    b=int(input("enter your first number:"))
    c=int(input("enter your second value:"))
    print(b+c)
elif a=="2":
    print("enter your values:")
    b1=int(input("enter you first value"))
    b2=int(input("enter your second value"))
    print(b1-b2)
elif a=="3":
    print("enter your values :")
    c1=int(input("enter your first value:"))
    c2=int(input("enter your second value"))
    print(c1*c2)
elif a=="4": 
    print("eneter your value:")
    d1=float(input("enetr your first value"))
    d2=float(input("enter your second value:"))
    print(d1/d2)
