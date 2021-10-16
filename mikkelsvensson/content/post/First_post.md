---
title: "This is my first post"
date: 2021-10-16T20:19:47+02:00
---
This is the section for content. I'm just trying it out to see how it will look.

Under should be a Python code block. The code is a solution to chapter 5 exercise 2 in 'Python for everybody' by Dr. Charles R. Severance
```Python
max=None
min=None
while True:
   number = input("Enter a number: ")
   if number.upper() == "DONE":
      print(f'Max: {max} Min: {min}')
      break
   try:
      number=float(number)
   except(ValueError):
      print("Invalid input")
      continue
   if max is None or number > max:
      max = number
   elif min is None or number < min:
      min = number
```
