# PYTHON-DJANGO-FLASK-LABS-IFEANYI
by Ifeanyi Omeata

## Python

<details>
  <summary>Python Basics</summary>

  ### 1. Print String

  ```py
  print("Hello World!")
  print("Python is easy!")

  if __name__ == '__main__':
      print('Completed!')
  ```

  ```
  Hello World!
  Python is easy!
  Completed!
  ```

  ### 2. Use Comments

  ```py
  """This is a multi-line comment
  Author: Ifeanyi omeata
  Date: 2025
  """
  
  # This is a sample Python script.
  print("Hello World!")
  print("Python is easy!")
  
  # Press the green button in the gutter to run the script.
  if __name__ == '__main__':
      print('Completed!')
  ```

  ```
  Hello World!
  Python is easy!
  Completed!
  ```

</details>

<details>
  <summary>Python Datatypes</summary>

  ### 1. NoneType
  - [ ] NoneType: an object that does not contain any value
  
  ```py
  #NoneType
  a = None
  print(a)
  print(type(a))
  ```

  ```
  None
  <class 'NoneType'>
  ```

  ### 2. Numeric-Integer

  ```py
  #Numeric-Integer
  a1 = 11
  b1 = 100
  c1 = -66
  print(a1,b1,c1)
  ```

  ```
  11 100 -66
  ```

  ### 3. Numeric-Floating Point (float)

  ```py
  #Numeric-Floating Point (float)
  a2 = 33.5
  b2 = -25.8
  print(a2,b2)
  ```

  ```
  33.5 -25.8
  ```

  ### 4. Numeric-Complex

  ```py
  #Numeric-Complex
  a3 = 3+5j
  print(a3)
  print(type(a3))
  ```

  ```
  (3+5j)
  <class 'complex'>
  ```

  ### 5. Numeric-Binary

  ```py
  #Numeric-Binary
  a4=0B1010
  print(a4)
  print(type(a4))
  ```

  ```
  10
  <class 'int'>
  ```

  ### 6. Numeric-Hexadecimal

  ```py
  #Numeric-Hexadecimal
  a5=0XFF
  print(a5)
  print(type(a5))
  ```

  ```
  255
  <class 'int'>
  ```

  ### 7. Boolean

  ```py
  #Boolean
  a6 = True
  b6 = False
  print(a6,b6)
  print(9>8)
  print(type(a6))
  ```

  ```
  True False
  True
  <class 'bool'>
  ```

</details>

<details>
  <summary>Type Conversion</summary>

  ### 1. Floating Point to Integer

  ```py
  #Floating Point to Integer
  a1=33.5
  b1=int(a1)
  print(b1)
  print(type(b1))
  ```

  ```
  33
  <class 'int'>
  ```

  ### 2. String to Floating Point

  ```py
  #String to Floating Point
  a2="22.5"
  b2=float(a2)
  print(b2)
  print(type(b2))
  ```

  ```
  22.5
  <class 'float'>
  ```

  ### 3. Integer to Binary

  ```py
  #Integer to Binary
  a3=10
  b3=bin(a3)
  print(b3)
  print(type(b3))
  ```

  ```
  0b1010
  <class 'str'>
  ```

</details>

