# CodeAlpha_FIBONACCI_GENERATOR
''' Code Alpha  Internship  Task 1'''
'''The Fibonacci series is a sequence where each number is
the sum of the two preceding numbers, defined by a
mathematical recurrence relationship.'''
def  fibo(n):
    if n==1:
        return 0
    elif n==2:
        return  1
    else:
        return (fibo(n-1)+fibo(n-2))
    
a= int (input("enter the terms of fibonacci series "))
print("fibonacci  series is :")
for i in range (1,a+1):
    print(fibo(i),end=" ")
