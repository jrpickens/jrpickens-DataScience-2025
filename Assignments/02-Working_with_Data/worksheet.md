# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` _____________append()_______________

2. How can you remove an item from a list by value?  
   `Answer:` _____________remove()_______________

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` _______[2 , 4, 6, 8]_________

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
fav_foods = ['chebureki', 'borscht', 'burger']
fav_foods.append('salmon')
fav_foods.remove('burger')
print(fav_foods)
---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` ____________A list can be changed while a tuple is immutable____________

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` ___________no, they are a fixed list, so the elements cant be modified_____________

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
fav_nums = (3, 21, 10)
a, b, c = fav_nums
print(a)
print(b)
print(c)
```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` _______you have the option of reutring None or a default value that you provide instead of giving an error code________

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` ________"for key, value in thing.items():"__________

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
```
person = {
   "name": "James Pickens",
   "age": 22,
   "hobby": "Artisan"
}
for key, value in person.items():
   print(f"{key}: {value}")
---

## 🧾 Submit Checklist

- [x] I practiced creating and modifying lists.
- [x] I understand how tuples are different from lists.
- [x] I accessed and looped through dictionary items.
