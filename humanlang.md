# HumanLang
##### Details will be written down sooner or later. Have a great day.

## Example:
### Python:
```py
import random
print("DnD Virtual PyDice Roller")
rr = input("Commands: 'd4', 'd6', 'd8', 'd10', 'd12', 'd20', 'd100'. >")
if rr == "d4":
    rand = random.randint(1, 4)
    num = int(input("How many d4 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d6":
    rand = random.randint(1, 6)
    num = int(input("How many d6 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print(" __________")
    print("|\ o       \\")
    print("| \_______o\u0332_\\")
    print("| | o       |")
    print("|o|    o    |")
    print("\ |       o |")
    print(" \|_________|")
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d8":
    rand = random.randint(1, 8)
    num = int(input("How many d8 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d10":
    rand = random.randint(1, 10)
    num = int(input("How many d10 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d12":
    rand = random.randint(1, 12)
    num = int(input("How many d12 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d20":
    rand = random.randint(1, 20)
    num = int(input("How many d20 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d100":
    rand = random.randint(1, 100)
    num = int(input("How many d100 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
else:
    print("I am sorry, but I am unable to process your request. You might have made a typo.")
```
### HumanLang:
```
Order 'random'
Say, "DnD Virtual HLDice Roller V 1.0"
Ask, "Commands: 'd4', 'd6', 'd8', 'd10', 'd12', 'd20', 'd100'. >" and it means 'rr'.
If 'rr' is "d4", then:
    To get 'rand', get an integer between 1 and 4.
    Ask, "How many d4 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d6", then:
    To get 'rand', get an integer between 1 and 6.
    Ask, "How many d6 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, " __________".
    Say, "|\ o       \\".
    Say, "| \_______o", and a special character called u0332, and "\".
    Say, "| | o       |".
    Say, "|o|    o    |".
    Say, "\ |       o |".
    Say, " \|_________|".
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d8", then:
    To get 'rand', get an integer between 1 and 8.
    Ask, "How many d8 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d10", then:
    To get 'rand', get an integer between 1 and 10.
    Ask, "How many d10 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d12", then:
    To get 'rand', get an integer between 1 and 12.
    Ask, "How many d12 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d20", then:
    To get 'rand', get an integer between 1 and 20.
    Ask, "How many d20 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
Or, if 'rr' is "d100", then:
    To get 'rand', get an integer between 1 and 100.
    Ask, "How many d100 do you want to roll? >" and it means 'num'.
    Ask, "How many should I add to the roll? >" and it means 'add'.
    Say, "Rolling...".
    Say, ('rand'*'num')+'add'.
If there is anything else, then:
    Say, "I am sorry, but I am unable to process your request. You might have made a typo.".
