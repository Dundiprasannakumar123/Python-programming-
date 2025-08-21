PROBLEM STATEMENT-1 
WRITE A PROGRAM TO PRINT GIVEN NUMBER IS EVEN OR ODD.
a=int(input())
if a%2==0:
    print("even")
else:
    print("odd") 


    
<img width="962" height="296" alt="image" src="https://github.com/user-attachments/assets/04a07cfb-108e-47e1-bbd6-239782fe12f5" />






PROBLEM STATMENT-2
WRITE A PROGRAM TO FIND THE NUMBER OF DIGITS IN A GIVEN NUMBER.
num=int(input())
count=0
i = num
while(i>0):
    count=count+1
    i=i//10
print(f"The number of digits in {num}:",count)




<img width="1915" height="402" alt="image" src="https://github.com/user-attachments/assets/cf3562a4-00ca-475f-a7b4-420e61a7f3ac" />



PROBLEM STATEMENT-3
WRITE A PROGRAM TO PRINT TABLES.

num = int(input()) 
for i in range(1, 11):      
   print (num, 'x', i, '=', num * i)




<img width="1918" height="830" alt="image" src="https://github.com/user-attachments/assets/d1d07f26-abea-440d-99da-5c3909ef6ac5" />


PROBLEM STATEMENT-4
WRITE A PROGRAM TO FIND FACTORIAL OF A NUMBER.

n=int(input())
f=1
for i in range(1, n + 1):
   f*=i
print(f)


<img width="1918" height="545" alt="image" src="https://github.com/user-attachments/assets/743fdfbd-db7b-4c3c-af13-8c4397e940a3" />



PROBLEM STATMENT-5
WRITE A PROGRAM TO SWAP TWO NUMBERS.

x=int(input())
y=int(input())
temp=x
x=y
y=temp
print('The value of x after swapping: {}'.format(x))
print('The value of y after swapping: {}'.format(y))


<img width="1907" height="510" alt="image" src="https://github.com/user-attachments/assets/a911b457-134a-4c97-b4a2-a7d7cf26123f" />





PROBLEM STATMENT-6

 Write a program to print given number is prime or not.
a=int(input())
c=0
for i in range(1,a):
    if a%i==0:
        c=c+1
if c>1:
    print("not prime")
else:
    print("prime")


<img width="1918" height="582" alt="image" src="https://github.com/user-attachments/assets/4ba22147-27f8-40ee-b3ae-3d52698be1ed" />



PROBLEM STATMENT-7
 Python program to check if year is a leap year or not.
year=int(input())
if(year % 400==0) and (year % 100==0):
    print("{0} is a leap year".format(year))
elif (year % 4 ==0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))



<img width="1917" height="748" alt="image" src="https://github.com/user-attachments/assets/10e781e7-2ba9-4ac3-ab6a-b43e71fb99e1" />


PROBLEM STATMENT-8
Python program to find the largest number among the three input numbers.
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
c = float(input("Enter third number: "))
if (a >= b) and (a >= c):
   largest = a
elif (b >= a) and (b >= c):
   largest = b
else:
   largest = c
print("The largest number is", largest)


<img width="1912" height="721" alt="image" src="https://github.com/user-attachments/assets/9323bad1-5921-4025-9408-27e9d5dde34e" />




PROBLEM STATMENT-9
Python program to display all the prime numbers within an interval.

l=int(input())
u=int(input())
for n in range(l,u+1):
   if n > 1:
       for i in range(2,n):
           if (n % i) == 0:
               break
       else:
           print(n)


<img width="1918" height="672" alt="image" src="https://github.com/user-attachments/assets/ac29617a-e6b5-47b6-9d2f-7268250890f0" />







