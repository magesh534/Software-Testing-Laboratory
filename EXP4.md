# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE: 16/04/2025                                                                           
### REGISTER NUMBER : 212222040092
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
x = input("Enter the input: ") 
if x.isnumeric(): 
 x = int(x) 
 temp = x 
 cube = 0; 
 while(temp>0): 
 digit = temp%10 
 cube = cube + (digit**3) 
 temp//=10 
 if(cube == x): 
 print("Armstrong Number") 
 else: 
 print("Not Armstrong Number") 
else: 
 print("Enter a Positive Integer.")
```


### Output:

![Screenshot 2025-04-16 085548](https://github.com/user-attachments/assets/2d59a8eb-a258-4cbc-b2e4-5ed897b2cb53)





### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


