# FibonacciNums
# python Program
nums = int(input("How many nums? "))
n1, n2 = 0, 1
count = 0

if nums <= 0:
   print("Please enter a positive integer")
elif nums == 1:
   print("Fibonacci sequence upto",nums,":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while count < nums:
       print(n1)
       n = n1 + n2
       
       n1 = n2
       n2 = n
       count +=1
