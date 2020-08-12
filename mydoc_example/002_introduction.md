
# Introduction

Hello World.

---

## Headings

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## New Lines

To write a new line in the same paragraph just add two spaces at the end of the first line.  
Like this.

To write a new line for a new paragraph, just place an empty line between the text lines.

Like this.

To write a new blank line between two paragraphs, use the backslash symbol followed by two spaces.

\  

Like this.

---

## Italic, Bold and Strikethrough

This is how to *use italic* text.
This is how to **use bold** text.  
This is how to ***use both*** at same time.  
This is how to ~~use strikethrough~~ text.  

---

## Superscripts and Subscripts

This is how to use superscripts and subscripts:

H~2~O=water  
2^8^=255.

---

## Blockquotes

> This is a blockquote text  
> with multiples lines

---

## Links

This is a [link to Google](https://www.google.com "cursor text. i.e. https://www.google.com")

You can write simple URL link by itself (without text):
<https://www.google.com>

You can write raw (no link) URL:  
`https://www.google.com`

---

## Images

![image alt text](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "cursor text")

---

## Code and Highlight Sintax

This is `inline code` inside a text.

This is C formated multi-line code:

```c
#include <stdio.h>

int main(void)
{
    printf("Hello World\n.");
    return 0;
}
```

This is Python formated multi-line code:

```python
print("Hello World")
```

This is JSON formated multi-line code:

```json
{
  "firstName": "John",
  "lastName": "Doe",
  "age": 30
}
```

---

## Tables

: Basic Table

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

Align cells to left by using :---  
Align cells to center by using :----:  
Align cell to right by using ---:

\  

: Multiline Table

+------------+-------+---------------------------------------------+
| Date       | ID    | Descripción                                 |
+:==========:+:=====:+:============================================+
| 2017/10/06 | 1     | First line.                                 |
|            |       | Second line.                                |
|            |       | Third line.                                 |
+------------+-------+---------------------------------------------+
| 2017/10/18 | 2     | Blah blah blah.                             |
+------------+-------+---------------------------------------------+
|            |       | OK                                          |
+------------+-------+---------------------------------------------+

Align cells to left by using :===  
Align cells to center by using :====:  
Align cell to right by using ===:

---

## Definition List

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

---

## Checkboxs List

- [ ] First item
- [x] Second item
- [ ] Third item

## Emojis

Emojis can also be used for html  
Check: <https://emojipedia.org>

## Footnotes

Let's try a footnote. [¹]  
Some normal text here.  
And another footnote. [²]

[¹]: This is a footnote.  
[²]: Second footnote
