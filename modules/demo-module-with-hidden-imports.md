---
id: aaed6749-9d79-4345-830e-47b4fa050981
slug: demo-hidden-imports
title: Hidden imports demo
tags:
  - work-in-progress
---

{--{"author":"Luc's AI","timestamp":1781585606945}@@# Lens: Why hidden imports exist
id:: 8144e19b-0c4a-4907-a871-cc1ff0968d68
#### Text
content::
--}{++{"author":"Luc's AI","timestamp":1781585606945}@@%% ++}Sometimes you want a lens to be available for links or cards without showing it as a step that's part of the linear progression for the user.

To hide a lens from the progress bar, import it with `hide:: true`. This must always be accompanied {--{"author":"Luc's AI","timestamp":1781585606945}@@with--}{++{"author":"Luc's AI","timestamp":1781585606945}@@by++} `optional:: {--{"author":"Luc's AI","timestamp":1781585606945}@@true` .--}{++{"author":"Luc's AI","timestamp":1781585606945}@@true`.++}

{--{"author":"Luc's AI","timestamp":1781585606945}@@These cards work because their targets are imported below as--}{++{"author":"Luc's AI","timestamp":1781585606945}@@This module uses dummy imports because++} hidden {--{"author":"Luc's AI","timestamp":1781585606945}@@optional lenses:

::card[[../Lenses/Article annotation and text collapse demo]]

::card[[../Lenses/Trial question and roleplay]]

::card[[../Lenses/video demo]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Article annotation and text collapse demo]]--}{++{"author":"Luc's AI","timestamp":1781585606945}@@imports are the feature being demonstrated. The actual card/link demo lives in the main demo module. %%++}

# Lens:
optional:: true
hide:: true
source:: {--{"author":"Luc's AI","timestamp":1781585606945}@@[[../Lenses/Trial question and roleplay]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/video demo]]--}{++{"author":"Luc's AI","timestamp":1781585606945}@@[[../Lenses/Dummy lens]]++}
