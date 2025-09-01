# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of words in a text file story.txt.

## 🧠 Algorithm
1. Open the file story.txt in read mode.
2. Read the entire content of the file into a variable content.
3. Split the content into individual words using the split() method.
4. Count the total number of words obtained.
5. Return this count as the output.

## 🧾 Program
def create_file(file_path, file_content):
 
  with open(file_path,'w') as file:
  
    file.write(file_content)

def count_words_in_file(file_path):
 
  with open (file_path,'r') as file:
  
    content = file.read()
    
    words = content.split()
    
    return len(words)

## Output
![WhatsApp Image 2025-09-01 at 16 09 17_e9435905](https://github.com/user-attachments/assets/cc16bcea-81e5-45dd-82ae-07d9f7c78d77)


## Result
Thus, Python program that counts the number of words in a text file story.txt is excuted and verified.
