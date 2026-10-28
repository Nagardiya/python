
# Core python

rows = 5

for i in range(1, rows + 1):
    print("* " * i)



*
* *
* * *
* * * *
* * * * *


n = 5

for i in range(n, 0, -1):
    for j in range(i):
        print("*", end=" ")
    print()


* * * * *
* * * *
* * *
* *
*



    
