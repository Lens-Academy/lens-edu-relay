---
id: b2c3d4e5-f6a7-8901-bcde-f23456789012
title: Article excerpt demo
---
#### Text
content::
This lens shows two short excerpts from the same article. The processor carries the article source forward, so later `#### Article` segments can omit `source::`.

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

#### Chat
hidePreviousContentFromUser:: false
hidePreviousContentFromTutor:: false
instructions::
This is a demo chat after article excerpts. Ask the learner what they noticed about article metadata, excerpt boundaries, and collapsed skipped text.
