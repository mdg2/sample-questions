
# Question 2 (python)

What will be printed to console after running this code?

Answer # | Text
--- | ---
1 | 1
2 | 2
3 | 3
4 | 111

Correct Answer #3 - "3" is the correct answer.  The recursive loop will run two times.  Returning first (1 + 1) and the +1 = 3.

**TIP** Increase difficult by changing from multiple choice to numeric input.

Link to answer:
[https://ide.geeksforgeeks.org/qq2SmHABkb](https://ide.geeksforgeeks.org/qq2SmHABkb)


```python
def test(message, counter):
    if (counter > 1):
        return message
    return message + test(message, counter + 1)

print(test(1, 0))
```


