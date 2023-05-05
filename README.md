# Markdown - Notes
This repo contains notes and cheatsheet for markdown.
___

## Headings
\# is used to create heading the number of \# set the level of heading like below.

```markdown
<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
**Output:**
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
---
## Italics
```markdown
<!-- Italics -->
*Italics* - first method.
_Italics_ - second method.
```
**Output:**
1. *Italics* - first method.
1. _Italics_ - second method.

---
## Strong

```markdown
<!-- Strong -->
**Strong** - Method 1
__Strong__ - Method 2
```
**Output:**
1. **Strong** - Method 1
1. __Strong__ - Method 2

---
## Strike Through
```markdown
<!-- Strikethrough -->
~~Strike through~~ - will strike the words.
This is the ~~cancelled word~~.
```
**Output:**
1. ~~Strike through~~ - will strike the words.
1. This is the ~~cancelled word~~.

---
## Horizontal rule
```markdown
---
___
```
**Output:**

---
___
---
## Blockquote
```markdown
<!-- Blockquote -->
> This is a quote.
```
**Output:**
> This is a quote.
---
## Links
```markdown
[Code With Rams](https://codewithrams.com)
[Code With Rams](https://codewithrams.com 
"Code With Rams")
```
**Output:**
1. [Code With Rams](https://codewithrams.com)
1. [Code With Rams](https://codewithrams.com 
"Code With Rams")
---
## Unordered List
```markdown
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
```
**Output:**
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
---
## Ordered List
```markdown
1. Item 1
1. Item 2
1. Item 3
```
**Output:**
1. Item 1
1. Item 2
1. Item 3
---
## Inline Code Block
```markdown
`<p>This is a paragraph</p>`
```
**Output:**

`<p>This is a paragraph</p>`

---

## Images
```markdown
![Markdown logo](https://markdown-here.com/img/icon256.png)
```
**Output:**

![Markdown logo](https://markdown-here.com/img/icon256.png)

---

## Code Blocks

````markdown
<!-- Bash Code Block -->
```bash
npm install
npm start
```
<!-- Javascript Code Block -->
```javascript
function add(num1, num2) {
    return num1 + num2;
}
```
<!-- Python Code Block -->
```python
def add(num1, num2):
    return num1 + num2
```
````


**Output:**
<!-- Bash Code Block -->
```bash
npm install
npm start
```
<!-- Javascript Code Block -->
```javascript
function add(num1, num2) {
    return num1 + num2;
}
```
<!-- Python Code Block -->
```python
def add(num1, num2):
    return num1 + num2
```
---

## Tables
```markdown
| Name   | Email    |
| ------ | -----    |
| Name 1 | Email 1  |
| Name 2 | Email 2  |
```
**Output:**
| Name   | Email    |
| ------ | -----    |
| Name 1 | Email 1  |
| Name 2 | Email 2  |
---

## Task Lists
```markdown
* [x] Task 1
* [x] Task 2
* [ ] Task 3
```
**Output:**
* [x] Task 1
* [x] Task 2
* [ ] Task 3
---
