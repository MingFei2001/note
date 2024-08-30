# Markdown

## Table of Contents
1. [Introduction](#introduction)
2. [Markdown Syntax](#markdown-syntax)
   - [Headings](#headings)
   - [Lists](#lists)
      - [Unordered List](#unordered-list)
      - [Ordered List](#ordered-list)
   - [Blockquotes](#blockquotes)
   - [Links and Images](#links-and-images)
      - [Links](#links)
      - [Images](#images)
   - [Code Blocks](#code-blocks)
   - [Tables](#tables)
3. [Summary & Next Steps](#summary--next-steps)

## Introduction
Markdown is a lightweight markup language used to format text. 
It's often used for writing documentation, README files, and 
creating rich text using a plain text editor.

## Markdown Syntax

### Text formatting
Text can be formatted in markdown.

#### Bold
Use two * or _ on each side of the text.
```markdown
**bold** or __bold__
```
> Result

**bold** or __bold__

#### Italics
Use one * or _ on each side of the text.

```markdown
*italic* or _italic_
```
> Result

*italic* or _italic_

#### Bold and Italic
Use three * or _ on each side of the text.
```markdown
***bold and italic*** or ___bold and italic___
```

> Result

***bold and italic*** or ___bold and italic___

#### Strikethrough
Strikethrough text is created using 2 tildes `~~ ` around the text.
```markdown
~~This text is struck through.~~
```
> Result

~~This text is struck through.~~

### Headings
Headings in Markdown are created by using the `#` symbol. 
The number of `#` symbols indicates the level of the heading.
The biggest is 1`#` and the smallest is 6`#`.

```markdown
# Heading 1
## Heading 2
### Heading 3
```
> Result

# Heading 1
## Heading 2
### Heading 3

### Lists
Lists can be either ordered or unordered.

#### Unordered List
```markdown
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```
> Result

- Item 1
- Item 2
  - Subitem 1
  - Subitem 2

#### Ordered List
```markdown
1. First item
2. Second item
3. Third item
```
> Result

1. First item
2. Second item
3. Third item

#### Task List
Task lists are used to create checkboxes. They are created using - [ ] for unchecked and - [x] for checked.

```markdown
- [ ] Task 1
- [x] Task 2
```

> Result

- [ ] Task 1
- [x] Task 2

### Blockquotes
Blockquotes are created using the > symbol. They are often used to highlight important text or quotes.

```markdown
> Markdown is a lightweight markup language with plain text formatting syntax.
```

#### Result

> Markdown is a lightweight markup language with plain text formatting syntax.

### Links and Images
Links are created using `[text](URL)` and images using `![alt text](URL)`.

#### Links
```markdown
[OpenAI](https://www.openai.com)
```
> Result

[OpenAI](https://www.openai.com)

#### Images
```markdown
![OpenAI Logo](https://www.openai.com/favicon.ico)
```
> Result

![OpenAI Logo](https://www.openai.com/favicon.ico)

### Code blocks
Code blocks can be created using triple backticks. You can specify the language for syntax highlighting.

````markdown
```python
def hello_world():
    print("Hello, world!")
```
````

> Result
```python
def hello_world():
    print("Hello, world!")
```
*p/s: to create a nested code block you can use different amount of backticks(```)*

### Tables
Tables are created using pipes (`|`) and hyphens (`-`).

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Data 1   |
| Row 2    | Data 2   |
```

> Result

| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Data 1   |
| Row 2    | Data 2   |

### Horizontal Rules
Horizontal rules are used to create a line that separates content. They are created with three or more hyphens (---), asterisks (***), or underscores (___).

```markdown
---
```

> Result 

*this is above the line*

---
*this is below the line*


### Additional Features
#### Footnotes
Footnotes are used to provide additional information or references. They are created using [^1] in the text and a corresponding reference section.

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote text.
```

> Result

Here is a footnote reference[^1].

[^1]: This is the footnote text.

#### Definition Lists
Definition lists are used for defining terms. They are created using a term followed by a colon and then the definition.

```markdown
term
: Definition
```
> Result

term
: Definition

## Summary
Markdown is a versatile tool for formatting text with simple syntax. It can be used to create documents that are easy to read and write.
|Feature|Syntax|Description|
|---|---|---|
|**Text Formatting**|`*text*` or `_text_` for italic, `**text**` or `__text__` for bold, `***text***` or `___text___` for bold and italic|Apply formatting to text|
|**Strikethrough**|`~~text~~`|Apply strikethrough formatting|
|**Headings**|`# Heading 1`, `## Heading 2`, `### Heading 3`|Create headings of different levels|
|**Lists**|`-/* item` for unordered; `1. item` for ordered|Create unordered or ordered lists|
|**Task Lists**|`- [ ] Task` for unchecked, `- [x] Task` for checked|Create checklists|
|**Links**|`[text](URL)`|Embed hyperlinks|
|**Images**|`![alt text](URL)`|Embed images|
|**Blockquotes**|`> text`|Highlight text or quotes|
|**Code Blocks**|```` ``` `code` ``` ````|Format code, specify language for syntax highlighting |
|**Tables**|\| Header \| Header \|`<br>`\|--------\|--------\|`<br>`\| Row 1 \| Data \||Create tables with columns and rows|
|**Horizontal Rules**|`---`, `***`, or `___`|Insert horizontal lines|
|**Footnotes**|`[^1]` in text and `[^1]: Footnote text`|Add footnotes|
|**Definition Lists** |`Term`<br>`: Definition`|Define terms and their definitions|

---

*Last updated: 2024-08-30*
