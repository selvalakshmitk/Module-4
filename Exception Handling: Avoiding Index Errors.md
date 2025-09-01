# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an *IndexError* when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list a with some integer elements.
2. Use a *try-except* block:
   - In the try block, attempt to access an index that is out of range (e.g., list1[6]).
   - In the except block, catch the error and print a custom message "6 is not accepted".
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
try:
  
    n=int(input())
    
    a = []
    
    for i in range(1,n+1):
    
        n1=int(input())
        
        a.append(n1)
   
    print(a)
    
    print(a[6])
                                
except IndexError:
       
        print("6 is not accepted")
        
## Output
![WhatsApp Image 2025-09-01 at 16 03 22_fe1ae243](https://github.com/user-attachments/assets/4f6b271d-9054-4e8b-8986-94619fe3c6b1)


## Result
Thus, Python program that handles an *IndexError* when trying to access an element beyond the available range of a list is excuted and verified. 
