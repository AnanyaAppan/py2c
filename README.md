# py2c
a program which converts python scripts to c

# Note
+ python version must be 2.7
+ indent in the python script must be 2 spaces
+ the python script must be in the same folder as py2c.py
+ use " "(double quotes) while writing strings (not single quotes)
+ input in the python script must be given as a type cast along with raw_input()
+ while using for loops along with range, use range(start,end,increment).

# features
+ takes care of declarations by checking type
+ converts list initialisations to array declarations
+ takes care of all control statements and looping constructs.
+ as of now, does not include function definitions
+ the generated c file will be indented along with braces acc. to the python script
+ includes input using map and raw_input()

# Instructions to use
+ clone the repo
+ run python py2c.py python_script_name.py
+ a file with python_script_name.c will be generated
