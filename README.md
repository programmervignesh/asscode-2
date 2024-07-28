#banking amount balance and widthdraw amounts
b=int(input("total amount balance:"))
w=int(input("widthdraw amount:"))
if w%5==0 and w<b: 
   print(b-w-0.50)
else:
   print(b) 
