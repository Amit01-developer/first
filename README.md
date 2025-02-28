for row in range (4):
    for col in range(row,4):
        print(" ",end=" ")
    for col in range(row):
        print("*",end=" ")
    for col in range(1,row):
        print("*",end=" ")
    for col in range(row,4):
        print(" ",end=" ")
    for col in range(row+1,4):
        print(" ",end=" ")
    for col in range(row-1):
        print("*",end=" ")
    for col in range(row):
        print("*",end=" ")
    print()



for row in range(7):
    for col in range(row):
        print(" ",end=" ")
    for col in range(row,7):
        print("*",end=" ")
    for col in range(row+1,7):
        print("*",end=" ")
    print()
