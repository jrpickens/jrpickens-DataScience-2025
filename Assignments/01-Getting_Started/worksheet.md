# 📝 Worksheet: 01 - Getting Started with Data Science

This worksheet guides you through key tasks and questions for each topic in this module. Use it to take notes, practice, and review before submitting your assignments.

---

## 🧠 Section 1: Google Colab

1. What is the primary difference between Colab and Jupyter Notebook on your local machine?  
   `Answer:` Colab is cloud based for easy sharing when jupyter runs locally and can work offline, i think its also dependent on your hardware.

2. How do you save a notebook to your own Google Drive?  
   `Answer:` There is a save copy to drive option when saving the notebook

3. In Colab, how do you add a new Markdown cell?

--- There should be a text button at the top of the notebook, optionally, whenever you hover over the next area of a notebook, a text box option will also show up

### ✏️ Task: Code Practice

```python
# Write a Python statement that prints your full name and your favorite number.
print("My name is James Pickens and my favorite number is 10")
```

---

## 🔗 Section 2: GitHub + Colab Workflow

4. What are the steps to upload a notebook to GitHub?  
   `Answer:` Save a copy to your drive and rename it, then click file at the top and click upload notebook, click on the github tab

5. What does "commit" mean in the context of GitHub?  
   `Answer:` its to save something that youve done, usefull for seeing the the changes of your file over time.

6. How do you open a GitHub notebook in Colab?  
   `Answer:` open up colab, click file at the top, click on open notebook, go down to the github tab and paste your repository path from the url.
---

### ✏️ Task: URL Check

Paste the link to your GitHub notebook here:  
`Link:` https://github.com/jrpickens/data-science-notebooks 

---

## 📊 Section 3: Python Basics

7. What are the four primary Python data types you've used so far?  
   `Answer:` int, bool, str, float

8. What’s the output of this code?

```python
x = 10
y = 2.5
print(type(x + y))
```

   `Answer:` It would output the results data type,'float'

---

### ✏️ Task: Input + Output

```python
# Write code to ask the user for a number and double it.
num = int(input('give me a number of your choice'))
num = num * 2
print('your number doubled', + num)

```

---

## 🧾 Submit Checklist

- [x] I can open and edit notebooks in Colab.
- [x] I have uploaded a notebook to GitHub.
- [x] I practiced using basic Python code (variables, types, arithmetic).
