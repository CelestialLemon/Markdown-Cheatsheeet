# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


<!-- Italics
    Wrap the text we want to italicize in * -->
*This is italic text*

<!-- Strong
    Wrap the text in ** to make it strong-->
__This text is strong__

<!-- Strikethrough
    Wrap the text in ~~ to make it strikethrough-->
~~This text is strike through~~

<!-- Horizontal rule
Put 3 minus to draw a horizontal line-->
---

<!-- To escape a special put a \ before-->
\*This text is not italic\*

<!--BLogquote-->
> This is a blog quote

<!--Links. 
Put the text to link in []
Put the link in () next to it
Put a space after the link to put quotes for the link on hover-->
[Homepage](www.gooogle.com "Homepage of google")

<!-- Unordered list 
* to add an item
Put space after * or it will consider as italic
To nest items put a tab and * items-->
* Item 1
* Item 2
    * Item 2.1
        * Item 2.1.1

---

<!-- Ordered list
Put 1. in the beginning-->
**Ordered List**
1. Item 1
1. Item 2
1. Item 3

---

<!-- Inline code block
Wrap text in ` -->

`Console.Writeline("Hello World");`

<!-- Image 
Similar to links but put ! before[] -->

![Logo](https://markdown-here.com/img/icon256.png)

<!-- Github markdown -->

<!-- Code block 
``` for code -->

``` system sleep(5000)```

<!-- if we want to be language specific put language name-->

```cpp
int Add(int a, int b)
{
    return a + b;
}
```

```cs
int Add(const int a, const int b)
{
    return a + b;
}
```
<!-- Tasklist 
[x] for complete
[ ] for incomplete -->
* [x] Task 1
* [x] Task 2
