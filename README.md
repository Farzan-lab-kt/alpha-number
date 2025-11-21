# alpha-number
def feb(x):
    if(x==0):
        return 0
    elif(x==1):
        return 1
    else:
        febonancci=feb(x-1)+feb(x-2)
        return(febonancci)
a=int(input())
for i in range(a+1):
    print(feb(i),end=" ")                                                                                     
