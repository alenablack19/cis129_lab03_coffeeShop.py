# My coffee, Muffin, tea, and Donut Shop
num_coffees = 3
num_muffins = 3
num_teas = 2
num_donuts = 2

# My Coffee, Muffin, Tea, and Donut Shop Recipt
price_coffee = 5
price_muffin = 4
price_tea = 2
price_donut = 2
# Calculate subtotal
subtotal = (num_coffees * price_coffee) + (num_muffins * price_muffin) + (num_teas * price_tea) + (num_donuts * price_donut)
tax = round(subtotal * 0.06, 2)
total = subtotal + tax


# Display the receipt
print("My Coffee and Muffin Shop")
print("Number of coffees bought? ", num_coffees)
print("Number of muffins bought? ", num_muffins)
print("Number of teas bought? ", num_teas)
print("Number of donuts bought? ", num_donuts)
print("My Coffee and Muffin Shop Receipt")
print(f"{num_coffees} Coffee at ${price_coffee} each: ${num_coffees * price_coffee:.2f}")
print(f"{num_muffins} Muffins at ${price_muffin} each: ${num_muffins * price_muffin:.2f}")
print(f"{num_teas} Teas at ${price_tea} each: ${num_teas * price_tea:.2f}")
print(f"{num_donuts} Donuts at ${price_donut} each: ${num_donuts * price_donut:.2f}")
print(f"6% tax: ${tax:.2f}")
print(f"Total: ${total:.2f}")

Thank you for coming!
