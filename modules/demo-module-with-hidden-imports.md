---
id: aaed6749-9d79-4345-830e-47b4fa050981
slug: demo-hidden-imports
title: Hidden imports demo
tags:
  - work-in-progress
---

%% Sometimes you want a lens to be available for links or cards without showing it as a step that's part of the linear progression for the user.

To hide a lens from the progress bar, import it with `hide:: true`. This must always be accompanied by `optional:: true`.

This module uses dummy imports because hidden imports are the feature being demonstrated. The actual card/link demo lives in the main demo module. %%

# Lens:{--{"author":"Luc's AI","timestamp":1781586074370}@@
source:: [[../Lenses/Dummy lens]]

# Lens:--}{++{"author":"Luc's AI","timestamp":1781586074370}@@ Cards to hidden imports++}
{--{"author":"Luc's AI","timestamp":1781586074370}@@optional:: true--}{++{"author":"Luc's AI","timestamp":1781586074370}@@id:: 1fc78936-050f-403b-911b-a8bfc2e69172++}
{--{"author":"Luc's AI","timestamp":1781586074370}@@hide:: true--}{++{"author":"Luc's AI","timestamp":1781586074370}@@#### Text
content::++}
{--{"author":"Luc's AI","timestamp":1781586074370}@@source:: [[../Lenses/Dummy --}{++{"author":"Luc's AI","timestamp":1781586074370}@@This inline lens links to lenses that are imported below, but hidden from the normal progression.

::card[[../Lenses/Dummy ++}lens]]

{++{"author":"Luc's AI","timestamp":1781586074370}@@::card[[../Lenses/Dummy lens 2]]

::card[[../Lenses/Dummy lens 3]]

++}# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy {--{"author":"Luc's AI","timestamp":1781586074370}@@lens]]--}{++{"author":"Luc's AI","timestamp":1781586074370}@@lens 2]]++}

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy {--{"author":"Luc's AI","timestamp":1781586074370}@@lens]]--}{++{"author":"Luc's AI","timestamp":1781586074370}@@lens 3]]++}