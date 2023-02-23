# Python-project- Code to convert weight btw lbs and kg
weight= int(input("what is your weight? "))
unit= input("What is the unit value, kg or lbs? ")
if unit == "kg":
  weight_lbs = weight * 2.2
  print ("Your weight in lbs is:", round(weight_lbs), "lbs")
elif unit == "lbs":
  weight_kg = weight / 2.2
  print ("Your weight in kg is:", round(weight_kg), "kg")
else:
  print("invalid entry")
