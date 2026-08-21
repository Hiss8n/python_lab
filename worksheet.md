

def square(n):
    return n*n

def is_even(n):
    if(n%2==0):
        return True
    return False
def celsius_to_fahrenheit(c):
    F=(c*float(9/5)+32)
    return F

    
    from utils import square,is_even,celsius_to_fahrenheit




print("Enter number:.....")

number=float(input())

print("There square of the number is:",square(number))


#HOW PYTHON IMPORT CONNECTS TO main.py and utils.py file.

Using the file import,python use the syntax

`from <src> import <function_name>,etc`


