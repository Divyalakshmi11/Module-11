# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
def slice(str1):
    text=str1[2:10:2]
    print(f"The sliced string is '{text}'")
str1=""

```

### OUTPUT
<img width="1040" height="288" alt="image" src="https://github.com/user-attachments/assets/5b475e3f-6e65-42e3-9a2e-2b9f4010a689" />


### RESULT
Thus the python program to create a python function that accepts the string and prints every second item between 2 to 10. and then prints the new string has been implemented and executed successfully.
