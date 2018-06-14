---
title: Writing with Markdown
date: '2018-06-14T01:05:12-06:00'
image: /img/uploads/markdown.png
showonlyimage: false
---
Markdown is a common plain text markup format which aims to be human-readable without any processing required. Its format is similar to conventions often found in plain text emails.
<!--more-->

Following are some examples of common usage. You can also view the [original syntax reference](https://daringfireball.net/projects/markdown/syntax "John Gruber's Markdown reference") on John Gruber's blog.



## Text-level formatting

### Font style

You have several options---_italic_, **bold**, even ~~strikethrough~~:

```markdown
*italic*           OR  _italic_
**bold**           OR  __bold__
~~strikethrough~~
```

### Links

Links are simple enough. They can be either inline or footnoted.
This is an [inline link](https://en.wikipedia.org/wiki/Markdown#Example). They can be harder to read, so it's prudent to place them instead as footnotes, like [this](https://en.wikipedia.org/wiki/Markdown "add hover text").

```markdown
What an [inline link](https://en.wikipedia.org/wiki/Markdown#Example)
looks like. And a [footnoted][abc] one, too.

[abc]: www.josleyn.com "Randy's website"
```

### Code, &c.

Code can be indicated with `back ticks (grave marks)` around the text. `\`back ticks\`\`

## Paragraph-level formatting

### Headers

To make a header, add one or more pound signs to the start of the line.

```markdown
# First level, usually one per page
## second level
...
###### all the way to sixth level
```


### Quotations

Just write a `>` at the beginning of the paragraph being quoted, just like in plain text emails.

> Randy Josleyn is a super cool dude. -- Randy
>
> > Are you sure? -- Steve

```markdown
> this is what they look like in markdown.

> > They can be nested, too.
```

### Code blocks
These are paragraphs of code surrounded by (at least) three back ticks on a line above and below, and they look like this in markdown:

````java
```
thisIs(a) {
blockOfCode();
}
```
````
Formatting in a code block remains unchanged; line breaks
will not be added, so whatever you type in a code block is what you get.

## For the visual learners

If you want to get this information in video format, you can check out this video on YouTube that explains it pretty clearly. 

{{< youtube 2JE66WFpaII >}}
