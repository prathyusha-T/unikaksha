#Amoeba Multiplication
n=int(input("Enter the number of Months :\n"))
a=-1
b=1
for i in range(1,n+1):
    c=a+b
    a=b
    b=c
print("The amoeba size is %d"%c)


#Factorial
n=int(input())
temp=n
sum=0
for i in range(1,n):
    if n%i==0:
        sum=sum+i
if sum==temp:
    print("yes")
else:
    print("no")
        
       
#Sum of Digits
n=int(input())
sum=0
while n!=0:
    rem=n%10
    sum=sum+rem
    n=n//10
print(sum)


#Friendly Pair
n1=int(input())
n2=int(input())
sum1=0
sum2=0
for i in range(1,n1+1):
    if n1%i==0:
        sum1=sum1+i
for i in range(1,n2+1):
    if n2%i==0:
        sum2=sum2+i
if sum1/n1==sum2/n2:
    print("friendly pair")
else:
    print("not  friendly pair")
    
    
#Reverse a Number
n=int(input())
rev=0
while n!=0:
    rem=n%10
    rev=rev*10+rem
    n=n//10
print(rev)


#Strong Number
num=int(input("Enter a number:")) 
sum=0  
temp=num  
while(num):  
    i=1  
    fact=1  
    rem=num%10  
    while(i<=rem):  
        fact=fact*i   
        i=i+1  
    sum=sum+fact  
    num=num//10  
if(sum==temp):  
    print("Given number is a strong number")  
else:  
    print("Given number is not a strong number")  


#Sum of natural Numbers
n=int(input())
sum=0
for i in range(1,n+1,1):
    sum=sum+i
print(sum)
    

#Sum of Numbers in a range
a=int(input())
b=int(input())
sum=0
for i in range(a,b+1):
    sum=sum+i
print(sum)
    
    
#Harshard Number
n=int(input())
sum=0
temp=n
while n!=0:
    rem=n%10
    sum=sum+rem
    n=n//10
if temp%sum==0:
    print("Harshad Number")
else:
    print("Not  Harshad Number")
    
    
#LCM of two numbers
num = int(input())
numb = int(input())
if(num > numb ):  
    max= num
else:
    max= numb
while(True):
    if(max % num == 0 and max % numb == 0):   
        print("LCM of %d"%num,"and %d"%numb,"is %d"%max)
        break
    max=max+1
        
       
#Palindrome of a number
n=int(input())
rev=0
temp=n
while n!=0:
    rem=n%10
    rev=rev*10+rem
    n=n//10
if rev==temp:
    print("palindrome")
else:
    print("not a palindrome")
    
    
#Perfect Number
n=int(input())
sum=0
temp=n
for i in range(1,n):
    if n%i==0:
        sum=sum+i
if sum==temp:
    print("perfect number")
else:
    print("not a perfect number")
    
    
#Prime Numbers in a Range
a=int(input())
b=int(input())
for j in range(a,b+1):
    count=0
    for i in range(2,j//2+1):
        if j%i==0:
            count=count+1
    if count==0 and j!=1:
        print(j,end=' ')
