# PYTHON-LABS-IFEANYI
by Ifeanyi Omeata

<details>
  <summary>Python Basics</summary>

  - [ ] 1. Print String
  - [ ] 2. Use Comments

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

  - [ ] 1. NoneType
  - [ ] 2. Numeric-Integer
  - [ ] 3. Numeric-Floating Point (float)
  - [ ] 4. Numeric-Complex
  - [ ] 5. Numeric-Binary
  - [ ] 6. Numeric-Hexadecimal
  - [ ] 7. Boolean

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

  - [ ] 1. Floating Point to Integer
  - [ ] 2. String to Floating Point
  - [ ] 3. Integer to Binary

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

  - [ ] 1. String Basics
  - [ ] 2. String Membership
  - [ ] 3. String Length
  - [ ] 4. String Concatenation
  - [ ] 5. String Repetition
  - [ ] 6. String Slicing
  - [ ] 7. String Strip
  - [ ] 8. String Replace
  - [ ] 9. String Split
  - [ ] 10. String Join
  - [ ] 11. String Format
  - [ ] 12. String Count
  - [ ] 13. String Find
  - [ ] 14. String Index
  - [ ] 15. String Isalnum
  - [ ] 16. String Isalpha
  - [ ] 17. String Isdigit
  - [ ] 18. String Islower
  - [ ] 19. String Isupper
  - [ ] 20. String Isspace
  - [ ] 21. String Istitle
  - [ ] 22. String to Number
  - [ ] 23. Number to String

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

  ### 22. String to Number

  ```py
  # String to Number
  my_string = "1011101"
  my_number = int(my_string)
  print(my_number, type(my_number))
  ```

  ```
  1011101 <class 'int'>
  ```

  ### 23. Number to String

  ```py
  # Number to String
  my_number = 1011101
  my_string = str(my_number)
  print(my_string, type(my_string))
  ```

  ```
  1011101 <class 'str'>
  ```
  
</details>



