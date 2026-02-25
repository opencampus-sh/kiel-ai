# Solutions

### Exercise: Create a flow chart for a simple calculator

<figure><img src="../../../.gitbook/assets/calculator.svg" alt=""><figcaption></figcaption></figure>

### Arrow Challenge

Write a function `draw_arrow(n)` that takes an integer `n` and prints the following pattern:

`n = 3`

```
  *
 ***
*****
  *
  *
```

`n = 5`

```
    *
   ***
  *****
 *******
*********
    *
    *
```

**Solution:**

```python
def draw_arrow(n):
    for i in range(n):
        #number of stars:
        stars = (i*2 +1) * "*"  # 1, 3, 5, 7, ...
        #number of spaces
        spaces = ((n-i) - 1) * " " # n-1, n-2, n-3, ...
        #print row
        print(spaces+stars)
    
    #print shaft
    shaft_spaces = (n-1) * " "
    print(shaft_spaces+"*")
    print(shaft_spaces+"*")
```

Try it out [here](https://colab.research.google.com/drive/1DnnYOE9w55l8Ng_C1is1ddwuNm4ao9du)
