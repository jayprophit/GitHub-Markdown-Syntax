Here’s a cleaned-up and structured reference guide to **GitHub Markdown Syntax**:

---

# **GitHub Markdown Syntax Guide**

## **Headings**
```markdown
# H1 - Heading Title
## H2 - Subheading
### H3 - Subheading
#### H4 - Subheading
##### H5 - Subheading
###### H6 - Subheading
```

---

## **Horizontal Rules**
```markdown
___
---
***
```

---

## **Emphasis**
```markdown
*Italic* or _Italic_
**Bold** or __Bold__
~~Strikethrough~~
```

---

## **Block Quotes**
```markdown
> Single-level quote  
>> Nested quote  
>>> Deeper nested quote  
```

---

## **Lists**
### **Unordered**
```markdown
- Item 1
  - Sub-item
    - Sub-sub-item
* Item 2
+ Item 3
```

### **Ordered**
```markdown
1. First item
2. Second item
   1. Sub-item
   2. Sub-item
3. Third item
```

---

## **Code**
### **Inline Code**
```markdown
`inline code`
```

### **Block Code**
Indented or fenced:
```markdown
    // Indented code block
    let x = 10;

```
```js
// JavaScript syntax highlighting
const x = 10;
console.log(x);
```

---

## **Tables**
```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| More 1   | More 2   | More 3   |
```

### **Right-Aligned Columns**
```markdown
| Column 1 | Column 2 |
|---------:|---------:|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```

---

## **Links**
```markdown
[Text](http://example.com)
[Text with title](http://example.com "Title")
```

---

## **Images**
```markdown
![Alt text](http://example.com/image.png)
![Alt text with title](http://example.com/image.png "Title")
```

---

## **Plugins**
- **Emojis:**  
  `:smile: :heart: :+1:`
- **Subscript/Superscript:**  
  `H~2~O` or `19^th^`
- **Inserted Text:**  
  `++Inserted text++`
- **Marked Text:**  
  `==Highlighted text==`

---

## **Footnotes**
```markdown
Text with footnote[^1].  
[^1]: Footnote explanation.
```

---

## **Definition Lists**
```markdown
Term 1  
: Definition 1

Term 2  
: Definition 2
```

---

## **Abbreviations**
```markdown
*[HTML]: Hyper Text Markup Language

This is HTML and not xxxHTMLxxx.
```

---

## **Colored Text**
```diff
- Red text
+ Green text
! Orange text
# Gray text
@@ Purple and bold text @@
```

---

## **Latex Color**
```markdown
$${\color{red}Red}$$
$${\color{green}Green}$$
$${\color{blue}Blue}$$
```

---

## **Useful Tips**
1. Use backticks (`) for inline code and fenced code blocks.
2. For custom colors or visuals, embed SVGs or images.
3. Explore GitHub's support for advanced Markdown features like LaTeX and syntax highlighting.

This reference is designed to help you get the most out of GitHub Markdown. Use it to format your README files, documentation, or notes effectively!