<details>
  <summary>Python Lists</summary>

  - [ ] 1. List Basics
  - [ ] 2. List Length
  - [ ] 3. List Index
  - [ ] 4. List Slicing
  - [ ] 5. List Multiplication
  - [ ] 6. List Extend
  - [ ] 7. List Append
  - [ ] 8. List Insert
  - [ ] 9. List Remove
  - [ ] 10. List Pop
  - [ ] 11. List Clear
  - [ ] 12. List Sort
  - [ ] 13. List Reverse-Sort
  - [ ] 14. List Reverse
  - [ ] 15. List Copy
  - [ ] 16. List Max and min
  - [ ] 17. List to Tuple
  - [ ] 18. Tuple to List
  - [ ] 19. List to String
  - [ ] 20. String to List
  - [ ] 21. List to Dictionary
  - [ ] 22. Dictionary to List
  - [ ] 23. List to Set
  - [ ] 24. Set to List

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

  - [ ] 1. Tuple Basics
  - [ ] 2. Tuple Count
  - [ ] 3. Tuple Length
  - [ ] 4. Tuple Index
  - [ ] 5. Tuple Max & Min
  - [ ] 6. Tuple Sum
  - [ ] 7. Tuple Sorted
  - [ ] 8. Tuple Reversed
  - [ ] 9. Tuple Slicing
  - [ ] 10. Tuple Membership
  - [ ] 11. Tuple Unpacking
  - [ ] 12. Tuple to List
  - [ ] 13. List to Tuple
  - [ ] 14. Tuple to String
  - [ ] 15. String to Tuple
  - [ ] 16. Tuple to Dictionary
  - [ ] 17. Dictionary to Tuple
  - [ ] 18. Tuple to Set
  - [ ] 19. Set to Tuple

  ### 1. Tuple Basics

  ```py
  # Tuple basics
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  print(my_tuple)
  ```

  ```
  (10, 20, 'Ifeanyi', -10, 30.5)
  ```

  ### 2. Tuple Count

  ```py
  # Tuple Count
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5, 10, 20)
  print(my_tuple.count(10))
  ```

  ```
  2
  ```

  ### 3. Tuple Length

  ```py
  # Tuple Length
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5, 10, 20)
  print(len(my_tuple))
  ```

  ```
  7
  ```

  ### 4. Tuple Index

  ```py
  # Tuple Index
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5, 10, 20)
  print(my_tuple.index(20))
  ```

  ```
  1
  ```

  ### 5. Tuple Max & Min

  ```py
  # Tuple Max & Min
  my_tuple = (10, 20, -10, 30.5, 10, 20)
  print(max(my_tuple), min(my_tuple))
  ```

  ```
  30.5 -10
  ```

  ### 6. Tuple Sum

  ```py
  # Tuple Sum
  my_tuple = (10, 20, -10, 30.5, 10, 20)
  print(sum(my_tuple))
  ```

  ```
  80.5
  ```

  ### 7. Tuple Sorted

  ```py
  # Tuple Sorted
  my_tuple = (10, 20, -10, 30.5, 10, 20)
  print(sorted(my_tuple))
  print(tuple(sorted(my_tuple)))
  print(sorted(my_tuple, reverse=True))
  print(tuple(sorted(my_tuple, reverse=True)))
  ```

  ```
  [-10, 10, 10, 20, 20, 30.5]
  (-10, 10, 10, 20, 20, 30.5)
  [30.5, 20, 20, 10, 10, -10]
  (30.5, 20, 20, 10, 10, -10)
  ```

  ### 8. Tuple Reversed

  ```py
  # Tuple Reversed
  my_tuple = (10, 20, -10, 30.5, 10, 20)
  print(reversed(my_tuple))
  print(tuple(reversed(my_tuple)))
  ```

  ```
  <reversed object at 0x00000169C2BFD060>
  (20, 10, 30.5, -10, 20, 10)
  ```

  ### 9. Tuple Slicing

  ```py
  # Tuple Slicing
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5, 10, 20)
  print(my_tuple[0:3])
  ```

  ```
  (10, 20, 'Ifeanyi')
  ```

  ### 10. Tuple Membership

  ```py
  # Tuple Membership
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5, 10, 20)
  print(10 in my_tuple)
  ```

  ```
  True
  ```

  ### 11. Tuple Unpacking

  ```py
  # Tuple Unpacking
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  a, b, c, d, e = my_tuple
  print(a, b, c, d, e)
  ```

  ```
  10 20 Ifeanyi -10 30.5
  ```

  ### 12. Tuple to List

  ```py
  # Tuple to List
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  my_list = list(my_tuple)
  print(my_list)
  ```

  ```
  [10, 20, 'Ifeanyi', -10, 30.5]
  ```

  ### 13. List to Tuple

  ```py
  # List to Tuple
  my_list = [10, 20, "Ifeanyi", -10, 30.5]
  my_tuple = tuple(my_list)
  print(my_tuple)
  ```

  ```
  (10, 20, 'Ifeanyi', -10, 30.5)
  ```

  ### 14. Tuple to String

  ```py
  # Tuple to String
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  my_string = ", ".join(str(item) for item in my_tuple)
  print(my_string)
  ```

  ```
  10, 20, Ifeanyi, -10, 30.5
  ```

  ### 15. String to Tuple

  ```py
  # String to Tuple
  my_string = "10, 20, Ifeanyi, -10, 30.5"
  my_tuple = tuple(my_string.split(", "))
  print(my_tuple)
  ```

  ```
  ('10', '20', 'Ifeanyi', '-10', '30.5')
  ```

  ### 16. Tuple to Dictionary

  ```py
  # Tuple to Dictionary
  my_tuple = (("a", 10), ("b", 20), ("c", 30))
  my_dict = dict(my_tuple)
  print(my_dict)
  ```

  ```
  {'a': 10, 'b': 20, 'c': 30}
  ```

  ### 17. Dictionary to Tuple

  ```py
  # Dictionary to Tuple
  my_dict = {"a": 10, "b": 20, "c": 30}
  my_tuple = tuple(my_dict.items())
  print(my_tuple)
  ```

  ```
  (('a', 10), ('b', 20), ('c', 30))
  ```

  ### 18. Tuple to Set

  ```py
  # Tuple to Set
  my_tuple = (10, 20, "Ifeanyi", -10, 30.5)
  my_set = set(my_tuple)
  print(my_set)
  ```

  ```
  {10, 20, 'Ifeanyi', -10, 30.5}
  ```

  ### 19. Set to Tuple

  ```py
  # Set to Tuple
  my_set = {10, 20, "Ifeanyi", -10, 30.5}
  my_tuple = tuple(my_set)
  print(my_tuple)
  ```

  ```
  (20, 'Ifeanyi', -10, 10, 30.5)
  ```

