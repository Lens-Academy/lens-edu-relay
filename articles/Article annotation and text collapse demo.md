---
title: "Article annotation and text collapse demo"
author: {--{"author":"Luc's AI","timestamp":1781582660901}@@Tim Urban--}{++{"author":"Luc's AI","timestamp":1781582660901}@@Lens Academy++}
published: {--{"author":"Luc's AI","timestamp":1781582660901}@@2015-01-22--}{++{"author":"Luc's AI","timestamp":1781582660901}@@2026-06-16++}
source_url: {--{"author":"Luc's AI","timestamp":1781582660901}@@https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html--}{++{"author":"Luc's AI","timestamp":1781582660901}@@https://editor.lensacademy.org/24abc9c0/Lens-Edu/articles/Article-annotation-and-text-collapse-demo.md++}
tags:
  - work-in-progress
---{--{"author":"Luc's AI","timestamp":1781582660901}@@


--}{++{"author":"Luc's AI","timestamp":1781582660901}@@

++}This article demos how to use `collapse`, `note`, and `footnote` fields inside {--{"author":"Luc's AI","timestamp":1781582660901}@@of articles. You can find the corresponding source code at https://editor.lensacademy.org/24abc9c0/Lens-Edu/articles/Article-annotation-and-text-collapse-demo.md.--}{++{"author":"Luc's AI","timestamp":1781582660901}@@article markdown.++}

See for example this: :collapse[this text will be collapsed by default, but can be expanded by the{--{"author":"Luc's AI","timestamp":1781582660901}@@ user -]--}{++{"author":"Luc's AI","timestamp":1781582660901}@@ user]++} isn't that pretty nice?

We can also collapse entire paragraphs:

:::collapse
This entire paragraph will be collapsed by default,

but can be opened by the {--{"author":"Luc's AI","timestamp":1781582660901}@@user--}{++{"author":"Luc's AI","timestamp":1781582660901}@@user.++}
:::

For footnotes added by the article authors, {--{"author":"Luc's AI","timestamp":1781582660901}@@we --}use markdown footnotes[^1].{--{"author":"Luc's AI","timestamp":1781582660901}@@
--}{++{"author":"Luc's AI","timestamp":1781582660901}@@ ++}We can also add Lens-added {--{"author":"Luc's AI","timestamp":1781582660901}@@footnotes,--}{++{"author":"Luc's AI","timestamp":1781582660901}@@footnotes++} with :footnote[This is a footnote added by Lens].

If we want an always-visible note, we can do :note[This is a note added by Lens] or we can do:
::note[This is a note created with two colons `::`, which means it gets its own line.]

Finally, we can do multi-line notes:
:::note
This is the first line of the note.

This {++{"author":"Luc's AI","timestamp":1781582660901}@@is ++}a second.

This {++{"author":"Luc's AI","timestamp":1781582660901}@@is ++}a third.
This is{--{"author":"Luc's AI","timestamp":1781582660901}@@ not a fourth. It is --}{++{"author":"Luc's AI","timestamp":1781582660901}@@ ++}rendered {--{"author":"Luc's AI","timestamp":1781582660901}@@at--}{++{"author":"Luc's AI","timestamp":1781582660901}@@on++} the same line as the third.
:::

{--{"author":"Luc's AI","timestamp":1781582660901}@@By the way, feel free to put `note` fields inside of `collapse` fields, and to put `footnote` fields in either.

Let us for example write --}{++{"author":"Luc's AI","timestamp":1781582660901}@@You can nest these. For example, here is ++}a collapsed {--{"author":"Luc's AI","timestamp":1781582660901}@@field:--}{++{"author":"Luc's AI","timestamp":1781582660901}@@field++} :collapse[with a note inside: :note[This{--{"author":"Luc's AI","timestamp":1781582660901}@@ is a--} note {--{"author":"Luc's AI","timestamp":1781582660901}@@added by Lens. It could contain a brief explanation of --}{++{"author":"Luc's AI","timestamp":1781582660901}@@explains ++}why we collapsed this bit of text.]]{--{"author":"Luc's AI","timestamp":1781582660901}@@

Similar nested things work for notes, and collapse blocks with two or three colons.--}

[^1]: Hi. This is a footnote added by the author of the article.