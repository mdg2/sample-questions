
# Question 2 (javascript)

What will be displayed in the DIV after running this code?

Answer # | Text
--- | ---
1 | sally
2 | sold
3 | seashells
4 | seashore

Correct Answer #3 - "seashells" is the correct answer.

Link to answer:
[https://ide.geeksforgeeks.org/tryit.php/bixbW7zc9g](https://ide.geeksforgeeks.org/tryit.php/bixbW7zc9g)


```html
<div id="idOutput"></div>

<script>
  function test(val) {
      tokens = val.split(' ');
      return tokens.slice(0, 3).pop();
  }
  
  document.getElementById("idOutput").innerHTML = test("sally sold seashells at the seashore");
</script>
```


