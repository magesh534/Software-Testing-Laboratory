# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```
i.)do…while: 
  def display(): 
  start=input("Enter a positive value for START: ") 
  end=input("Enter a positive value for END: ") 
  if start.isnumeric() and end.isnumeric(): 
  while True: 
  start=int(start) 
  end=int(end) 
  print(start,end=‘ ‘) 
  if start<end: 
  start+=1 
  else: 
  break 
  Output: 
  else: 
  print("Enter a valid positive number.") display()
ii.) while…do 
  start=input("Enter a positive value for START: ") end=input("Enter 
  a positive value for END: ") 
  if start.isnumeric() and end.isnumeric(): 
  start=int(start) 
  end=int(end) 
  while start<end: 
  print(start) 
  start+=1 
  else: 
  print("Enter a valid positive number.")
iii.) switch 
  def switch(): 
  switcher={ 
  0:"even", 
  1:"odd" 
  } 
  n=input('Enter a value for N: ') try: 
  n=int(n) 
  print(switcher[n%2]) 
  except ValueError: 
  print("Enter a valid number.") 
  switch()
iv.) if else
  def compare(): 
  a=input("Enter a value for A: ") 
  b=input("Enter a value for B: ") 
  try: 
  a=int(a) 
  b=int(b) 
  if a>b: 
  print("A is greater than") 
  elif a<b: 
  print("B is greater than") 
  else: 
  print("A is equal to B") 
  except ValueError: 
  print(“Enter a valid number.”)
iv.) if else 
  def compare(): 
  a=input("Enter a value for A: ") 
  b=input("Enter a value for B: ") 
  try: 
  a=int(a) 
  b=int(b) 
  if a>b: 
  print("A is greater than") 
  elif a<b: 
  print("B is greater than") 
  else: 
  print("A is equal to B") 
  except ValueError: 
  print(“Enter a valid number.”)
```


### Output:
![Screenshot 2025-03-19 084300](https://github.com/user-attachments/assets/c5978be3-ee9f-447a-9b29-43dca195e722)
![Screenshot 2025-03-19 084533](https://github.com/user-attachments/assets/cca610d2-20dd-4e88-9fa1-4a1b2181c3d6)
![Screenshot 2025-03-19 084639](https://github.com/user-attachments/assets/ae833712-32a7-4853-be38-b5e9929f46da)
![Screenshot 2025-03-19 084740](https://github.com/user-attachments/assets/92b3e86d-4c9d-42cf-bdba-4575c165ceb0)
![Screenshot 2025-03-19 085031](https://github.com/user-attachments/assets/9e92a349-6274-4bcb-af8a-1099731b3b66)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


