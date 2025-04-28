## Shell Scripting Tutorial
#### By ARYAM

### **Contents**

1. Basic Shell Commands
2.  Writing First Script
3. Variables and User Inputs
4. Conditional Statements
5. Loops

### **Introduction to Shell Scripting**

Shell scripting allows you to automate repetitive tasks, manage system operations, and create powerful programs right from your terminal.

A **shell script** is simply a text file containing a series of shell (bash, sh, etc.) commands.

### **Basic Commands**

Learn Basics Commands like:

| Commands  | Purpose |
| --------- | ------- |
|   ls      | List files and directories |
|   cd      | Change the current directory |
|  pwd      | Print the current working directory path|
|  mkdir    | Create a new directory |
| touch     | Create an empty file |
|  rm       | Remove(delete) files or directories|
| cat       | Display content of file|
| echo      | Print text or variables to the terminal|

### **Writing First Script**

Example of a simple shell script:

```
#!/bin/bash
echo "Hello, World!"
```

**Steps:**
1. Save the script as `hello.sh`.
2. Make it executable:

```bash
chmod +x hello.sh
```
3. Run the script:

```bash
./hello.sh
```

---

### **Variables and User Inputs**

- Declaring variables:

```bash
name="Aryam"
echo "Hello $name"
```

- Taking user input:

```
read -p "Enter your name: " user_name
echo "Welcome, $user_name!"
```

---

### **Conditional Statements**

Using `if-else`:

```
age=18

if [ "$age" -ge 18 ]; then
    echo "You are an adult."
else
    echo "You are a minor."
fi
```

---

### **Loops**

- **For Loop:**

```
for i in {1..5}
do
  echo "Number $i"
done
```

- **While Loop:**

```
count=1
while [ $count -le 5 ]
do
  echo "Count is $count"
  ((count++))
done
```

---

### **Conclusion**

Congratulations! 🎉  
You’ve taken your first big step into the world of shell scripting.

- Shell scripts are powerful tools for automating tasks, managing servers, and improving productivity.
- With just simple commands and basic logic, you can create scripts that save hours of manual work.















