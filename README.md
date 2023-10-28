# github-docs-example

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

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

## Using Codeblocks

The primary purpose of using Codeblocks is to highlight syntax and errors in the console. Codeblocks make it *very easy* for tech people to **copy, paste, share** code. A good  __Cloud Engineer__ uses Codeblocks whenever possible

Because it allows others to copy and paste their code to replicate or research issues. You should use codeblocks with error messages as well. 


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
<img width="200px" src="assets/desert_sunset.jpg" alt="Image" width="300" height="200" />

## Tables
Here is how to add tables for quick reference

| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |

## Inline Code
Use backticks (`) to format inline code within your text:

For example, to install a package, use `pip install package_name`.

## Links and References
Include links to external sources
- [Github Flavored Markdown Documentation](https://github.github.com/gfm/)
- [Google](https://google.com/)
- [ChatGPT](https://chatgpt.com/)
- Add links with references to easily mark/identify documentation  <sup>1</sup>

## References
- [StackOverflow](https://stackoverflow.com/) <sup>1</sup>


---


# ChatGPT

In GitHub-Flavored Markdown (GFM), you can create quick links to reference different sections or headings within your document using anchor links. Anchor links make it easy for readers to navigate to specific parts of your document. Here's how you can create quick links using anchor links:

1. **Create an Anchor:**

   To create an anchor link, you'll need to add an HTML `<a>` tag with the `name` attribute to the section or heading you want to link to. For example:

   ```markdown
   <a name="section-1"></a>
   ## Section 1
   This is the content of Section 1.
   ```

   In the above example, we've added an anchor link with the name "section-1" before the heading "Section 1."

2. **Create a Quick Link:**

   To create a quick link that references the anchor, you can use regular Markdown links. For example:

   ```markdown
   [Go to Section 1](#section-1)
   ```

   This Markdown link will take the reader to the "Section 1" heading when clicked.

3. **Use Descriptive Text:**

   It's a good practice to use descriptive text in your link to make it clear where the link will take the reader. For example:

   ```markdown
   [Jump to the Installation Section](#installation)
   ```

   This link will take the reader to a section with the `name` attribute set to "installation."

By following these steps, you can create quick links in your GFM document that help readers easily navigate to specific sections or headings. Remember that anchor links are created using HTML tags, while the quick links are created using regular Markdown link syntax.


