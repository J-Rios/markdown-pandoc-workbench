# 4. Text Format

This section covers the different formats that can be applied to a markdown text.

## 4.1. Italic, Bold and Strikethrough

This is how to *use italic* text.  
This is how to **use bold** text.  
This is how to ***use both*** at same time.  
This is how to ~~use strikethrough~~ text.  

## 4.2. Superscripts and Subscripts

This is how to use superscripts and subscripts:

H~2~O=water  
2^8^=255.

## 4.3. Blockquotes

> This is a blockquote text  
> with multiples lines

\newpage

## 4.4. Code and Highlight Sintax

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

## 4.5. Footnotes

Let's try a footnote. [¹]

Some normal text here.

And another footnote. [²]

[¹]: This is a footnote.

[²]: Second footnote
