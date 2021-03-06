# What are variables in Python?

*Variables are used to label and store data that can be referenced and manipulated by your code. You have already worked with variables in the code you've written so far. This lesson will dive deeper into variables. You'll learn the rules governing the naming of variables as well as some recommended industry conventions to follow.*


*I bet you already understand variables. Take a look at this basic math:*

```py
a = 1
b = 2
c = a + b
c = ?
```

*What is c? If you said c = 3 than your right.*

- a, b, and c are variables.

*Variables are just nicknames for things in your code. They are like boxes you can put things in and take them out of.*

*Create a file called **variables.py**:*

```py
# Variables are just nicknames
# there plain, lowercase words
# examples: x, y, banana, phone_a_quail

name = "Mattan Griffel"
orphan_fee = 200
teddy_bear_fee = 121.80

total = orphan_fee + teddy_bear_fee

print(name, "the total will be", total)
```

> Tip: Vs code will suggest variables for you to fill in, and if you hit Tab, it will auto-complete them. 

- When you run the file:

```bash
$ python variables.py
Mattan Griffel the total will be 321.08
```

## Variables in Python

- Must start with a lowercase letter.
- Can have letters, numbers, and underscores (but no spaces).
- Should use underscores (instead of spaces). E.g. your_name.

*When you define a variable, the variable name has to go on the left. This won't work:*

```py
"Mattan Griffel" = name
```
