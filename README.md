# Game-A-Thon:Introduction to Git and Github

# Name : Rushikesh Pattewar

# Problem Statement 1 :  Sum of natural numbers up to num

TestCase: input:16 , output:136

num = 16

if num < 0:
   print("Enter a positive number")
else:
   sum = 0
   #use while loop to iterate until zero
   while(num > 0):
       sum += num
       num -= 1
   print("The sum is", sum)

# Problem statement 2 : Write program to find the largest number among the three input numbers
TestCase: input 10,14,12 , output:14
num1 = 10
num2 = 14
num3 = 12

if (num1 >= num2) and (num1 >= num3):
   largest = num1
elif (num2 >= num1) and (num2 >= num3):
   largest = num2
else:
   largest = num3

print("The largest number is", largest)

