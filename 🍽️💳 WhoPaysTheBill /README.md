# 🍽️💳 WhoPaysTheBill 
```python
import random
friends = ["Ishu", "Span", "Sai", "Charan", "Renu"]

#Option 1
bill_payer = random.choice(friends)
print(f"Bill is on {bill_payer}")

#Option 2
random_index = random.randint(0, len(friends)-1)
print(f"Bill is on {friends[random_index]}")
```
