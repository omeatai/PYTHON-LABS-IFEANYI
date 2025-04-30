# PYTHON-DJANGO-FLASK-LABS-IFEANYI
by Ifeanyi Omeata

## Python

<details>
  <summary>Print String</summary>

  ### 1. Print String
  - [ ] Print "Hello World"
  ```py
  print("Hello World!")
  print("Python is easy!")

  if __name__ == '__main__':
      print('Completed!')
  ```

</details>

<details>
  <summary>Use Comments</summary>
  
  ### Use Comments
  - [ ] Enter Comments above statements
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

</details>

<details>
  <summary>Python Datatypes</summary>

  - [ ] NoneType: an object that does not contain any value
    - [ ] None
  - [ ] Numeric Types:
    - [ ] int - 100
    - [ ] float - 22.6
    - [ ] complex - 3+5j
    - [ ] binary - 0B1010
    - [ ] hexadecimal - 0XFF
  - [ ] Boolean Types:
    - [ ] True
    - [ ] False
  - [ ] Sequences:
    - [ ] str - "Hello"
    - [ ] list - [1,2,3,4]
    - [ ] tuple - (5,6,7)
    - [ ] range - range(0,9)
    - [ ] bytes
    - [ ] bytearray
  - [ ] Sets - {2,4,6,8}
  - [ ] Mappings

  ### 1. NoneType
  - [ ] NoneType
  ```py
  #NoneType
  a = None
  print(a)
  print(type(a))
  ```

  ### 2. Numeric-Integer
  - [ ] Integer
  ```py
  #Numeric-Integer
  a1 = 11
  b1 = 100
  c1 = -66
  print(a1,b1,c1)
  ```

  ### 3. Numeric-Floating Point (float)
  - [ ] Floating Point (float)
  ```py
  #Numeric-Floating Point (float)
  a2 = 33.5
  b2 = -25.8
  print(a2,b2)
  ```

  ### 4. Numeric-Complex
  - [ ] Complex
  ```py
  #Numeric-Complex
  a3 = 3+5j
  print(a3)
  print(type(a3))
  ```

  ### 5. Numeric-Binary
  - [ ] Binary
  ```py
  #Numeric-Binary
  a4=0B1010
  print(a4)
  print(type(a4))
  ```

  ### 6. #Numeric-Hexadecimal
  - [ ] Hexadecimal
  ```py
  #Numeric-Hexadecimal
  a5=0XFF
  print(a5)
  print(type(a5))
  ```

  ### 7. Boolean
  - [ ] Boolean
  ```py
  #Boolean
  a6 = True
  b6 = False
  print(a6,b6)
  print(9>8)
  print(type(a6))
  ```

</details>

<details>
  <summary>Type Conversion</summary>

  ### 1. Floating Point to Integer
  - [ ] Float to Integer
  ```py
  #Floating Point to Integer
  a1=33.5
  b1=int(a1)
  print(b1)
  print(type(b1))
  ```

  ### 2. String to Floating Point
  - [ ] String to Floating Point
  ```py
  #String to Floating Point
  a2="22.5"
  b2=float(a2)
  print(b2)
  print(type(b2))
  ```

  ### 3. Integer to Binary
  - [ ] Integer to Binary
  ```py
  #Integer to Binary
  a3=10
  b3=bin(a3)
  print(b3)
  print(type(b3))
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
  ```

  ```
  10
  ```

  ### 14. String Join

  ```py
  #string join
  s5="You are a good person"
  print(" ".join(s5))
  ```

  ```
  Y o u   a r e   a   g o o d   p e r s o n
  ```

  ### 15. String Join

  ```py
  #string join
  s5="You are a good person"
  print(" ".join(s5))
  ```

  ```
  Y o u   a r e   a   g o o d   p e r s o n
  ```

  ### 16. String Join

  ```py
  #string join
  s5="You are a good person"
  print(" ".join(s5))
  ```

  ```
  Y o u   a r e   a   g o o d   p e r s o n
  ```

</details>


























