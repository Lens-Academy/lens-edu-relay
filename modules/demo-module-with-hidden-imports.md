---
id: aaed6749-9d79-4345-830e-47b4fa050981
slug: demo-hidden-imports
title: Hidden imports demo
{--{"author":"Luc's AI","timestamp":1781588695006}@@tags:
  - work-in-progress
--}---

%% Sometimes you want a lens to be available for links or cards without showing it as a step that's part of the linear progression for the user.

To hide a lens from the progress bar, import it with `hide:: true`. This must always be accompanied by `optional:: true`.

This module uses dummy imports because hidden imports are the feature being demonstrated. The actual card/link demo lives in the main demo module. %%

# Lens: Cards to hidden imports
id:: 1fc78936-050f-403b-911b-a8bfc2e69172
#### Text
content::
This Lens links to lenses that are imported below, but hidden from the normal progression.

::card[[../Lenses/Dummy lens]]

::card[[../Lenses/Dummy lens 2]]

::card[[../Lenses/Dummy lens 3]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens 2]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens 3]]