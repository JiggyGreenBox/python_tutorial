# Python Tutorials

A revision list for learning python.

## Week 1
- printing output
    ```python
    print('text')
    print(5)

    x = "this is text"
    print(x)
    ```

- ```'+'``` operator in ```print()```
    ```python
    # adding str and int exhibits different behaviour
    
    print('string1' + 'string2')  # string1string2

    print(1 + 3) # 3

    print(1.0 + 2.2) # 3.2
    ```

- ```type()``` function
    ```python
    x = 5       # this is an integer (no decimals, can be negative)
    y = 5.5     # this is a float (decimal, can be negative)
    z = '5'     # string/ aka text

    print(type(x))      # int   - integer
    print(type(y))      # float - floating point decimal
    print(type(z))      # str   - string aka text

    a = {'name':'sourabh','age':34}
    b = [1,2,3]
    
    print(type(a)) # dict
    print(type(b))  # list
    ```

- casting
    ```python

    a = 5         # default type will be int
    type(a)       # int

    # we can assign the type ourselves

    x = str(3)    # x will be '3'   (type = str)
    y = int(3)    # y will be 3     (type = int)
    z = float(3)  # z will be 3.0   (type = float)

    ```

- list
    ```python

    mylist = ['banana', 'apple', 'anjeer']

  # print original list
  print(mylist)
  # ['banana', 'apple', 'anjeer']
  
  # add to list
  mylist.append('cherry')
  
  # change the first value
  mylist[0] = 'mango'
  
  # check the updated list
  print(mylist)
  # ['mango', 'apple', 'anjeer', 'cherry']
  
  
  # how many entries do we have?
  print(len(mylist)) # 4

    ```

- ```True / False``` and ``if``
    ```python
    # booleans aka bool are variables that store True or False
    # we use them to make decisions

    if (True):
        print('this will print')


    if (False):
        print('this will not print')


    x = True

    if (x):
        print('x is True')

    # is 5 greater than 3? yes aka True
    if 5 > 3:
        print('5 > 3 evaluates to True')


    # is 0 greater than 3? no aka False
    if 0 > 3:
        print('0>3 evaluates to False') # will not print

    ```
