---
title: "Article annotation and text collapse demo"
author: Tim Urban
published: 2015-01-22
source_url: https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html
tags:
  - work-in-progress
---


This article demos how to use `collapse`, `note`, and `footnote` fields inside of articles. You can find the corresponding source code at https://editor.lensacademy.org/24abc9c0/Lens-Edu/articles/Article-annotation-and-text-collapse-demo.md.

See for example this: :collapse[this text will be collapsed by default, but can be expanded by the user -] isn't that pretty nice?

We can also collapse entire paragraphs:

:::collapse
This entire paragraph will be collapsed by default,

but can be opened by the user
:::

For footnotes added by the article authors, we use markdown footnotes[^1].
We can also add Lens-added footnotes, with :footnote[This is a footnote added by Lens].

If we want an always-visible note, we can do :note[This is a note added by Lens] or we can do:
::note[This is a note created with two colons `::`, which means it gets its own line.]

Finally, we can do multi-line notes:
:::note
This is the first line of the note.

This a second.

This a third.
This is not a fourth. It is rendered at the same line as the third.
:::

By the way, feel free to put `note` fields inside of `collapse` fields, and to put `footnote` fields in either.

Let us for example write a collapsed field: :collapse[with a note inside :note[This is a note added by Lens. It could contain a brief explanation of why we collapsed this bit of text.]]

Similar nested things work for notes, and collapse blocks with two or three colons.

[^1]: Hi. This is a footnote added by the author of the article.