n = input("Enter your weight system (lbs or kgs): ").lower()
n1 = float(input("Enter your weight: "))

if n == "lbs":
    n_kg = n1 * 0.453592
elif n == "kgs":
    n_kg = n1
else:
    print("Invalid weight system! Please enter 'lbs' or 'kgs'.")
    exit()

height = input("Enter your height system (meter or feet): ").lower()
h = float(input("Enter your height: "))

if height == "feet":
    h_meter = h * 0.3048
elif height == "meter":
    h_meter = h
else:
    print("Invalid height system! Please enter 'meter' or 'feet'.")
    exit()

bmi = n_kg / (h_meter ** 2)

print("Your BMI is:", round(bmi, 2))
print("Category:",
      "underweight" if bmi < 18.5 else
      "normal" if bmi <= 24.9 else
      "overweight" if bmi <= 29.9 else
      "obese")
