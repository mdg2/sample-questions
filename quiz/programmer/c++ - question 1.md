# Question 1 (C++)

What will be printed to console after running this code?

Answer # | Text
--- | ---
1 | 0
2 | 12
3 | 3
4 | test(2)

Correct Answer #2 - "12" is the correct answer

**TIP** Increase difficulty by changing from multiple choice to numeric input.

Link to answer:
[https://ide.geeksforgeeks.org/bPpQDTnVZt](https://ide.geeksforgeeks.org/bPpQDTnVZt)


```c++
#include<iostream>

using namespace std;

string test(int num) {
  return "1" + std::to_string(num);
}

int main()
{
  cout << test(2);
  return 0;
}
```
