def recur_factorial (n)
if n==1:
return n
else:
return n*recur_factorial (n-1) 
#take input from the user
num=int(input("Enter a number:") 
#check is the number is negative
if n <0 :
    print("sorry, factorial is does not exist for negative number ") 
 elif num == 0:
    print(" factorial of 0 is 1") 
 else :
    print ("the factorial of ", num , " is", recur_factorial (n-1)) 
