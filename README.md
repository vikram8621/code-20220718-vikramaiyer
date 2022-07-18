# code-20220718-vikramaiyer
#Dont change the below code ↓
height = input("enter your height in m: ")
weight = input("enter your weight in kg: ")
gender = input("enter your gender in str:")
#Dont change the above code ↑

#BMI exponent calculation below this line ↓
bmi = int(weight) / float(height) ** 2
bmi_as_int = int(bmi)
print(bmi_as_int)

#BMI calculation as per brief
if bmi <= 18.4:
 print(f"Underweight, Malnutrition risk")
elif bmi >= 18.5 <= 24.9:
  print(f"Normal Weight, Low risk")
elif bmi >= 25 <= 29.9:
  print(f"Overweight, Enhanced risk")
elif bmi >= 30 <= 34.9:
  print(f"Moderately obese, Medium risk")
elif bmi >= 35 <= 39.9:
  print(f"Severely obese, High risk")
elif bmi >= 40:
  print(f"Very Severely obese, Very high risk")

  


## The above function shall calculate BMI and output on the basis given data in an un-organized format
## Require sometime to populate the values into tables as instructed
## As per data provided there are no overweight people