</details>


<details>
  <summary>Python Set</summary>

  - [ ] 1. Set Basics
  - [ ] 2. Set Add
  - [ ] 3. Set Remove
  - [ ] 4. Set Pop
  - [ ] 5. Set Clear
  - [ ] 6. Set Length
  - [ ] 7. Set Update
  - [ ] 8. Set Union
  - [ ] 9. Set Intersection
  - [ ] 10. Set Difference
  - [ ] 11. Set Symmetric Difference
  - [ ] 12. Set Subset
  - [ ] 13. Set Superset
  - [ ] 14. Set to Frozen Set
  - [ ] 15. Frozen Set to Set

  ### 1. Set Basics

  ```py
  # Set Basics
  my_set = {1, 2, 3, 4, 5}
  print(my_set)
  ```

  ```
  {1, 2, 3, 4, 5}
  ```

  ### 2. Set Add

  ```py
  # Set Add
  my_set = {1, 2, 3, 4, 5}
  my_set.add(6)
  print(my_set)
  ```

  ```
  {1, 2, 3, 4, 5, 6}
  ```

  ### 3. Set Remove

  ```py
  # Set Remove
  my_set = {1, 2, 3, 4, 5}
  my_set.remove(2)
  print(my_set)
  ```

  ```
  {1, 3, 4, 5}
  ```

  ### 4. Set Pop

  ```py
  # Set Pop
  my_set = {1, 2, 3, 4, 5}
  my_set.pop()
  print(my_set)
  ```

  ```
  {2, 3, 4, 5}
  ```

  ### 5. Set Clear

  ```py
  # Set Clear
  my_set = {1, 2, 3, 4, 5}
  my_set.clear()
  print(my_set)
  ```

  ```
  set()
  ```

  ### 6. Set Length

  ```py
  # Set Length
  my_set = {1, 2, 3, 4, 5}
  print(len(my_set))
  ```

  ```
  5
  ```

  ### 7. Set Update

  ```py
  # Set Update
  my_set = {1, 2, 3, 4, 5}
  my_set.update([4, 5, 6, 7, 8, 9, 10])
  print(my_set)
  ```

  ```
  {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
  ```

  ### 8. Set Union

  ```py
  # Set Union
  my_set = {1, 2, 3, 4, 5}
  my_set2 = {4, 5, 6, 7, 8, 9, 10}
  print(my_set.union(my_set2))
  ```

  ```
  {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
  ```

  ### 9. Set Intersection

  ```py
  # Set Intersection
  my_set = {1, 2, 3, 4, 5}
  my_set2 = {4, 5, 6, 7, 8, 9, 10}
  print(my_set.intersection(my_set2))
  ```

  ```
  {4, 5}
  ```

  ### 10. Set Difference

  ```py
  # Set Difference
  my_set = {1, 2, 3, 4, 5}
  my_set2 = {4, 5, 6, 7, 8, 9, 10}
  print(my_set.difference(my_set2))
  ```

  ```
  {1, 2, 3}
  ```

  ### 11. Set Symmetric Difference

  ```py
  # Set Symmetric Difference
  my_set = {1, 2, 3, 4, 5}
  my_set2 = {4, 5, 6, 7, 8, 9, 10}
  print(my_set.symmetric_difference(my_set2))
  ```

  ```
  {1, 2, 3, 6, 7, 8, 9, 10}
  ```

  ### 12. Set Subset

  ```py
  # Set Subset
  my_set = {1, 2, 3, 4, 5}
  my_set2 = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
  print(my_set.issubset(my_set2))
  ```

  ```
  True
  ```

  ### 13. Set Superset

  ```py
  # Set Superset
  my_set = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
  my_set2 = {1, 2, 3, 4, 5}
  print(my_set.issuperset(my_set2))
  ```

  ```
  True
  ```

  ### 14. Set to Frozen Set

  ```py
  # Set to Frozen Set
  my_set = {1, 2, 3, 4, 5}
  my_frozen_set = frozenset(my_set)
  print(my_frozen_set, type(my_frozen_set))
  ```

  ```
  frozenset({1, 2, 3, 4, 5}) <class 'frozenset'>
  ```

  ### 15. Frozen Set to Set

  ```py
  # Frozen Set to Set
  my_frozen_set = frozenset({1, 2, 3, 4, 5})
  my_set = set(my_frozen_set)
  print(my_set, type(my_set))
  ```

  ```
  {1, 2, 3, 4, 5} <class 'set'>
  ```


