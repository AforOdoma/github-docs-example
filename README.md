# Writing Good Documentation
[<sup>[2]</sup>](#External-References).
## Step 1 - Using Codeblocks

codeblocks in *markdown* makes it easy **forr tech people** to 

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
puts "Factorial of 5 is #{factorial(5)}"
```

-thhhhh

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
puts "Factorial of 5 is #{factorial(5)}"
```
* Make note of where the backtick button is located.
* It should appear above the tab key.
* But it may vary based on your key board layout



![IMG_20230921_013933~2](https://github.com/AforOdoma/github-docs-example/assets/113310868/59a681b6-f09b-4b4e-8f5f-dc671da7b5e4)

![bear](https://github.com/AforOdoma/github-docs-example/assets/113310868/5c1db75d-636a-4356-8c01-36de87fdcd18)

<img src="https://github.com/AforOdoma/github-docs-example/assets/113310868/5c1db75d-636a-4356-8c01-36de87fdcd18"  width="200" height="200"/>


Good cloud engineers use codeblocks for both code and errors that appear in the console

```bash
NameError: undefined local variable or method `undefined_variable' for main:Object
```

> Here is an example of using a codeblock for an error that appears in bash

## Step 3 -Use Github Flavored Markdown Tast Lists

Github extends Markdown to have a list where you can check off items. <sup>1</sup>
* [x] Finish Step 1
* [ ] Finish Step 2
* [ ] Finish Step 3

# Step 4 - Use Emojis (Optional)
GitHub Flavored Markdown (GFM) suports emoji short codes.
Here are some examples

| Name | Shortcode | Emoji |
| --- | --- |---|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` |:cloud_with_lightning:|

# Step 5 - How to create a table

You can use the following markdown format to create tables

```markdown
| Name | Shortcode | Emoji |
| --- | --- |---|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` |:cloud_with_lightning:|
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formating options. 
[<sup>[2]</sup>](#External-References).

## External References

* [GitHub Flavored Markdown Spec](https://https://github.github.com/gfm/). 
* [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links).
* [GFM - Task lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>1</sup>
* [emoji-cheat-sheet](https://https://https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#emoji-cheat-sheet).
* [Tables (extension)](https://https://github.github.com/gfm/#tables-extension-).  <sup>2 </sup>


