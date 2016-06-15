---
layout: article
title: Markdown Basics 03
excerpt: Links and image links
category: markdown
---

---

### Inline Links

The simplest way to include an html link is to either just type the URL, or place it in angled brackets:

`http://www.google.com` => http://www.google.com

`<http://www.google.com>` => <http://www.google.com>

If you want the text to be different from the link, put the link text first in square brackets, and the link url right after it in parentheses.  You can put an optional alternate text (for screen readers, also shows up as tooltip) in double quotes inside the url parentheses:

`[Google](http://www.google.com "google.com")` => [Google](http://www.google.com "google.com")

---

### Reference Style Links

To clean up the look of your code, you can assign URLs to variables, and put them at the bottom of your page, and use the variables instead.  Note that the variable assignment lines at the end are not rendered if they are separated from the rest of your code.

~~~
* [Nodeschool.io][ns]
* [Github][gh]

[ns]:http://nodeschool.io
[gh]:<http://github.com> "github"
~~~

* [Nodeschool.io][ns]
* [Github][gh]

[ns]:http://nodeschool.io
[gh]:<http://github.com> "github"

---

### Image Links

Image links work just like regular links, but have the following format:
`![alt text](link)`

The link can be either a path, or a URL.  You can also use the reference style with image links:

~~~
![Baron Blade][bb]

[bb]: /images/baronblade.jpg
~~~

![Baron Blade][bb]

[bb]: {{site.baseurl}}/images/baronblade.jpg

---
