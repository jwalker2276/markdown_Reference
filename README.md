# Markdown Quick Reference

# Paragraphs

Cillum ad esse laborum aute mollit voluptate velit consequat consectetur.

**Space between paragraphs**

Nulla culpa sint adipisicing nisi consequat cupidatat dolor incididunt deserunt commodo cillum. Proident minim veniam quis laborum consequat commodo cupidatat sunt duis anim aute reprehenderit. Irure sit cupidatat cupidatat ad irure fugiat adipisicing dolore esse ad irure laborum ullamco.

# Text Decoration

```md
**Bold**

_Italic_

~~Strikethrough~~
```

**Bold**

_Italic_

~~Strikethrough~~

# Headings

```md
# H1

## H2

### H3

#### H4
```

# Links

### A basic link:

```js
<https://www.linkedin.com/in/jordan-walker-85246458/>
```

<https://www.linkedin.com/in/jordan-walker-85246458/>

### Text link:

```js
[My Linkedin Profile](https://www.linkedin.com/in/jordan-walker-85246458/)
```

[My Linkedin Profile](https://www.linkedin.com/in/jordan-walker-85246458/)

### Keys in paragraphs:

```js
Make sure you check out my linkedin [profile][1].

[1]: https://www.linkedin.com/in/jordan-walker-85246458/
```

Make sure you check out my linkedin [profile][1].

[1]: https://www.linkedin.com/in/jordan-walker-85246458/

# Images

```js
// Image
![alt](link)

// Image with separte key
![alt][key]

[key]: link to picture

// HTML
<img src="source.jpg" width="50px" height="50px" alt="alt text">
```

# Code Blocks

### Here is a code block:

````js
// Wrap codeblock in ```language
const x = 50000;
let y = 3;
// End codeblock in ```
````

### Write code in a sentence:

```js
// Wrap the code in ` `
Did you try `x += y` ?
```

### Show code diff:

````js
// Wrap the diff in ```diff
// Show error with - code
// Show correction with + code
````

```diff
let x = 1000;
- let y = 2000;
+ let y = 3000;
```

# Lists

### Unordered list

```md
+ item
+ item
+ item
```

+ item
+ item
+ item

### Ordered list

```md
1. first
1. second
1. third
```

1. first
2. second
3. third

### Nested list

```md
+ item
  * item
    * item
+ item
  * item
```

+ item
  * item
    * item
+ item
  * item

# Line Breaks

```md
// Words don't follow each other because of <br>
Sentence<br>
Sentence
```
Sentence<br>
Sentence

# Horizontal Rules

```md
Words
// space
--- //hr
// space
More Words
```

Words

---

More Words

# Block Quotes

```md
> "Every great developer you know got there by solving problems they were unqualified to solve until they actually did it." 
> 
> Patrick McKenzie
```

> "Every great developer you know got there by solving problems they were unqualified to solve until they actually did it."
>
> Patrick McKenzie

# Tables

```md
|Col1|Col2|
|:--:|---:|
|Cell|Cell|
|Cell|Cell|
```

| Col1  | Col2 |
| :---: | ---: |
| Cell  | Cell |
| Cell  | Cell |

# Check boxes

```md
**Todo**
* [ ] First
* [x] Second
* [ ] Last
```

**Todo**
* [ ] First
* [x] Second
* [ ] Last

