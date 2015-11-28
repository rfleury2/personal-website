---
layout: post
title: "Simple Hover Effect"
permalink: simple-hover-effect
date: 2015-11-27 17:16:12
comments: true
description: "A simple hover effect that can be applied across buttons, links, and other elements to show emphasis in a subtle way."
keywords: ""
categories: ["Quick & Easy"]

tags: ["Quick & Easy", "CSS", "Front End"]

---

This is a quick reference on how to create a simple hover effect on an element.  The objective is to signal to the user in a subtle, yet clear way that the highlighted element is subject to a click.

For example, take a simple list of links 

```html
<ul>
  <li><a href='#'><i class="icon-github"></i> - Github </a></li>
  <li><a href='#'><i class="icon-twitter"></i> - Twitter </a></li>
  <li><a href='#'><i class="icon-linkedin"></i> - LinkedIn</a></li>
</ul>
```

which looks like this:

![Simple List of Link Elements](../images/simple-list-of-link-elements.jpg) 

In order to add a quick hovering effect that is color and style agnostic, here is some simple CSS

```css
li:hover {
  opacity: 0.6;
}
```

that makes the Twitter link dim slightly when the user hovers the cursor over, then returns it to normal when the user exits the clickable area.

![Simple List of Link Elements with Highlight](../images/simple-list-with-highlight.png) 

For a live example of this, go see my ["Contact" section](../#contact)

Adding opacity for simple highlighting is where I typically start because it's easy to implement and looks nice with just about any link or button.  To dive deeper, play with other styling items, such as color, font weight/size, and animations for a more customized look. 

