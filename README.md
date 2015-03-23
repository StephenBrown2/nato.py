# nato.py

A simple command line script to convert ASCII text to NATO phonetics,
and transliterate other keyboard symbols, for the purpose of reading
passwords and other confusing text over the phone... or just sounding
really cool.

## Usage:

### Simple

Just make the script executable, and pass it the word you want to transliterate:

```
% nato password
password
papa alpha sierra sierra whiskey oscar romeo delta
```

It even handles spaces and UPPERCASE letters:

```
% nato Stephen Brown II
Stephen Brown II
UPPERCASE SIERRA tango echo papa hotel echo november space UPPERCASE BRAVO romeo oscar whiskey november space UPPERCASE INDIA UPPERCASE INDIA
```

And if you want to get crazy...

```
% nato 'w@lRu$Es {ar3} N1\c#!'
w@lRu$Es {ar3} N1\c#!
whiskey at-sign lima UPPERCASE ROMEO uniform dollar-sign UPPERCASE ECHO sierra space left-curly-brace alpha romeo tree right-curly-brace space UPPERCASE NOVEMBER one backslash charlie octothorpe exclamation-point
```
