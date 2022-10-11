# A complete guide for Markdown files

## What is  Markdown?
According to Wikipedia: 
> Markdown is a lightweight markup language for creating formatted text using a plain-text editor. **John Gruber** and **Aaron Swartz** created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.

A markdown file has `.md` extension and we can write and design text or useful information by following the basic syntaxes. It's very popular and easy to use. 

*HTML tags are also supported in markdown.*

---

## Use Case
Markdown syntax is used in various popular places nowadays. You can also make websites using markdown files. This can be done using [docsify](https://docsify.js.org/#/).

Some popular platforms that use Markdown syntaxes and files are as follows - 
- GitHub
- Hashnode
- Dev.to
- Discord and many other platforms.

---

<h2 align="center"><u>Basic Syntaxes</u></h2>

### Headings

**Syntax:**

```
# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6
```
**Output:**

# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6

---

### Code
This can be written in 2 ways - Inline code and normal code

**Syntax for inline code:**
```
`Hello World`
```

**Output:**
`Hello World`

**Syntax for normal code:**

````
```
You can write code here
```
````

**Output:**

```
You can write code here
```

---

## Unordered List of Items

**Syntax:**

```
- Milk
- Tea
- Beer
```

**Output:**

- Milk
- Tea
- Beer

**Syntax:**
> This is an alternate syntax to create unordered list items.

```
* JavaScript
* TypeScript
* ReactJs
```

**Output:**

* JavaScript
* TypeScript
* ReactJs

---

## Ordered List of Items

**Syntax:**

```
1. Eat
1. Walk
1. Sleep
```

**Output:**

1. Eat
2. Walk
3. Sleep

---

## CheckBox Task List

**Syntax:**

```
- [x] Code
- [ ] Review
- [ ] Commit
```

**Output:**


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664210036368/GDes3axlz.png align="left")

---

## Code Block

**Syntax:**

````
```
This is a code block. You can create for code syntaxes like Java, C, C++, JavaScript, HTML, CSS, Bash, and many more.
```
````

**Output:**
```
This is a code block. You can create for code syntaxes like JavaScript, HTML, CSS, Bash, and many more.
```

In order to ***highlight the code***, you can add language name at the start of the backticks as in the following examples.

**Example 1:**

````
```js
function print() {
 console.log('This is is a JavaScript Code Block');
}
```
````

**Output:**
```js
function print() {
 console.log('This is is a JavaScript Code Block');
}
```

**Example 2:**

````
```bash
# This is bash
echo 1
```
````

**Output:**
```bash
# This is bash
echo 1
```

## Strikethrough Text

**Syntax:**

```
~~Work all day without taking rest.~~
```

**Output:**

<s>Work all day without taking rest.</s>

## Blockquote Text

**Syntax:**

```
> “I'm unpredictable, I never know where I'm going until I get there, I'm so random, I'm always growing, learning, changing, I'm never the same person twice. But one thing you can be sure of about me; is I will always do exactly what I want to do.”
```

**Output:**

> “I'm unpredictable, I never know where I'm going until I get there, I'm so random, I'm always growing, learning, changing, I'm never the same person twice. But one thing you can be sure of about me; is I will always do exactly what I want to do.”

## Bold

**Syntax:**

```
**DO NOT UNDERESTIMATE THE POWER OF A PROGRAMMER.**
```

**Output:**

**DO NOT UNDERESTIMATE THE POWER OF A PROGRAMMER.**


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664210778385/XINmqpSv1.png align="left")

## Italic

**Syntax:**

```
*It is Written in Italics*
```

**Output:**

*It is Written in Italics*

## Bold and Italic

**Syntax:**

```
***You Can Combine Bold and Italics***
```

**Output:**

***You Can Combine Bold and Italics***

## Link

**Syntax:**

```
Did you know I have a stress-relieving [Website](https://sukoon-stress-free.netlify.app/)?
```

**Output:**

