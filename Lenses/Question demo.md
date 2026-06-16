---
id: 8189763f-576e-4f04-a614-4a00c628e386
title: Question and roleplay demo
tags:
  - lens
  - work-in-progress
---

#### Text
content::
This lens demonstrates interactive segments: roleplay, written questions, character limits, voice enforcement, and AI feedback.

#### Roleplay
id:: 313958db-3b65-438f-9725-d9b483977284
content:: You are explaining a new course feature to a collaborator who is skeptical that learners need it.
ai-instructions:: You are a thoughtful collaborator. You are curious but skeptical. Ask practical questions, push back on vague claims, and become more receptive when the learner gives concrete examples.
opening-message:: I'm not sure this course needs another interactive feature. What is this supposed to add?
user-customizable:: true
assessment-instructions:: Evaluate whether the learner clearly explains the purpose of the feature and responds constructively to pushback.
feedback:: true

#### Question
feedback:: true
content:: In one or two sentences, explain what a `#### Question` segment is useful for.
assessment-instructions:: Look for a concise answer that says questions collect learner responses and can be assessed by the AI tutor.
max-chars:: 500

#### Question
feedback:: true
content:: Try answering this one by voice. What would you test before using a roleplay in a real course?
assessment-instructions:: Look for a concrete testing plan, such as checking the opening message, character behavior, scoring rubric, and feedback quality.
enforce-voice:: true
