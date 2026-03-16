# 課堂實作 (Practice Labs) 

## P03-01

x = 10
if x > 0:
    print("Positive")
## P03-02
x = -5
if x > 0:
    print("Pos")
else:
    print("Non-Pos")
## P03-03
n = 4
if n % 2 == 0:
    print("Even")
else:
    print("Odd")
## P03-04
score = 59
if score >= 60:
    print("Pass")
else:
    print("Fail")
## P03-05
pwd = input("Pwd: ")
if pwd == "secret":
    print("Access Granted")
else:
    print("Denied")
## P03-06
n = 0
if n > 0: print("+")
elif n < 0: print("-")
else: print("0")
## P03-07
s = 85
if s >= 90: print("A")
elif s >= 80: print("B") 
else: print("C")
## P03-08
age = 20
license = True
if age >= 18:
    if license:
        print("Can Drive")
## P03-09
age = 5
if age < 12: print("Child")
elif age < 18: print("Teen")
else: print("Adult")
## P03-10
a, b = 1, 1
if a > 0 and b > 0: print("Both Pos")
## P03-11
msg = "Yes" if True else "No"
if "a" in "apple": print("Has a")
