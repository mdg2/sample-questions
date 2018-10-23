
# Question 2 (C++)

What will be printed to console after running this code?

Answer # | Text
--- | ---
1 | 2
2 | 3
3 | num++
4 | test(2)

Correct Answer #1 - "2" is the correct answer.  num++ will return the value of num before the increment.

**TIP** Increase difficult by changing from multiple choice to numeric input.

Link to answer:
[https://ide.geeksforgeeks.org/sW8IHa9Pqs](https://ide.geeksforgeeks.org/sW8IHa9Pqs)


```c++
#include<iostream>

using namespace std;

int test(int num) {
    return num++;
}

int main()
{
	cout << std::to_string(test(2));
	return 0;
}
```


