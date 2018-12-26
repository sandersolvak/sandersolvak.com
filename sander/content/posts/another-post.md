+++
title = "Learning Markdown"
date = 2018-12-21T23:31:38+02:00
draft = true
tags = ["bar"]
categories = []
+++


# Markdown heading H1
This is a second post. Learning markdown.

## H2 heading
Hello! This word has *emphasis* and this is a **strong** one and this is both ***bold emphasis***.

### H3 level heading - let's make lists!

Ordered list first:

1. first
2. second
  * second A unordered
  * second B unordered
    this should align
3. Third
  1. Three-one
  2. Three-two

Unordered list:

* can use asterisks
- or a minus
+ or a plus

Alright.
Two trailing spaces after "alright" should put this on a new line w/o making a new paragraph.

As opposed to this being a new paragraph.

### Links

I'm an [inline-style link with title](https://www.google.com "Google's Homepage"), where the title is after the url in double quotes.

### Images

Inline-style:
![alt text](https://c1.staticflickr.com/5/4860/44363955080_9ddfb6c32c_o.jpg "View of Tel Aviv from Jaffa")


But how do I have an image with a caption?  
Same image using html `<figure>` tag with `<figcaption>`:
<figure>
  <img src="https://c1.staticflickr.com/5/4860/44363955080_9ddfb6c32c_o.jpg" alt="View of Tel Aviv from Jaffa">
  <figcaption>View of [Tel Aviv](https://www.wikipedia.com) from Jaffa</figcaption>
</figure>



Blockquotes:

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.
