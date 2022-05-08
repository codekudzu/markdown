<!-- Headings -->
# Headings
To add any heading from H1 through H6, use the below markdown syntax:

> Pound (#) symbol followed by the heading title. For H1 use a pound symbol (#), for H2 use two pound symbols (##), for H3 use three pound symbols (###), so on and so forth.

\# Heading 1
# Heading 1

\## Heading 2
## Heading 2

\### Heading 3
### Heading 3

\#### Heading 4
#### Heading 4

\##### Heading 5
##### Heading 5

\###### Heading 6
###### Heading 6

# Emphasis
<!-- Italics -->
## Italics
Enclose the text either in asterisks (*) or underscores (_) to italicize the text.

### Example:

| Syntax                     | Output                 |
| -------------------------- | ---------------------- |
| \*This  text\* is italic   | *This  text* is italic |
| \_This text\_ is italic    | _This text_ is italic  |

<!-- Strong -->
## Strong / Bold
Enclose the text either in double asterisks (**) or double underscores (__) to make the text bold.

### Example:

| Syntax                         | Output                    |
| ------------------------------ | ------------------------- |
| \*\*This text\*\* is strong    | **This text** is strong   |
| \_\_This text\_\_ is strong    | __This text__ is strong   |

<!-- Strikethrough -->
## Strikethrough
Enclose the text in double tilde (~~) to strikethrough the text.

### Example:

| Syntax                                | Output                           |
| ------------------------------------- | -------------------------------- |
| \~\~This text\~\~ is strikethrough    | ~~This text~~ is strikethrough   |

<!-- Horizontal Rule -->
## Horizontal Rule

Use three or more hyphens (---) or underscores (___) to generate a horizontal rule.

---
___

<!-- Blockquote -->
## Blockquote

Start a paragraph with \> to show the text as blockquote.
> This is a quote

<!-- Links -->
## Links
Use the below syntax to create links.

`
[Google](https://www.google.com)
`

[Google](https://www.google.com)

`
[Google](https://www.google.com "Link Title")
`

[Google](https://www.google.com "Google Search Engine")

## Lists
<!-- Unordered List -->
### Unordered List
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

<!-- Ordered List -->
### Ordered List
1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`

<!-- Images -->
## Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the URL to the image in parentheses. You can optionally add a title in quotation marks after the URL.
`
![Markdown Logo](https://markdown-here.com/img/icon256.png "Title")
`

![Markdown Logo](https://markdown-here.com/img/icon256.png "Icon")

<!-- Github Markdown -->

<!-- Code Blocks -->
```bash
  npm install

  npm start
```

```javascript
  function add(num1, num2) {
    return num1 + num2;
  }
```

```python
  def add(num1, num2):
    return num1 + num2
  }
```

<!-- Tables -->
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| Jane Doe | jane@gmail.com |

<!-- Task Lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3