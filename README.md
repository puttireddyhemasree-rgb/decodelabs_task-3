#  Python-Internship-2026 | DecodeLabs 

**Intern:** Putti Reddy Hemasree | **Batch:** 2026  
**Role:** Junior Python Developer @ DecodeLabs
## Project 3: Random Password Generator

### **Goal**
Write a tool that asks the user for a password length and generates a random, complex password using letters and numbers using pure Python logic.

### **Key Skills Demonstrated**
- **Importing Modules**: Using `import random` and `import string` from Python's built-in libraries
- **String Manipulation**: Combining `string.ascii_letters + string.digits` to create character pool
- **Loops/Comprehension**: Using generator expression with `for i in range(length)` to build password
- **Built-in Functions**: `random.choice()` for random selection and `''.join()` to convert list to string

### **Features**
1. **Take Length Input** → User enters desired password length
2. **Generate Password** → Creates non-predictable password using letters and numbers
3. **Display Output** → Shows the generated secure password

### **How to Run**
```bash
password_generator.py
```
### **Sample Output**
```
Enter password length: 8
Generated Password: mK9pQ2tR
```
### **Status:** completed
