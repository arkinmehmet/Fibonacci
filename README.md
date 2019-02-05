This program will help you, how to finding Fibonacci sequence. Limit-Path Number (n) has to provided by user. 

(If you want you can take input by user side using line 4 besides line 7.)
n = int(input("How many terms? "))

You can change that value below, to find other results.
n = 6      

n1 = 0
n2 = 1
count = 0

if n <= 0:
   print("Please enter a positive integer")
   
elif n == 1:
   print("Fibonacci sequence upto",n,":")
   print(n1)
   
else:
   print("Fibonacci sequence upto",n,":")
   
   while count < n:
       print(n1,end=' , ')
       nth = n1 + n2
       n1 = n2
       n2 = nth
       count += 1
