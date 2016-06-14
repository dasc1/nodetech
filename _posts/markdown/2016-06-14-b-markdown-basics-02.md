---
layout: article
title: Markdown Basics 02
excerpt: Lists (unordered, ordered, nested)
category: markdown
---

---

### Unordered Lists

Simply prefix consecutive lines with asterisks or dashes to create unordered lists.  There must be a space after the asterisk or dash.

Try to use the same symbol for each line of a list - this will guarantee that the renderer will not place the items in separate lists.

~~~
* An Item
* Another Item
~~~

* An Item
* Another Item

---

### Ordered lists

Prefix lines with a number, followed by a period, followed by a space to create an ordered list item. 

In __kramdown__, numbered lists always start with 1 regardless of the first number.
In other markdowns sometimes the first number is used.

~~~
99. One
938. Two
1. Three
~~~

99. One
938. Two
1. Three

---

### Nested lists

To start a nesting within a list, simply indent the nested list by three or more spaces.  This works with ordered and unordered lists.

~~~
1. One
2. Two
   1. Two point one
   2. Two point two
3. Three
   * Three A
   * Three B
~~~

1. One
2. Two
   1. Two point one
   2. Two point two
3. Three
   * Three A
   * Three B

---

