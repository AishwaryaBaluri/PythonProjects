# 💰Tip Calculator
```python
print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("How much tip would you like to give? 10, 12, or 15?"))
people = int(input("How many people to split the bill"))

#calculating the total tip with the bill
bill_with_tip = tip/100 * bill + bill

#total amount to be paid by each person
total = round(bill_with_tip/people, 2)

print(f"Each person should pay: ${total}")
```
