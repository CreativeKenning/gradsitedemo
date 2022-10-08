---
layout: post
title: Mapping Discord's Darkside, Distributed Hate-Networks on Disboard
description: An exploration of Discord's technoculture using data collected from the third-party search board, Disboard.
---
Example modified from [here](http://www.unexpected-vortices.com/sw/rippledoc/quick-markdown-example.html){:target="_blank"}.

h1 Header Mapping Discord's Darkside: Distribiuted Hate-Networks on Disboard
============

![lich](/gradsitedemo/assets/images/lich.png "Playful Pedagogy")

In the early parts of 2021, I had a problem. I was looking to make an argument about connectivity (following Van Djick) and non-connective messaging apps ala Discord. However, as an early Grad student with little IRB experience, I had no way of actually studying Discord's communities. However, in searching for information on Discord, I stumbled on the technically-unaffilaited third-party invite hosting and search site, Disboard. A cursory search revealed serious, as of yet unaddressed problems with Discord's technoculture: specifically in their continued networking of white-supremacist and hate groups. With technical guidance from my co-author PS Berge, we scraped Disboard


h1 Abstract
>Discord, a popular community chat application, has rhetorically distanced itself from its associations with white supremacist content through a public commitment to proactive moderation. However, Discord relies extensively on third-party services (like bots and server bulletins), which have been overlooked in their role in facilitating hateful networks. This study notes how Discord offloads searchability to server bulletin sites like Disboard, to deleterious effect. This study involves two parts: (1) we use critical technoculture discourse analysis to examine Discord’s blogs, policies, and application programming interface and (2) we present data scraped from 2741 Discord servers listed on Disboard, revealing networks of hateful and white supremacist communities that openly use “edgy,” raiding-oriented, and toxic messaging. These servers exploit Discord’s moderation tools and affordances to proliferate within Discord’s distributed ecology. We argue that Discord’s policies fail to address its reliance on unmoderated third-party services or the networked practices of its toxic communities.



H2 Header
------------

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it by specifying the languagae after the start of a block (e.g. `~~~python`) which would look like :

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print(i)
~~~

### An H3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a footnote [^1].

[^1]: Some footnote text.

Tables can look like this:

| Header 1 | Header 2                   | Header 3 |
|:--------:|:--------------------------:|:--------:|
| data1a   | Data is longer than header | 1        |
| d1b      | add a cell                 |          |
| lorem    | ipsum                      | 3        |
|          | empty outside cells        |          |
| skip     |                            | 5        |
| six      | Morbi purus                | 6        |


A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.

oranges
  : Citrus!

tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term and  its definition to spread things out more.)

Here's a "line block" (note how whitespace is honored):

| Line one
|   Line too
| Line tree

and images can be specified like so:

![example image](https://images.unsplash.com/photo-1488190211105-8b0e65b80b4e?w=300&h=300&fit=crop "An exemplary image")

Inline math equation: $\omega = d\phi / dt$. Display
math should get its own line like so:

$$I = \int \rho R^{2} dV$$
