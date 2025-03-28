# Simple To-Do List   

This repository has a basic script that lets you create a simple to-do list.  

## Code in This Repo  
```python
tasks = []  

while True:  
    task = input("Enter the task (or type 'done' to finish): ")  
    if task.lower() == "done":  
        break  
    tasks.append(task)  

print("\nYour To-Do List:")  
for i, task in enumerate(tasks, 1):  
    print(f"{i}. {task}")  
