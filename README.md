# Writing Good Documentation

## Step 1 - Using Codeblocks

- Codeblocks in markdown is a good practice.

- Use backticks (`) to create codeblocks and not to be confused with single quotations (').
  


```Python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```
- Try to use syntax highlighting for codes whenever it is possible.



<img width="250" src="https://github.com/anijyojyo/github-docs-terraform/assets/71109436/de575bac-d1f8-4072-8440-669e832f92b0">



Use Codeblocks for both Code and errors that appear in the console



```bash
try:result = 5 / 0  # Attempting to divide by zero
except ZeroDivisionError as e:
    print(f"Error: {e}")
```

> Here is an example of using a codeblock for an error that appears in bash


## Step 3 - Use Github Flavoured Markdown Tasks Lists

Github extends Markdown to have a list where you can check off items

- [X] Finish Step 1
- [] Finish Step 2
- [] Finish Step 3
- [] Finish Step 4 

## Step 4 - Use emojis ( Optional)

Github Flavoured Markdown supports emojis
Here are some examples:
☁️ ⛈️


[Secret Window Hidden Garden]_(secret-window/hidden-garden.md)



##  References


- [https://github.github.com/gfm/)https://github.github.com/gfm/](https://github.github.com/gfm/)https://github.github.com/gfm/
