# Get the number of coffees and muffins from the user
num_coffees = int(input("Number of coffees bought? "))
num_muffins = int(input("Number of muffins bought? "))

# Prices of coffee and muffin
coffee_price = 5
muffin_price = 4

# Calculate subtotal, tax, and total
subtotal = (num_coffees * coffee_price) + (num_muffins * muffin_price)
tax = round(subtotal * 0.06, 2)
total = subtotal + tax

# Display the receipt
print("My Coffee and Muffin Shop")
print("Number of coffees bought?")
print(num_coffees)
print("Number of muffins bought?")
print(num_muffins)
print("My Coffee and Muffin Shop Receipt")
print(f"{num_coffees} Coffee at ${coffee_price} each: ${num_coffees * coffee_price:.2f}")
print(f"{num_muffins} Muffins at ${muffin_price} each: ${num_muffins * muffin_price:.2f}")
print(f"6% tax: ${tax:.2f}")
print(f"Total: ${total:.2f}")
Thank you for coming!
