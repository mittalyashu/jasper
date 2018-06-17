---
layout: post
author: mittalyashu
title: Using a Text Editor
description: When you go to edit a post and see special characters and colours intertwined between the words, those are Markdown shortcuts which tell Jekyll what to do with the words in your document. The biggest benefit of Markdown is that you can quickly apply formatting as you type, without needing to pause.
date: 2018-06-01 17:55:34 +0530
category: getting-started
image: /assets/images/writing.jpg
---

Jekyll uses a language called **Markdown** to format text.

When you go to edit a post and see special characters and colours intertwined between the words, those are Markdown shortcuts which tell Jekyll what to do with the words in your document. The biggest benefit of Markdown is that you can quickly apply formatting as you type, without needing to pause.

Check this post to [learn everything about Markdown](https://blog.codecarrot.net/learning-markdown/).

For now, though, let's run you through some of the basics. You'll want to make sure you're editing this post.

## Headings

To create headings in Markdown you simply prefix the heading text with a pound sign (#) followed by a space. The number of pound signs that you use indicates the importance of the heading.

```
# Level 1 Heading  
## Level 2 Heading  
### Level 3 Heading  
#### Level 4 Heading  
##### Level 5 Heading  
###### Level 6 Heading
```

## Images

Images in Markdown look just the same as links, except they're prefixed with an exclamation mark, like this:

```
![Random image](https://picsum.photos/1200/700/?random)
```

The example above will be converted to the following HTML.

```
<img src="https://picsum.photos/1200/700/?random" alt="Random image">
```

![Random image](https://picsum.photos/1200/700/?random)

_**Important Note:** Jekyll does not have automatic image resizing, so it's always a good idea to make sure your images aren't gigantic files before using them._

## Making lists

Lists in HTML are a formatting nightmare, but in Markdown they become an absolute breeze with just a couple of characters and a bit of smart automation. For numbered lists, just write out the numbers. For bullet lists, just use * or - or +. Like this:

1. Crack the eggs over a bowl
2. Whisk them together
3. Make an omellete

or

* Remember to buy milk
* Feed the cat
* Come up with idea for next story

## Adding quotes

When you want to pull out a particularly good except in the middle of a piece, you can use > at the beginning of a paragraph to turn it into a Blockquote. You might've seen this formatting before in email clients.

> A well placed quote guides a reader through a story, helping them to understand the most important points being made

All themes handles blockquotes slightly differently. Sometimes they'll look better kept shorter, while other times you can quote fairly hefty amounts of text and get away with it. Generally, the safest option is to use blockquotes sparingly.

## Dividing things up

If you're writing a piece in parts and you just feel like you need to divide a couple of sections distinctly from each other, a horizontal rule might be just what you need. Dropping `---` on a new line will create a sleak divider, anywhere you want it.

---

This should get you going with the vast majority of what you need to do in the editor, but if you're still curious about more advanced tips then check out the [Advanced Markdown Guide](https://blog.codecarrot.net/learning-markdown/).