</details>


<details>
  <summary>Python Range</summary>

  - [ ] 1. Range Basics
  - [ ] 2. Range with start, stop
  - [ ] 3. Range with start, stop, step
  - [ ] 4. Range Length
  - [ ] 5. Range to List
  - [ ] 6. Range to Tuple
  - [ ] 7. Range to Set
  - [ ] 8. Range to Dictionary

  ### 1. Range Basics

  ```py
  # Range Basics
  my_range = range(5)
  for i in my_range:
      print(i)
  ```

  ```
  0
  1
  2
  3
  4
  ```

  ### 2. Range with start, stop

  ```py
  # Range with start, stop
  my_range = range(1, 10)
  for i in my_range:
      print(i)
  ```

  ```
  1
  2
  3
  4
  5
  6
  7
  8
  9
  ```

  ### 3. Range with start, stop, step

  ```py
  # Range with start, stop, step
  my_range = range(1, 10, 2)
  for i in my_range:
      print(i)
  ```

  ```
  1
  3
  5
  7
  9
  ```

  ### 4. Range Length

  ```py
  # Range Length
  my_range = range(5)
  print(len(my_range))
  ```

  ```
  5
  ```

  ### 5. Range to List

  ```py
  # Range to List
  my_range = range(5)
  my_list = list(my_range)
  print(my_list)
  ```

  ```
  [0, 1, 2, 3, 4]
  ```

  ### 6. Range to Tuple

  ```py
  # Range to Tuple
  my_range = range(5)
  my_tuple = tuple(my_range)
  print(my_tuple)
  ```

  ```
  (0, 1, 2, 3, 4)
  ```

  ### 7. Range to Set

  ```py
  # Range to Set
  my_range = range(5)
  my_set = set(my_range)
  print(my_set)
  ```

  ```
  {0, 1, 2, 3, 4}
  ```

  ### 8. Range to Dictionary

  ```py
  # Range to Dictionary
  my_range = range(5,10,2)
  my_dict = dict((index,item) for index,item in enumerate(my_range))
  print(my_dict)
  ```

  ```
  {0: 5, 1: 7, 2: 9}
  ```

</details>


