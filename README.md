# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```
num = input("Enter a number: ")  
flag = 0  

if num.isnumeric():  
    z = int(num)  

    if z == 2:  
        flag = 1  
    elif z > 2:  
        for i in range(2, z // 2 + 1):  # Loop should include z//2
            if z % i == 0:  
                flag = 0  
                break  
        else:  
            flag = 1  

    if flag == 1:  
        print("Prime Number")  
    else:  
        print("Not a Prime Number")  

else:  
    print("Enter a Positive Number")
```
## Output

![image](https://github.com/user-attachments/assets/0531d3c8-885b-46bb-8de9-4e3bfb6d8050)

![image](https://github.com/user-attachments/assets/76480681-b3e2-4a6c-8418-0db2dd4537b1)

![image](https://github.com/user-attachments/assets/5bc360dc-f453-4ed8-845e-09de189e283a)

![image](https://github.com/user-attachments/assets/b99f555e-af96-453d-be20-9e691f120e3b)

![image](https://github.com/user-attachments/assets/2f93744a-b1cf-4320-8e19-50aaeb14d221)

![image](https://github.com/user-attachments/assets/10a0de27-9705-425c-a4ae-d4c34a3be8bb)

## Result
Thus, the python program to check the number is prime or not is implemented and the output is 
verified successfully.

