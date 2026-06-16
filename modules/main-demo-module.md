---
id: f97b4ad0-7fcf-408c-835a-a0aca0be9e9b
slug: demo-basics
title: Demo basics
tags:
  - work-in-progress
---

%% Welcome. A module primarily contains lenses and learning outcomes.

Anything in-between double percentage marks is treated as a comment, and is ignored by our website. %% 

# Lens: Basic Example
id:: 83fac088-1e23-4249-98ce-604b3f7c65d8

#### Text
content::
Here is a basic lens that is defined right within a module file. A Lens is basically a page, by the way. Lenses contain fields like `#### Text` and `#### Chat`.

#### Chat
instructions::
This is a demo chat segment. In real course content, use this field to tell the tutor what the learner just saw and what kind of conversation would be helpful next.


%% We'll now import a lens from an external file instead of defining it inside the module file.%%
# Lens: An imported lens
source:: [[../Lenses/Dummy lens]]

%% The benefit of importing is that we can reuse the same lens in different modules without copying its source text. Importing lenses is usually preferred over defining them directly in the module. %%

%% Instead of importing lenses directly, we can import a learning outcome: %%
## Learning Outcome:
source:: [[../Learning Outcomes/Dummy learning outcome]]

%% That learning outcome then contains its own lenses. 

Having lenses be part of learning outcomes is often what we strive for. But when lenses don't have a learning outcome yet, it's okay to import them directly. 

A module can contain as many learning outcomes and lenses as you want.

Now that we know the st
%%


# Learning Outcome:
source:: [[../Learning Outcomes/Media lens demo|Media lens demo]]

# Learning Outcome:
source:: [[../Learning Outcomes/Learning Outcome Demo|Demo learning outcome]]
## Lens:
source:: [[../Lenses/Article excerpt demo]]
# Lens:
source:: [[../Lenses/video demo]]

# Lens:
source:: [[../Lenses/Article annotation and text collapse demo]]

# Lens:
source:: [[../Lenses/Trial question and roleplay]]

# Lens:
optional:: true
source:: [[../Lenses/Links and cards demo]]

