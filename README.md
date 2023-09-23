# Writing Good Documentation

## Step 1 - using Codeblocks.

Codeblocks in markdown make it *very easy* to **copy, paste, and share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```
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

- When you can you should attempt to apply syntax highlighting to your codeblocks

```{python}
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
Make note of where the backtick button is located. 
It should appear above the tab key, but it may vary based on your keyboard layout.

![backtick key](https://github.com/kedwards-io/github-docs-example/assets/145159193/1b7f4ccc-e502-438e-9167-450f235559c2)

Good Cloud Engineers use codeblcoks for both Code and Errors that appear in the console.

```bash
NameError: name 'undefined_variable' is not defined
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use GetiHub Flavoured Markdown Task Lists

Gethub extends Markdown to have a list where you can check off items.<sup>[1]<sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

|Name|Shortcode|Emoji|
|---|---|---|
|Cloud|`:cloud:`|:cloud:|
|Cloud with Lightning|`:cloud_with_lightning:`|:cloud_with_lightning:|

# Step 5 - how to create a table

you can use the following markdown format to create tables"

```md
|Name|Shortcode|Emoji|
|---|---|---|
|Cloud|`:cloud:`|:cloud:|
|Cloud with Lightning|`:cloud_with_lightning:`|:cloud_with_lightning:|
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[2]<sup>](#references)


## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [About writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)
- [GFM  - Task Lists]()<sup>[1]<sup>
- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]<sup>
- 
