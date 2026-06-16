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

# Lens:
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]

# Lens:
optional:: true
hide:: true
source:: [[../Lenses/Dummy lens]]