<details>
  <summary>Python Dictionary</summary>
  
  - [ ] 1. Dictionary Basics
  - [ ] 2. Dictionary Length
  - [ ] 3. Dictionary Access
  - [ ] 4. Dictionary Get
  - [ ] 5. Dictionary Items
  - [ ] 6. Dictionary Keys
  - [ ] 7. Dictionary Values
  - [ ] 8. Dictionary Clear
  - [ ] 9. Dictionary Copy
  - [ ] 10. Dictionary Fromkeys
  - [ ] 11. Dictionary Has_key
  - [ ] 12. Dictionary Pop
  - [ ] 13. Dictionary Popitem
  - [ ] 14. Dictionary Setdefault
  - [ ] 15. Dictionary Update
  - [ ] 16. Dictionary with Nested Dictionaries
  - [ ] 17. Dictionary with list of Tuples
  - [ ] 18. Dictionary with list of Dictionaries

  ### 1. Dictionary Basics

  ```py
  # Dictionary Basics
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York', 'is_student': True}
  ```

  ### 2. Dictionary Length

  ```py
  # Dictionary Length
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(len(my_dict))
  ```

  ```
  4
  ```

  ### 3. Dictionary Access

  ```py
  # Dictionary access
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict["name"])
  ```

  ```
  John
  ```

  ### 4. Dictionary Get

  ```py
  # Dictionary get
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict.get("name"))
  ```

  ```
  John
  ```

  ### 5. Dictionary Items

  ```py
  # Dictionary items
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict.items())
  ```

  ```
  dict_items([('name', 'John'), ('age', 25), ('city', 'New York'), ('is_student', True)])
  ```

  ### 6. Dictionary Keys

  ```py
  # Dictionary keys
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict.keys())
  ```

  ```
  dict_keys(['name', 'age', 'city', 'is_student'])
  ```

  ### 7. Dictionary Values

  ```py
  # Dictionary values
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print(my_dict.values())
  ```

  ```
  dict_values(['John', 25, 'New York', True])
  ```

  ### 8. Dictionary Clear

  ```py
  # Dictionary clear
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  my_dict.clear()
  print(my_dict)
  ```

  ```
  {}
  ```

  ### 9. Dictionary Copy

  ```py
  # Dictionary copy
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  my_dict_copy = my_dict.copy()
  print(my_dict_copy)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York', 'is_student': True}
  ```

  ### 10. Dictionary Fromkeys

  ```py
  # Dictionary fromkeys
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  
  my_dict_fromkeys = dict.fromkeys(["name", "age", "city", "is_student"])
  print("Default fromkeys:", my_dict_fromkeys)
  
  my_dict_fromkeys_with_value = dict.fromkeys(["name", "age", "city", "is_student"], "default")
  print("fromkeys with default value:", my_dict_fromkeys_with_value)
  ```

  ```
  Default fromkeys: {'name': None, 'age': None, 'city': None, 'is_student': None}
  fromkeys with default value: {'name': 'default', 'age': 'default', 'city': 'default', 'is_student': 'default'}
  ```

  ### 11. Dictionary Has_key

  ```py
  # Dictionary has_key
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  print("name" in my_dict)
  ```

  ```
  True
  ```

  ### 12. Dictionary Pop

  ```py
  # Dictionary pop
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  my_dict.pop("name")
  print(my_dict)
  ```

  ```
  {'age': 25, 'city': 'New York', 'is_student': True}
  ```

  ### 13. Dictionary Popitem

  ```py
  # Dictionary popitem
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  my_dict.popitem()
  print(my_dict)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York'}
  ```

  ### 14. Dictionary Setdefault

  ```py
  # Dictionary setdefault
  my_dict = {"age": 25, "city": "New York", "is_student": True}
  my_dict.setdefault("name", "Unknown")
  print(my_dict)
  ```

  ```
  {'age': 25, 'city': 'New York', 'is_student': True, 'name': 'Unknown'}
  ```

  ### 15. Dictionary Update

  ```py
  # Dictionary update
  my_dict = {"name": "John", "age": 25, "city": "New York", "is_student": True}
  my_dict.update({"name": "Daniel", "age": 30})
  print(my_dict)
  ```

  ```
  {'name': 'Daniel', 'age': 30, 'city': 'New York', 'is_student': True}
  ```

  ### 16. Dictionary with Nested Dictionaries

  ```py
  # Dictionary with nested dictionaries
  my_dict = {
      "name": "John",
      "age": 25,
      "city": "New York",
      "is_student": True,
      "address": {
          "street": "123 Main St",
          "city": "New York",
          "zip": "10001"
      }
  }
  print(my_dict)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York', 'is_student': True, 'address': {'street': '123 Main St', 'city': 'New York', 'zip': '10001'}}
  ```

  ### 17. Dictionary with list of Tuples

  ```py
  # Dictionary with list of tuples
  my_dict = {
      "name": "John",
      "age": 25,
      "city": "New York",
      "skills": [("Python", "Intermediate"), ("SQL", "Advanced"), ("JavaScript", "Beginner")]
  }
  print(my_dict)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York', 'skills': [('Python', 'Intermediate'), ('SQL', 'Advanced'), ('JavaScript', 'Beginner')]}
  ```

  ### 18. Dictionary with list of Dictionaries

  ```py
  # Dictionary with list of dictionaries
  my_dict = {
      "name": "John",
      "age": 25,
      "city": "New York",
      "skills": [
          {"language": "Python", "level": "Intermediate"},
          {"language": "SQL", "level": "Advanced"},
          {"language": "JavaScript", "level": "Beginner"}
      ]
  }
  print(my_dict)
  ```

  ```
  {'name': 'John', 'age': 25, 'city': 'New York', 'skills': [{'language': 'Python', 'level': 'Intermediate'}, {'language': 'SQL', 'level': 'Advanced'}, {'language': 'JavaScript', 'level': 'Beginner'}]}
  ```

