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

