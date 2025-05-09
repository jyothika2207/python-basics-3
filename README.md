#program for basic operations by taking user input of an equation
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=int(input("enter the value of c:"))
x=int(input("enter the value of x:"))
result= a*(x**2)+b*x +c
print("the result of the equation is",result)


#swapping numbers (using temporary variable)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swapping",a,b)
temp=a
a=b
b=temp
print("after swapping ",a,b)
