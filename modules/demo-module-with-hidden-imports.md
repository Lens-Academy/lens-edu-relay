---
id: aaed6749-9d79-4345-830e-47b4fa050981
slug: demo-hidden-imports
title: Hidden imports demo
tags:
  - work-in-progress
---

# Lens: Why hidden imports exist
id:: 8144e19b-0c4a-4907-a871-cc1ff0968d68
#### Text
content::
Sometimes you want a lens to be available for links or cards without showing it as a normal required step.

Use `hide:: true` together with `optional:: true` on the imported lens. Hidden required lenses are invalid, because learners could not complete them.

These cards work because their targets are imported below as hidden optional lenses:

::card[[../Lenses/Article annotation and text collapse demo]]

::card[[../Lenses/Trial question and roleplay]]

::card[[../Lenses/video demo]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Article annotation and text collapse demo]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Trial question and roleplay]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/video demo]]
