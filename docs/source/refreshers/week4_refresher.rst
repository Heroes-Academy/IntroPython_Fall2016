Week 4 Refresher
================

Let's refresh your memory!
First, read the reminders about syntax.
Then, complete the exercises!


Reminders
---------

Basic Variables and Operations
******************************

There are four basic variable types
.. code-block:: python
    :linenos:
    x = 5     # int
    x = 5.0   # float
    x = "5"   # str
    x = True  # bool

You can convert between types
.. code-block:: python
    :linenos:
    y = "5"       # a string variable
    x = int(y)    # convert to integer
    x = float(y)  # convert to float
    z = str(x)    # convert the float to string. does this equal "5" or "5.0"

There are 7 math operator types
.. code-block:: python
    :linenos:
    x = 10
    y = 2
    x + y
    x - y
    x * y
    x / y
    x // y
    x ** y
    x % y

There are shortcuts for math operators.  The following pairs of statements have the same result.
.. code-block:: python
    :linenos:
    x = x * y
    x *= y

    x = x - y
    x -= y

    x = x * y
    x *= y

    x = x / y
    x /= y

    x = x // y
    x //= y

    x = x ** y
    x **= y

    x = x % y
    x %= y

Booleans and Comparisons
************************

There are boolean variables
.. code-block:: python
    :linenos:
    x = True
    x = False

Variables can be compared to create boolean variables
::
    x = 42
    y = 41
    x == y
    x != y
    x > y
    x >= y
    x < y
    x <= y

Boolean variables can be combined using the special boolean keywords
.. code-block:: python
    :linenos:
    x = True
    y = False
    z1 = x and y
    z2 = x or y
    z3 = (x and y) or (not x and not y)
    z4 = (not x and y) or (x and not y)

Code blocks let you group code.  In python, they are created with 4 spaces.
In pycharm and most python editors, hitting tab will just add 4 spaces.
:p:`if` statements use code blocks.
.. code-block:: python
    :linenos:
    x = 10
    y = 9
    if x > y:
        print("X is bigger!")

:p:`if` statements can be expanded using :p:`elif`.  :p:`elif` will only be used if the first :p:`if` is false.
(hidden question: What needs to be put into the placeholder to make the above code work?)
.. code-block:: python
    :linenos:
    x = "3"
    # placeholder
    if x == 1:
        print("x is 1")
    elif x == 2:
        print("x is 2")
    elif x == 3:
        print("x is 3")
    else:
        print("I'm not sure what x is")


Getting Input from Users
************************

You can use the `input`


Exercises
---------


.. role:: p(code)
    :language: python

.. code-block:: python
    :linenos:
    :caption:
    :name: