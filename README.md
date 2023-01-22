# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.
## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Develop:Sirisha onteddu
#ref.no:22003264
n1=int(input())
n2=int(input())
def gcd():
   if n1>n2:
      smaller=n2
   else:
      smaller=n1
   for i in range (1,smaller+1):
     if(n1%i==0 and n2%i==0):
        gcd=i
   print("GCD of two numbers is:",gcd)
 ```

## Output:
![image](https://user-images.githubusercontent.com/119389139/213917367-ed78497a-2ee1-465f-a3ef-1fedaa045009.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
