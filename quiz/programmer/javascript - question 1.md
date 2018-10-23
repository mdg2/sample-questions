
# Question 1 (javascript)

What will be printed to console after running this code?

Answer # | Text
--- | ---
1 | 0
2 | 3
3 | 4
4 | 5

Correct Answer #2 - "3" is the correct answer as the for loop will break/exit after the third iteration.

**TIP** Increase difficult by changing from multiple choice to numeric input.

Link to answer:
[https://ide.geeksforgeeks.org/tryit.php/BN2HMsrTvb](https://ide.geeksforgeeks.org/tryit.php/BN2HMsrTvb)


```html
<div id="idOutput"></div>

<script>
 function test(val) {
     for (i = 0; i < 5; i += 1) {
         if (i > 2) {
             break;
         }
         val = val + 1
     }
     return val;
 }

 document.getElementById("idOutput").innerHTML = test(0);
</script>
```


