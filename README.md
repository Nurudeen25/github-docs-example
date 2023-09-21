# Wrting Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy8 for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows other to copy paste their code to replicate or research issues.

- This code defines a factorial function that calculates the factorial of a non-negative integer n recursively. It then takes user input, calculates the factorial, and displays the result. Make sure you have Ruby installed on your system to run this code.
```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}"
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}"
end
```


![2023-04-27](https://github.com/Nurudeen25/github-docs-example/assets/67113867/b0f2ad44-25bf-4dc6-bb02-cb186468b162)

<img width="200px" src="https://github.com/Nurudeen25/github-docs-example/assets/67113867/b0f2ad44-25bf-4dc6-bb02-cb186468b162"/>

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.


```bash
Error: undefined local variable or method `undefined_variable' for main:Object
Backtrace:
example.rb:2:in `<main>'
```

> Here is an example of using a codeblock for an error that appears in bash.


## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# step 4 - Use Emojis (Optional)

Here are some examples:
GitHub Flavoured Markdown (GFM) supports emoji shortcodes. Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightening | `🌩️:` | 🌩️: |

## Step 5 - how to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightening | `🌩️:` | 🌩️: |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>]



## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links) 
- [GFM - Tasks List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links) <sup>[1]</sup>
