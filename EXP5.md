## EX:5 BINARY SEARCH

# DATE:23/04/2025
# REGISTER NO:212222040081
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:

1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

```
def Palindrome(string): 
    for i in range(0, int(len(string)/2)): 
        if string[i] != string[len(string) - i - 1]: 
            return False 
    return True 

s = input("Enter a string: ") 
c = 1 

for i in s: 
    if not i.isalpha(): 
        c = 0 
        break  

if c == 0: 
    print("Enter a valid string") 
else: 
    answer = Palindrome(s) 
    if answer == True: 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome")




```





### Output:

![Screenshot 2025-04-23 083701](https://github.com/user-attachments/assets/44b04bf7-0eb1-4040-87c4-2e97bad4ba85)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

