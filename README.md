# Day-2-Project-Tip-Calculator



print("Welcome to the Tip calculator.")

bill = float(input("What was the total bill ? $"))

tip = float(input("What percentage tip would you like to give? 10, 12, or 15 ?"))

people = int(input("How many people to split the bill?"))
pay = float(( bill / people ) * ( 1 +  tip / 100 ))
pay = round(pay, 2)
print(f"Each person should pay {pay}")
