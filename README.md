# SumofCube


#Python Program for cube sum of first n natural numbers

n=int(input("Enter the Number:"))

def cube(n):
    total=0                               # Value of total after count 0,1,5,14,30
    for i in range(1,n+1):                # range value 0,1,2,3,4
        total=total+(i*i*i)               # 0,1,8,27,64
    return total

print(cube(n))
