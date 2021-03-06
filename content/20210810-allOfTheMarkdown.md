---
title: "All of the Markdown"
image: "images/posts/20210810-allOfTheMarkdown/1.webp"
date: 2021-08-10T17:55:39+02:00
draft: false
tags: ["post"]
---

# Heading
This is a sample Post copy 2

> The secret to creativity is knowing how to hide your sources. 
> &mdash; <cite>[Albert Einstein][1]</cite>

[1]: http://www.quotedb.com/quotes/2112


![image alt text](/images/posts/20210810-allOfTheMarkdown/1.webp)

Lorem ipsum dolor sit amet, consectetur...

## What is Lorem Ipsum?
In mollis cursus ligula, et venenatis neque maximus ut...

Vivamus ut tincidunt urna. Nam eu mollis dolor...

## In mollis cursus ligula
Etiam et ligula sit amet urna aliquam suscipit...

- Cras dui nulla,
- ornare eget fermentum quis, 
- accumsan vitae purus.

Nam eget pharetra arcu. Cras dui nulla, ornare eget...

### Nullam a risus maximus
Fusce facilisis non ante quis blandit...

### Donec vel accumsan justo
Maecenas eu libero ac justo tempor pellentesque...

---

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

---



**This is bold text**

*This text is italicized*

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

---

Quoting text:

In the words of Abraham Lincoln:

> Pardon my French

---

Quoting code:

Some basic Git commands are:
```
git status
git add
git commit
```

---

Links:

This site was built using [GitHub Pages](https://pages.github.com/).

---

Lists:

- George Washington
- John Adams
- Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

---

Nested Lists:

1. First list item
   - First nested list item
     - Second nested list item

---

Task lists:

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

---

Ignoring Markdown formatting:

Let's rename \*our-new-project\* to \*our-old-project\*.

---

Creating a table:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |

---

1. First ordered list item
2. Another item
??????* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
??????1. Ordered sub-list
4. And another item.

?????????You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

?????????To have a line break without a paragraph, you will need to use two trailing spaces.??????
?????????Note that this line is separate, but within the same paragraph.??????
?????????(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

---

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

---

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

---

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

var s = "JavaScript syntax highlighting";
alert(s);

s = "Python syntax highlighting"
print s

No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a <b>tag</b>.

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

Three or more...

---

Hyphens

***

Asterisks

___

Underscores