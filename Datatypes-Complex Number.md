## CONDITIONAL STATEMENTS-To evaluate body mass of a person to determine his weight status using if statement.

## 🎯 Aim :
To calculate the Body Mass Index (BMI) of a person and determine their weight status (Underweight, Normal weight, Overweight, or Obese) based on the calculated BMI.


## 🧠 Algorithm :
1.Input: Read the height (in meters) and weight (in kilograms) from the user.

2.Calculate BMI: Use the formula BMI = weight / (height * height) to calculate the BMI.

3.Determine Weight Status:

*  If BMI < 18.5, the status is Underweight.
  
*  If 18.5 <= BMI < 25, the status is Normal weight.
  
* If 25 <= BMI < 30, the status is Overweight.
  
* If BMI >= 30, the status is Obese.

4.Output: Print the height, weight, calculated BMI, and the corresponding weight status.


## 💻 Program :
```.py
height=float(input())
weight=int(input())
BMi=weight/(height*height) 
print(f"Your Height and Weight are {height} and {weight}")
if(BMi<18.5):
    print(f"your BMI {BMi:.2f} indicates you are Under weight")
if(18.5<=BMi<25):
    print(f"your BMI {BMi:.2f} indicates you are Normal weight")
if(25<=BMi<30):
    print(f"your BMI {BMi:.2f} indicates you are Over weight")
if(30<=BMi):
    print(f"your BMI {BMi:.2f} indicates you are Obese")
```


## Output :
![image](https://github.com/user-attachments/assets/ce68c03c-dc3f-4fea-85ae-f6abd80a4e5e)


## Result :
The program calculates the BMI of the person as 25.02.

Based on this value, the program classifies the person as Over weight according to the BMI ranges.
