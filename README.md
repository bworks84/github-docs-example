# github-docs-example

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation
Provide instructions on how to install and set up your project.

## Usage
Explain how to use your project with examples.

## Contributing
Tell others how they can contribute to your project.

## Task Lists
Github Flavored Markdown makes it easy to add check lists

- [x] Homework item 1
- [x] Homework item 2
- [ ] Homework item 3

## Links and References
Include links to external sources
- [Github Flavored Markdown Documentation](https://github.github.com/gfm/)
- [Google](https://google.com/)
- [ChatGPT](https://chatgpt.com/)
- Add links with references to easily mark/identify documentation  <sup>1</sup>

## References
- [StackOverflow](https://stackoverflow.com/) <sup>1</sup>

## Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. A good  __Cloud Engineer__ uses Codeblocks whenever possible

Because it allows others to copy and paste their code to replicate or research issues. You should use codeblocks with error messages as well 


### Example Python code with backticks for easy copying/pasting
```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

try:
    # Get user input
    num = int(input("Enter a non-negative integer: "))

    if num < 0:
        print("Factorial is undefined for negative numbers.")
    else:
        result = factorial(num)
        print(f"The factorial of {num} is {result}")
except ValueError:
    print("Invalid input. Please enter a non-negative integer.")


```

## Working with photos
To include a photo in documentation follow the example format listed:

-  \ ! \[Alt Text]\(image_url) \

- if the photo is too large, you can use HTML inline to resize the width and height
<img width="200px" src="https://github.com/bworks84/github-docs-example/assets/64917010/f1c5760a-2a6b-4197-8634-ed5ab3458e7a)" alt="Image" width="300" height="200" />

## Tables
Here is how to add tables for quick reference

| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |

## Inline Code
Use backticks (`) to format inline code within your text:

For example, to install a package, use `pip install package_name`.



