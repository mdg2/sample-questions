
# Question 2 (python)

What will be printed to console after running this code?

Answer # | Text
--- | ---
1 | 1
2 | 2
3 | 3
4 | 111

Correct Answer #4 - This is a trick question.  A string of "1" is being passed, so python will concatenate the strings.

**TIP** Increase difficulty by changing from multiple choice to numeric input.

Link to answer:
[https://ide.geeksforgeeks.org/KbzUh5UGz4](https://ide.geeksforgeeks.org/KbzUh5UGz4)


```python
def test(message, counter):
    if (counter > 1):
        return message
    return message + test(message, counter + 1)

print(test("1", 0))
```


