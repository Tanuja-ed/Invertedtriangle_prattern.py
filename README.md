# Invertedtriangle_prattern.py
Inverted triangle pattern  in Python using  for loops 
#lower piramid  
for i in range(n,0,-1): # if n=5 range(5,1) after 1 loop -1
    for j in range(n-i):#here range is 5;5-5=0 no space
        print(" ",end="")
    for k in range (2*i-1):#2*5-1=9 stars
        print("*" , end="")
    print()  #after loop next line 
