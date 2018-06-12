---
title: Writing with Markdown
date: '2018-06-12T04:27:12-06:00'
image: /img/uploads/markdown.png
showonlyimage: true
---
Markdown is a common plain text markup format which aims to be human-readable without any processing required. Its format is similar to conventions often found in plain text emails.

Following are some examples of common usage. You can also view the [original syntax reference][daring] on John Gruber's blog.

[daring]: https://daringfireball.net/projects/markdown/syntax "John Gruber's Markdown reference"

## Headers

To make a header, add one or more pound signs to the start of the line.

```markdown
# First level, usually one per page
## second level
...
###### all the way to sixth level
```

## Text formatting

You have several options---_italic_, __bold__, even ~~strikethrough~~:
```markdown
*italic*           OR  _italic_
**bold**           OR  __bold__
~~strikethrough~~
```

## Paragraphs

Couldn't be simpler: just a line
or
multiple lines of text surrounded by a blank line on
top and on bottom.

## Quotations

Just write a `> ` at the beginning of the paragraph being quoted, just like in plain text emails.

> Randy Josleyn is a super cool dude. -- Randy

> > Are you sure? -- Steve

```markdown
> this is what they look like in markdown.

> > They can be nested, too.
```

## Links

Links are simple enough. They can be either inline or footnoted.

This is an [inline link](https://en.wikipedia.org/wiki/Markdown#Example). They can be harder to read, so it's prudent to place them instead as footnotes, like [this][abc].

[abc]: https://en.wikipedia.org/wiki/Markdown "add hover text"

```markdown
What an [inline link](https://en.wikipedia.org/wiki/Markdown#Example)
looks like. And a [footnoted][abc] one, too.

[abc]: www.josleyn.com "Randy's website"
