---
title: Markdown Guide
weight: 5
---

## Introduction

To contribute to PIRL documentation you'll have to use ["markdown"](https://daringfireball.net/projects/markdown/syntax) formatting. Markdown is one of many ways to do documentation. It's probably not the best and certainly not the worst. It's easy to get into and allow for a self-consistent documentation cycle.

Below you'll find some examples of how to use markdown along with our recommendations and best practices. Please use our recommendations when composing PIRL documentation so that it looks well put together with the rest of the content. Also, make sure to take look at [Style Guide]({{< ref "/getting started/how to contribute/style guide" >}}) for additional guidelines regarding content formatting.

## Example Markdown Document

Below is an example document using markdown. This document will be rendered by the software to display as desrcibed.

![Sample](/getting started/how to contribute/markdown guide/images/sample.jpg)

## Basic Markdown Guide

### Main Title

The main document title is displayed at the top of the document using the largest font. In markdown, the title goes at the very top of the document in between the **`---`** section as shown below for this very document.

```
---
title: Markdown Guide
weight: 5
---
```

### Headers

Headers are usually sized from H1 (largest) to H6 (smallest). Markdown is no different. The number representing the size of the header is represented by a **`#`**. A single **`#`** is equivalent to **H1**, two **`##`** is equivalent to **H2**, etc.

```
# This is an H1 tag
## This is an H2 tag
### This is an H3 tag
#### This is an H4 tag
##### This is an H5 tag
###### This is an H6 tag
```

> **PIRL TIP:** The major sections of a document start with **##** or H2

### Emphasis

To *italicize* text, use a single set of asterisks around it. To mark text as **bold**, use a set of two asterisks around it. To strike out some text, use two tildes **(~)** around it.

```
*This text will be italicized*
**This text will be in bold**
~~Did I say something wrong?~~
```

*This text will be italicized*

**This text will be in bold**

~~Did I say something wrong?~~

### Lists

Ordered lists are created by using **1.** for the find item and then incrementing with each subsequent line. Unordered lists are created by using **+**.

```
1. First
2. Second
3. Third

+ Satoshi
+ Vitalik
+ PIRL

1. This is first
  + First thing
2. This is Second
  + Second thing
3. This is Third
  + Third thing
```

1. First
2. Second
3. Third

+ Satoshi
+ Vitalik
+ PIRL

1. This is first
  + First thing
2. This is Second
  + Second thing
3. This is Third
    + Third thing

### Links

Making links simply involves pasting a URL between a set of **()** parenthesis. There are also a couple extra options.

```
This is an [example link](http://example.com/ "With a Title"). It will still work if the only thing included is the link within the parenthesis.
```

This is an [example link](http://example.com/ "With a Title"). It will still work if the only thing included is the link within the parenthesis.

### Images

Linking images is just like links with a **!** exclamation point in front.

```
* ![Magic](/getting started/how to contribute/images/magic.gif?classes=shadow "Magic!")
```

* ![Magic](/getting started/how to contribute/images/magic.gif?classes=shadow "Magic!")

### Code

There are two ways to distinguish code from text, one for inline use and one for blocks of code. To distinguish code `inline` put a set of back ticks around it. To do it as a block of text, put three back ticks at the tom and the bottom.

![Code Block](/getting started/how to contribute/markdown guide/images/code.jpg)

```
This is will be displayed a as a block of code.
More importantly, notice the back ticks at the top and bottom.
```
