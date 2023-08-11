# NED_PGD_DS_Assignment2-Python-String-Formatting

**Assignment 1: String Concatenation and Formatting**

name = "Irtiqa Ur Rehman Khan"

age = 26

country = "Pakistan"

text = "My name is " + name + ", I am " + str(age) + " years old, and I live in " + country + "."

print(text)

**Assignment 2: String Formatting using `.format()`**

item = "laptop"

price = 999.99

quantity = 2

total_cost = price * quantity

text = "I bought {} {}(s) at {} each, for a total of ${:.2f}.".format(quantity, item, price, total_cost)

print(text)


item = "book"

price = 12.99

quantity = 5

total_cost = price * quantity

text = f"I bought {quantity} {item}(s) at {price} each, for a total of ${total_cost:.2f}."

print(text)


**Assignment 3: String Interpolation using `f''`**

city = "Karachi"

temperature = 32.2

print (f"The temperature in {city} is {temperature}°C.")



**Assignment 4: String Formatting using `%()`**

first_name = "Irtiqa"
last_name = "Khan"
birth_year = 1997
current_year = 2023
age = current_year - birth_year

text = "My name is %s %s and I am %d years old." % (first_name, last_name, age)
print(text)


first_name = "Irtiqa"
last_name = "Khan"
birth_year = 1997
current_year = 2023
age = current_year - birth_year

text = ("My name is %(first_name)s %(last_name)s and I am %(age)d years old.") %{"first_name": first_name, "last_name": last_name, "age": age}
print (text)

**Assignment 5: Combining Formatting Methods**

product = "Smartphone"

discount = 15

original_price = 500

discounted_price = original_price * (1 - discount / 100)

text = "The {} is originally priced at ${:.2f}. With a discount of {}%, the discounted price is ${:.2f}.".format(product, original_price, discount, discounted_price)

print(text)


product = "Laptop"

discount = 20

original_price = 150000

discounted_price = original_price * (1 - discount / 100)

descriptive_string = f"The {product} is originally priced at PKR{original_price:.2f}. With a discount of {discount}%, the discounted price is PKR{discounted_price:.2f}."

print(descriptive_string)