Did you know I have a stress-relieving [Website](https://sukoon-stress-free.netlify.app/)?

## Image

**Syntax:**

```
![alt text](image)
```

**Output:**

![Getting Started With React.js](https://susmitadey.hashnode.dev/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1655694894367%2FStfc_G8Yo.png%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=1920&q=75)

## Linking an Image

**Syntax:**

```
[![alt text](image)](hyperlink)
```

**Output:**

[![My 3-months Open Source Journey at GSSoC'22](https://susmitadey.hashnode.dev/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1654005117970%2FAGetj2kLw.png%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=1920&q=75)](https://susmitadey.hashnode.dev/my-3-months-open-source-journey-at-gssoc22)

## Emojis

**Syntax:**

```
:mango: :lemon: :man: :car:
```

**Output:**

🥭 🍋 👨 🚗

## Table

**Syntax:**

```
| Fruit | Emoji |
| ----------- | ----------- |
| Mango | :mango: |
| Lemon | :lemon: |
```

**Output:**


| Fruit | Emoji |
| ----------- | ----------- |
| Mango | 🥭 |
| Lemon | 🍋 |

## Table With Alignments

**Syntax:**

```
| Fruit(left)      | Emoji(center) | Taste(right)     |
| :---        |    :----:   |          ---: |
| Mango is the king of Fruits      | :mango:       | Sweet and I love it  |
| Lemon is good for health   | :lemon:        | Sour, mix it in the water     |
```

**Output:**

| Fruit(left)      | Emoji(center) | Taste(right)     |
| :---        |    :----:   |          ---: |
| Mango is the king of Fruits      |  🥭    | Sweet and I love it  |
| Lemon is good for health   |   🍋     | Sour, mix it in the water     |

## Horizontal Line

**Syntax:**

```
---
```

**Output:**

---

## HTML

**Syntax:**

```
<p align="center">
 Yes, you can use allowed raw HTML in mark-down file.
 This is a paragraph aligned in the center.
</p>
```

**Output:**

<p align="center">
 Yes, you can use allowed raw HTML in mark-down file.
 This is a paragraph aligned in the center.
</p>

<details>
    <summary>Heading</summary>
    The details are here.
</details>

## Embed YouTube Video

**Syntax:**

```
[![Alt Text](Thumbnail Image)](YOUTUBE VIDEO LINK)
```

**Output:**

[![Can an AI write programs without errors? | Testing the power of GitHub Copilot robot](http://img.youtube.com/vi/ME3_uchWv8k/0.jpg)](https://www.youtube.com/watch?v=ME3_uchWv8k)

## Embed GIF

**Syntax:**

```
![alt-text](gif link)
```

**Output:**

![gif-embed](https://media3.giphy.com/media/cO2GMlSmqEhWko77KU/giphy.gif)

## Mathematical Expressions

1. **Inline expressions:**

    **Syntax**

    ```plain
    $<<mathematical expression>>$
    ```

    Replace `<<mathematical expression>>` with your expression.

    **Example**

    ```plain
    $\sqrt{3}+1$
    ```

    **Output**

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665295554522/ViK4lERUX.png align="left")

2. **Block Expressions:**

    **Syntax**

    ```plain
    $$<<mathematical expression>>$$
    ```

    **Example**

    ```plain
    $$\sqrt{3}+1$$
    ```

    **Output**

    $$\sqrt{3}+1$$

3. **Mixed Expressions:**

    **Syntax**
    
    ```
    When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
    
    $$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$
    ```

    **Output**
    
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665295889450/ZIcCx4mRH.png align="center")

For more information on how to write mathematical expressions, [visit this page](https://en.wikibooks.org/wiki/LaTeX/Mathematics).

---

## Conclusion
This is a comprehensive list for you all as your guide. Hope all went well and you enjoyed the article.

More powers to you. 💪 

<iframe src="https://giphy.com/embed/287U9qQH5vrKg7KYSH" width="480" height="390" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/jackiejameswhiskey-good-luck-crossing-fingers-cross-287U9qQH5vrKg7KYSH">via GIPHY</a></p>

---

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊




