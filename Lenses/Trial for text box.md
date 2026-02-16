---
id: <uuid, generate at https://www.uuidgenerator.net/version4>
tags:
  - lens
  - work-in-progress
---

### Page
#### Text
content::
We'll be asking you some questions about X



#### Textbox
max-time:: 3:00
enforce-voice:: true
user-instruction::
What's the difference between x and y?


assessment-prompt::
Give the user a score based on dimensions j and k.

#### Textbox
max-time:: none %% default %%
max-chars:: 1000 %% max length in characters %%
enforce-voice:: false %% default %%
user-instruction::
What's the difference between x and y?


assessment-prompt::
Give the user a score based on dimensions j and k.
### Article: `article title`
source:: [[]]
#### Text
content::
`<introductory text>`

#### Textbox
max-time:: none %% default %%
max-chars:: 1000 %% max length in characters %%
enforce-voice:: false %% default %%
user-instruction::
What's the difference between x and y?

#### Article-excerpt
to:: "`<an exact quote from the article where the exerpt should stop>`"

#### Text
content::
`<prompt the user on how they should interact with the chatbot>`
#### Chat: Discussion on X-Risk
instructions::
TLDR of what the user just read:
`<TLDR text (optional, the bot can see all the text on the page)>`

Discussion topics to explore:
- `<Discussion point 1>`
- `<Discussion point 2>`
- `<Discussion point 3>`
- `<Discussion point 4>`

Ask what they found surprising or new. Check if they can explain `<key concept>` in their own words—it's a key concept.

The user just answered the question: `<tell the chatbot what prompt the user is responding to>`