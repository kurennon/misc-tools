# misc-tools
A set of miscellaneous tools written in Python, Java, etc.

## Tools Available:

1. [Gift Exchanger (Python)](#gifte)
2. [Find Validator (Python)](#fvalid)

## 1. Gift Exchanger (Python) <a name=gifte></a>

A program to auto generate a set of exchange buddies for a gift exchange.
At the moment requires a config file, called geconf.txt by default, formatted as follows:

    Name of exchange
    Guest Name
    Guest Pronoun
    Guest Email
    Guest Likes
    Guest Dislikes
    ...
    
    
The Guest * parts are required for each guest.
There is currently a terminal and Tkinter frontend, called gifte_term.py and gifte_tkinter.py.
Any frontend that can call python code may be written on top of the library file named gifte_core.py.

## 2. Find Validator (Python) <a name=fvalid></a>

A Program that takes a number in base 1-35 (determined by the user) and
outputs the last digit of the sum of the digits.
This program is interactive, allowing multiple numbers to have a validator
found and multiple bases to be used without closing the program.
