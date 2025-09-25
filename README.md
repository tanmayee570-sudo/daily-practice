# daily-practice 
# program:1,2
# hello_world.py
print("Hello World")

# simple_math.py
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum:", a+b)
print("Difference:", a-b)
print("Product:", a*b)
print("Division:", a/b)

# palindrome_check.py
s = input("Enter string: ")
print("Palindrome?", s == s[::-1])

# sum_of_digits.py
num = int(input("Enter number: "))
print("Sum of digits:", sum(int(d) for d in str(num)))
