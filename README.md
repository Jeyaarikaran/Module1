## Data types-python program to read two numbers and convert and print them into a complex number
## Aim:
The aim of the program is to read two input numbers (representing the real and imaginary parts) from the user, convert them into a complex number, and print the complex number. Additionally,
the program will print the imaginary part of the complex number.
## Algorithm:
1.Read two numbers from the user (these will be the real and imaginary parts of the complex number).
2.Create a complex number using the complex() function or the format real_part + imaginary_part * j.
3.Print the complex number.
4.Extract and print the imaginary part of the complex number using the .imag attribute.
## Program:
```.py
a=int(input())
b=int(input())
print(complex(a,b))
print(float(b))
```
## Output:
![image](https://github.com/user-attachments/assets/3c8765a5-fee5-4ad0-9c74-7ff00e670303)

## Result :
The program prints the complex number (5+6j).
The program extracts and prints the imaginary part, which is 6.0.
