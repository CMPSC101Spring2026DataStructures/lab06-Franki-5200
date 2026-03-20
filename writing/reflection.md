# CS101 Spring 2026 — Practice Midterm Reflection

Name: Francesca Hoh
Date: 3/13/26

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `to and do` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.


---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I felt pretty good actually. I got most answers right first try. The only difficult part was Which of the following is a valid Python integer literal, but other than that it wasn't too difficult.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

Which of the following is a valid Python **integer** literal, was the hardest question for me. I had to look up the definition to make sure I had it right. I think the answer was 0xff which actually stood for a number

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

range(1, 7, 2)This skips upwards by 2
range(3, 8, -2)This counts backwards from 2


---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

For a list you can change what’s in it while in tuples you can't change what's inside. Tuples would be for unchanging variables while list could be a roster of student names. A dictionary has sets and key pairs while sets only want unique values. A set is for when you would filter while a dictionary is better for more complex values

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A parameter is a predetermined value. def hi(name, message="Hello"):
return f"{message}, {name}!
print(greet("Silver"))
If the argument is omitted it crashes.


---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [n*2 for n in range(1, 11) if n % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

The answer is 256, This is done because 2 squared is done but that is cubed so you have 2^2^3 which equals 256.

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

A class is sort of like a blueprint that can be used over and over again. It’s necessary to program one for organization, two for repeatability and three for functionality in general.

---

(Did you remember to add your name and date at the top of this document?)
