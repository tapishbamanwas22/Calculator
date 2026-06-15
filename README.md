
print("Enter 2 number below:")
a=int(input("Enter number 1:"))
b=int(input("Enter number 2:"))
ch=0
while ch<5:
    print("Calculator Menu")
    print("1.Add")
    print("2.Substract")
    print("3.Multiply")
    print("4.Divide")
    print("5.Exit")

    #input choice
    ch = int(input("Enter Choice(1-5):"))

    if ch == 1:
        c=a+b
        print("Sum =",c)
    elif ch == 2:
        c=a-b
        print("Difference =",c)
    elif ch == 3:
        c=a*b
        print("Product =",c)
    elif ch == 4:
        c=a/b
        print("Quotient =",c)
    elif ch == 5:
        break
    else:
        print("Invalid Choice")
