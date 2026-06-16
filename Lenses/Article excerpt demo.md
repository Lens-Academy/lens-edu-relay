---
id: b2c3d4e5-f6a7-8901-bcde-f23456789012
title: Article excerpt demo
---
#### Text
content::
This lens shows {--{"author":"Luc's AI","timestamp":1781583583498}@@two--}{++{"author":"Luc's AI","timestamp":1781583583498}@@three++} short excerpts from the same article. The processor carries the article source forward, so later `#### Article` segments can omit `source::`.

#### Article
source:: [[../articles/wikipedia-existential-risk-from-ai]]
from:: "**Existential risk from artificial intelligence**"
to:: "irreversible [global catastrophe]"

#### Text
content::
The UI can show collapsed content before or after excerpts when the source article has skipped material.

#### Article
from:: "> The upshot is simply a question of time"
to:: "moment question."

{++{"author":"Luc's AI","timestamp":1781583561409}@@%% You can also add article excerpts without text in between. %%
++}#### {--{"author":"Luc's AI","timestamp":1781583561409}@@Chat--}{++{"author":"Luc's AI","timestamp":1781583561409}@@Article++}
{--{"author":"Luc's AI","timestamp":1781583561409}@@hidePreviousContentFromUser:: false--}{++{"author":"Luc's AI","timestamp":1781583561409}@@from:: "In 1951, foundational computer scientist"++}
{--{"author":"Luc's AI","timestamp":1781583561409}@@hidePreviousContentFromTutor:: false--}{++{"author":"Luc's AI","timestamp":1781583561409}@@to:: "take control"

#### Chat++}
instructions::
This is a demo chat after article excerpts. Ask the learner what they noticed about article metadata, excerpt boundaries, and collapsed skipped text.
