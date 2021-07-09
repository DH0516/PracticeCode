# PracticeCode
#Recursion practice python
def PS(n):
    if n > 1:
        PS(n-1)
    for i in range(n):
        print("*")
        
PS(5)
