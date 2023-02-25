<!-- Example of title -->
The exercises in Markdown<!-- omit in toc -->
=======================

<!-- Here comes the table of content -->

Table of Contens:

- [How to do a paragraph?](#how-to-do-a-paragraph)
  - [It is another example of a paragraph](#it-is-another-example-of-a-paragraph)
  - [How to bold a paragraph?](#how-to-bold-a-paragraph)
  - [How to italic a paragraph?](#how-to-italic-a-paragraph)
  - [How to do strikethrough?](#how-to-do-strikethrough)
- [How to do perfect headers?](#how-to-do-perfect-headers)
  - [Header No. 2](#header-no-2)
    - [Header No. 3](#header-no-3)
      - [Header No. 4](#header-no-4)
        - [Header No. 5](#header-no-5)
          - [Header No. 6](#header-no-6)
- [How to do external link?](#how-to-do-external-link)
- [How to link to another file?](#how-to-link-to-another-file)
- [Images](#images)
  - [How to do hover text?](#how-to-do-hover-text)
- [Equation](#equation)
- [How to do a block of code in MD?](#how-to-do-a-block-of-code-in-md)
- [How to do a code highlighting?](#how-to-do-a-code-highlighting)
- [How to do a quote?](#how-to-do-a-quote)
- [How to do bullet list?](#how-to-do-bullet-list)
- [How to do numbered list?](#how-to-do-numbered-list)
- [How to do a table?](#how-to-do-a-table)

<!-- Example of paragraph of text with line break -->

# How to do a paragraph?

This is a paragraph.  

Press space twice and Enrter once to move a paragraph to the next line.  

<!-- Example of another paragraph -->

## It is another example of a paragraph

Below it is another example of a paragraph.  

Example: "Technical Writing jobs involve researching and writing technical content related to a variety of topics, such as engineering, computer software, medical devices, and other specialized technical fields. Technical Writers often work with engineers and scientists to create user manuals, specifications, and documents that clearly and concisely explain complex information. They may also work with marketing and sales teams to create product literature, web content, and other materials that help explain a company’s products and services."  

A pragraph can be long and not broken until the above [method](#how-to-do-a-paragraph) is used.  

<!-- Example of bold -->

## How to bold a paragraph?

**There are two ways to bold a paragraph:**  
1. Write two stars before the text and after it.  
2. Write two underscores before the text and after it.  

__Lets see it in the code.__  

<!-- Example of italic  -->

## How to italic a paragraph?

*There are two ways to italic a paragraph:*  

1. Write one star before the text and after it.  
2. Write one underscore before the text and after it.  

_Lets see it in the code._  

## How to do strikethrough?

Write two tildes to strikethrough the text.  

~~Strikethrough~~  

<!-- Example of headers -->

# How to do perfect headers?

 The hush and the space tells the MD that it's a header.  
Write multiples of hush (from 2-6) before the text to create headlines.  

 ## Header No. 2
 ### Header No. 3
 #### Header No. 4
 ##### Header No. 5
 ###### Header No. 6  
 
"Hush" x2 to 6.  

<!-- Example of external link -->

# How to do external link?

It is example of external link - Google search.  

[Webpage in localization](https://google.com/)  

Write "Webpage in localization" between square brackets and paste url (the address of a web page) between round brackets to do external link.  

<!-- Example of link to another file -->

# How to link to another file?

It is example of link to another file named "Reference".

[Reference](Reference.md)  

Write "Reference" between square brackets and name of the file with extension between round brackets to do link to another file.  

<!-- Example of an image -->

# Images

It is example of image from the folder.  

This image shows icon of fox around blue ball.  

Write exclamation mark, square brackets with text about image and location of the image between round brackets.  
To do hover text write text between quotation marks.  
![SVG image from Internet](./images/Firefox.jpg "Firefox logo")  

It is example of image from the Internet.

This image shows black dog.  

<!--Check the source of this image-->

When using an image from the internet instead of a file from computers folder, we use url.  

![Dog](https://picsum.photos/id/237/200/300 "Black puppy")  

<!-- Example of an image with hover text -->

## How to do hover text?

To do hover text write text between quotation marks.  

![Cats](https://upload.wikimedia.org/wikipedia/commons/3/32/Collage_of_Six_Cats-03.JPG "Six cats")  

<!-- Example of equation or inline code -->

# Equation

```
2x-10=12
```

    2+2=4

Write apostrophe three times before and after code. 
Another way to do block of code is adding 4 spaces before code.  

<!-- Example of a block of code -->

# How to do a block of code in MD?

This is a JS example.

```javascript
const test = "Hello";
console.log(test);
```

    const test = "Hello";console.log(test);

<!-- Example of code highlighting -->

# How to do a code highlighting?

```javascript
function test() {
console.log("look ma`, no spaces");
}
```

<!-- Example of quote -->

# How to do a quote?

Write close angle bracket before quote to do one.  

RM said:  
> I live so I love.

<!-- Example of bullet list -->

# How to do bullet list?

Write star and space to do bullet list.  

This is bullet list:  
* Milk  
* Bread  
* Eggs  
* Chocolate  

<!-- Example of numbered list -->

# How to do numbered list?

Write nuber and dot to do numbered list.  

This is numbered list:  
1. Plan  
2. Buy  
3. Pack up  
4. Go on holidays  

<!-- Example of table -->

# How to do a table?

Use vertical bars and spaces to do columns in the table.  
Use colons to adjust the text.

| Column1   | Column 2    | Column 3  |
| :-------- | :---------: | --------: |
| Row 1     | Row 2       | Row 3     |
| Row I     | Row II      | Row III   |
| [Google Browser](https://www.google.com/) | ``` <p>I really like using Markdown.</p> ``` | **This is ex. of bold text** |

<!-- Paragraph after table -->
`
The text after the table must have one empty line.
