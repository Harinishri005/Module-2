# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To print right angled triangle pattern of numbers .Get the number of rows as input .


### ALGORITHM
1.Start
2.Input the number of rows n from the user.
3.For each row number i from 1 to n:
4.Start an inner loop from j = 1 to i:
5.Print number j (on the same line).
6.After the inner loop ends, move to the next line.
7.End


### PROGRAM
#Reg.No:212223090008
#Name:Harinishri S
```
rows=int(input())
for i in range(1, rows):
    num=1
    for j in range(rows, 0,-1):
        if j>i:
            print(" ",end=' ')
        else:
            print(num, end=' ')
            num +=1
    print("")
```

### OUTPUT

![outputpatt](https://github.com/user-attachments/assets/9554ab5b-bca2-4991-a361-5561ca874fab)

### RESULT
The program prints a right-angled triangle where each row i contains sequential numbers from 1 to i, forming an incremental numeric pattern.