</details>


<details>
  <summary>Python Operations and Operands</summary>
  
  - [ ] 1. Addition
  - [ ] 2. Subtraction
  - [ ] 3. Multiplication
  - [ ] 4. Division
  - [ ] 5. Floor Division
  - [ ] 6. Modulus
  - [ ] 7. Exponentiation
  - [ ] 8. Assignment Operators
  - [ ] 9. Comparison Operators
  - [ ] 10. Logical Operators
  - [ ] 11. Identity Operators
  - [ ] 12. Membership Operators

  ### 1. Addition

  ```py
  # Addition
  a,b=10,5
  print(a+b)
  ```

  ```
  15
  ```

  ### 2. Subtraction

  ```py
  # Subtraction
  a,b=10,5
  print(a-b)
  ```

  ```
  5
  ```

  ### 3. Multiplication

  ```py
  # Multiplication
  a,b=10,5
  print(a*b)
  ```

  ```
  50
  ```

  ### 4. Division

  ```py
  # Division
  a,b=10,5
  print(a/b)
  ```

  ```
  2.0
  ```

  ### 5. Floor Division

  ```py
  # Floor Division
  a,b=10,5
  print(a//b)
  ```

  ```
  2
  ```

  ### 6. Modulus

  ```py
  # Modulus
  a,b=10,5
  print(a%b)
  ```

  ```
  0
  ```

  ### 7. Exponentiation

  ```py
  # Exponentiation
  a,b=10,5
  print(a**b)
  ```

  ```
  100000
  ```

  ### 8. Assignment Operators

  ```py
  # Assignment Operators
  a=b=c=10
  print(a,b,c)
  
  a=10
  a+=10
  print(a)
  
  a=10
  a-=10
  print(a)
  
  a=10
  a*=10
  print(a)
  
  a=10
  a/=10
  print(a)
  
  a=10
  a%=10
  print(a)
  
  a=10
  a//=10
  print(a)
  
  a=10
  a**=10
  print(a)
  ```

  ```
  10 10 10
  20
  0
  100
  1.0
  0
  1
  10000000000
  ```

  ### 9. Comparison Operators

  ```py
  # Comparison Operators
  a,b=10,5
  print(a==b)
  print(a!=b)
  print(a>b)
  print(a<b)
  print(a>=b)
  print(a<=b)
  ```

  ```
  False
  True
  True
  False
  True
  False
  ```

  ### 10. Logical Operators

  ```py
  # Logical Operators
  a,b=True,False
  print(a and b)
  print(a or b)
  print(not a)
  ```

  ```
  False
  True
  False
  ```

  ### 11. Identity Operators

  ```py
  # Identity Operators
  a,b=10,10
  print(a is b)
  print(a is not b)
  ```

  ```
  True
  False
  ```

  ### 12. Membership Operators

  ```py
  # Membership Operators
  a="Hello World"
  print("H" in a)
  print("h" in a)
  print("H" not in a)
  print("h" not in a)
  ```

  ```
  True
  False
  False
  True
  ```


</details>


<details>
  <summary>Python BMI Calculation</summary>
 
  ### Calculate BMI

  ```py
  # Calculate BMI
  height_in_feet=5.9167
  weight_in_kg=80
  
  height_in_meters=height_in_feet*0.3048
  
  bmi=weight_in_kg/(height_in_meters**2)
  print('BMI', bmi)
  ```

  ```
  BMI 24.59806602388617
  ```

</details>


<details>
  <summary>Python String Formatting</summary>
 
  ### Python String Formatting

  ```py
  #String Formatting
  name,marks="John",94.5678
  print(name,marks,sep='|')
  
  print("Name is",name,"and marks are",marks)
  print("Name is %s and marks are %.3f"%(name,marks))
  print("Name is {0} and marks are {1:.2f}".format(name,marks))
  print(f"Name is {name} and marks are {marks:.1f}")
  ```

  ```
  John|94.5678
  Name is John and marks are 94.5678
  Name is John and marks are 94.568
  Name is John and marks are 94.57
  Name is John and marks are 94.6
  ```

</details>



