<details>
  <summary>Python Strings</summary>

  ### 1. String Basics

  ```py
  s1="You are a good person"
  print(s1)
  
  s2="""
  You are a great person
  You are a nice person
  """
  print(s2)
  ```

  ```
  You are a good person

  You are a great person
  You are a nice person
  ```

  ### 2. String Membership

  ```py
  s1="You are a good person"
  print(s1)

  #membership
  print("good" in s1)
  print("bad" in s1)
  ```

  ```
  You are a good person

  True
  False
  ```

  ### 3. String Length

  ```py
  s1="You are a good person"
  print(s1)
  
  #length
  print(len(s1))
  ```

  ```
  You are a good person

  21
  ```

  ### 4. String Concatenation

  ```py
  #concatenation
  s3="I love"
  s4="Python"
  s5=s3+s4
  print(s5)
  ```

  ```
  I lovePython
  ```

  ### 5. String Repetition

  ```py
  #repetition
  s6="Hello"
  s7=s6*3
  print(s7)
  ```

  ```
  HelloHelloHello
  ```

  ### 6. String Slicing

  ```py
  s1="You are a good person"

  #slicing
  print(s1[0])
  print(s1[0:])
  print(s1[:7])
  print(s1[0:6])
  print(s1[0:7:2])
  print(s1[-3:-1])
  print(s1[15::-1])
  print(s1[::-1])
  ```

  ```
  Y
  You are a good person
  You are
  You ar
  Yuae
  so
  p doog a era uoY
  nosrep doog a era uoY
  ```

  ### 7. String Strip

  ```py
  #string strip
  s2="   You are a good person   "
  print(s2.strip())
  print(s2.lstrip())
  print(s2.rstrip())
  ```

  ```
  You are a good person
  You are a good person   
     You are a good person
  ```

  ### 8. String Replace

  ```py
  #string replace
  s3="You are a good person"
  print(s3.replace("good","tall"))
  ```

  ```
  You are a tall person
  ```

  ### 9. String Split

  ```py
  #string split
  s4="You are a good person"
  print(s4.split())
  ```

  ```
  ['You', 'are', 'a', 'good', 'person']
  ```

  ### 10. String Join

  ```py
  #string join
  s5="You are a good person"
  print(" ".join(s5))
  ```

  ```
  Y o u   a r e   a   g o o d   p e r s o n
  ```

  ### 11. String Format

  ```py
  #string format
  s6="You are a good person"
  print(f"Hey! {s6}")
  ```

  ```
  Hey! You are a good person
  ```

  ### 12. String Count

  ```py
  #string count
  s7="You are a good person"
  print(s7.count("a"))
  ```

  ```
  2
  ```

  ### 13. String Find

  ```py
  #string find
  s8="You are a good person"
  print(s8.find("good"))
  print(s8.find("good", 2, 14))
  print(s8.find("good", 2, 10))
  ```

  ```
  10
  10
  -1
  ```

  ### 14. String Index

  ```py
  #string index
  s9="You are a good person"
  print(s9.index("good"))
  ```

  ```
  10
  ```

  ### 15. String Isalnum

  ```py
  #string isalnum
  s10="person123"
  print(s10.isalnum())
  ```

  ```
  True
  ```

  ### 16. String Isalpha

  ```py
  #string isalpha
  s11="person"
  print(s11.isalpha())
  ```

  ```
  True
  ```

  ### 17. String Isdigit

  ```py
  #string isdigit
  s12="123"
  print(s12.isdigit())
  ```

  ```
  True
  ```

  ### 18. String Islower

  ```py
  #string islower
  s13="person"
  print(s13.islower())
  ```

  ```
  True
  ```

  ### 19. String Isupper

  ```py
  #string isupper
  s14="PERSON"
  print(s14.isupper())
  ```

  ```
  True
  ```

  ### 20. String Isspace

  ```py
  #string isspace
  s15="  "
  print(s15.isspace())
  ```

  ```
  True
  ```

  ### 21. String Istitle

  ```py
  #string istitle
  s16="Person"
  print(s16.istitle())
  ```

  ```
  True
  ```

</details>



