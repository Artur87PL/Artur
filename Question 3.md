mydict=dict()
for n in range(8,0,-1):
    x=n*n
    #print(str(x))
    #print(str(n))
    print(str(x)+":"+str(n))
    mydict.update({n:x})
print(mydict)
