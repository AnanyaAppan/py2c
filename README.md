# py2c
a program which converts python scripts to c

# Note
+ indent in the python script must be 2 spaces
+ the python script must be in the same folder as py2c.py
+ use " "(double quotes) while writing strings (not single quotes)

# features
+ takes care of declarations by checking type
+ converts list initialisations to array declarations
+ takes care of all control statements and looping constructs.
+ as of now, does not include function definitions
+ the generated c file will be indented along with braces acc. to the python script