<details>
  <summary>Python Lists</summary>

  ### 1. List Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 2. List Length

  ```py
  # List length
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(len(my_list))
  ```

  ```
  5
  ```

  ### 3. List Index

  ```py
  # List index
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list[0], my_list[2])
  ```

  ```
  10 Ifeanyi
  ```

  ### 4. List Slicing

  ```py
  # List slicing
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list[2:5])
  ```

  ```
  ['Ifeanyi', -10, 30.5]
  ```

  ### 5. List Multiplication

  ```py
  # List multiplication
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list * 2)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5, 10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 6. List Extend

  ```py
  # List extend
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.extend([1, 2, 3])
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5, 1, 2, 3]
  ```

  ### 7. List Append

  ```py
  # List append
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.append("James")
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5, 'James']
  ```

  ### 8. List Insert

  ```py
  # List insert
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.insert(0, 99)
  print(my_list)
  ```

  ```
  [99, 10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 9. List Remove

  ```py
  # List remove
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.remove(30.5)
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10]
  ```

  ### 10. List Pop

  ```py
  # List pop
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.pop()
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10]
  ```

  ### 11. List Clear

  ```py
  # List clear
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.clear()
  print(my_list)
  ```

  ```
  []
  ```

  ### 12. List Sort

  ```py
  # List sort
  my_list = ["10", "20", "Ifeanyi", "-10", "30.5"]
  my_list.sort()
  print(my_list)
  ```

  ```
  ['-10', '10', '20', '30.5', 'Ifeanyi']
  ```

  ### 13. List Reverse-Sort

  ```py
  # List reverse-sort
  my_list = ["10", "20", "Ifeanyi", "-10", "30.5"]
  my_list.sort(reverse=True)
  print(my_list)
  ```

  ```
  ['Ifeanyi', '30.5', '20', '10', '-10']
  ```

  ### 14. List Reverse

  ```py
  # List reverse
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_list.reverse()
  print(my_list)
  ```

  ```
  [30.5, -10, 'Ifeanyi', 20, 10]
  ```

  ### 15. List Copy

  ```py
  # List copy
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_new_list = my_list.copy()
  print(my_new_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 16. List Max and min

  ```py
  # List Max and min
  my_list = [10, 20, -10, 30.5]
  print(max(my_list), min(my_list))
  ```

  ```
  30.5 -10
  ```

  ### 17. List to Tuple

  ```py
  # List to Tuple
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_tuple = tuple(my_list)
  print(my_tuple)
  ```

  ```
  (10, 20, 'Ifeanyi', -10, 30.5)
  ```

  ### 18. Tuple to List

  ```py
  # Tuple to List
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  my_list = list(my_tuple)
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 19. List to String

  ```py
  # List to String
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_string = ", ".join(str(item) for item in my_list)
  print(my_string)
  ```

  ```
  10, 20, Ifeanyi, -10, 30.5
  ```

  ### 20. String to List

  ```py
  # String to List
  my_string = "10, 20, Ifeanyi, -10, 30.5"
  my_list = my_string.split(", ")
  print(my_list)
  ```

  ```
  ['10', '20', 'Ifeanyi', '-10', '30.5']
  ```

  ### 21. List to Dictionary

  ```py
  # List to Dictionary
  my_list = [("a", 10), ("b", 20), ("c", 30)]
  my_dict = dict(my_list)
  print(my_dict)

  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_dict = {item: index for index, item in enumerate(my_list)}
  print(my_dict)
  ```

  ```
  {'a': 10, 'b': 20, 'c': 30}
  {10: 0, 20: 1, 'Ifeanyi': 2, -10: 3, 30.5: 4}
  ```

  ### 22. Dictionary to List

  ```py
  # Dictionary to List
  my_dict = {"a": 10, "b": 20, "c": 30}
  my_list = list(my_dict.items())
  print(my_list)
  
  my_dict = {"a": 10, "b": 20, "c": 30}
  my_list = list(my_dict.values())
  print(my_list)
  
  my_dict = {"a": 10, "b": 20, "c": 30}
  my_list = list(my_dict.keys())
  print(my_list)
  ```

  ```
  [('a', 10), ('b', 20), ('c', 30)]
  [10, 20, 30]
  ['a', 'b', 'c']
  ```

  ### 23. List to Set

  ```py
  # List to Set
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_set = set(my_list)
  print(my_set)
  ```

  ```
  {10, 'Ifeanyi', 20, -10, 30.5}
  ```

  ### 24. Set to List

  ```py
  # Set to List
  my_set = {10, 20, "Ifeanyi", -10, 30.5}
  my_list = list(my_set)
  print(my_list)
  ```

  ```
  [20, 'Ifeanyi', -10, 10, 30.5]
  ```

</details>

<details>
  <summary>Python Tuple</summary>

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 1. Tuple Basics

  ```py
  # List basics
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

</details>















