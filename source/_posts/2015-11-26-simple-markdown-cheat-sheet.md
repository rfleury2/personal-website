---
layout: post
title: "A Simple Markdown Cheat Sheet"
permalink: simple-markdown-cheat-sheet
date: 2015-11-26 15:39:10
comments: true
description: ""
keywords: ""
categories:

tags:

---

In order to cut down on the amount of time fiddling with Markdown and concentrate on the content of this blog, I needed to make a **simple reference where I could pick and choose individual components in a clean and fast way**

So here it is:

# Markdown Cheat Sheet
---
# Heading 1
## Heading 2
### Heading 3 
#### Heading 4
##### Heading 5
###### Heading 6

``` 
# Heading 1
## Heading 2
### Heading 3 
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Alternate syntax -->
Alternate Heading 1
=============

Alternate Heading 2
-------------
```

### Text decoration
---
*This is italic*

_This is also italic_

```
*This is italic*

_This is also italic_
```

**This is bold**

__This is also bold__


```
**This is bold**

__This is also bold__
```

[This is a link](http://www.wikipedia.org)

```
[This is a link](http://www.wikipedia.org)
```

### Code Snippets
---
####Inline Code
This is how `inline_code()` is displayed (backticks).

This is how \`inline_code()\` is displayed (backticks).

####Code Block
Display blocks of code by wrapping the code in three backticks (\`\`\`):

\`\`\`
	code.run()
\`\`\`


```
code.run()
```

Additionally, you can specify a language inside the block by opening it with the syntax:

\`\`\`ruby
	
User.first.include(:posts)

\`\`\`

```ruby
User.first.include(:posts)
```


### Lists
---
#### Unordered Lists
- Unordered list items are prepended by '-'
+ You can also use the '+' syntax
* You can also use the '*' syntax

```
- Unordered list items are prepended by '-'
+ You can also use the '+' syntax
* You can also use the '*' syntax
```

#### Ordered Lists
1. Start it with a number
2. Continue along
7. The number itself doesn't matter, just the order

```
1. Start it with a number
2. Continue along
7. The number itself doesn't matter, just the order
```

### Tables
---
id | name | email
--- | --- | ---
1 | George | george@beatles.co.uk
2 | Ringo | ringo@beatles.co.uk


```
id | name | email
--- | --- | ---
1 | George | george@beatles.co.uk
2 | Ringo | ringo@beatles.co.uk
```

### Miscellaneous
---

#### Images
![Alternate Text](http://lorempixel.com/200/150 "image title")

```
![Alternate Text](http://lorempixel.com/200/150 "image title")
```

#### Horizontal Rule

text above the rule
***
text below the rule


```
text above the rule
***
text below the rule

<!-- Alternate syntax -->
* * *
- - -
---
```




