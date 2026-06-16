---
id: f97b4ad0-7fcf-408c-835a-a0aca0be9e9b
slug: demo-basics
title: Demo basics
tags:
  - work-in-progress
---

# Lens: {--{"author":"Luc's AI","timestamp":1781583702446}@@Start here--}{++{"author":"Luc's AI","timestamp":1781583702446}@@A lens defined inside a module++}
id:: 83fac088-1e23-4249-98ce-604b3f7c65d8
#### Text
content::
{--{"author":"Luc's AI","timestamp":1781583702446}@@This module demos the--}{++{"author":"Luc's AI","timestamp":1781583702446}@@Look, here is a++} basic {--{"author":"Luc's AI","timestamp":1781583702446}@@building blocks for course formatting.

We can use normal wikilinks inside the editor to link to other lenses: [[../Lenses/Article annotation and text collapse demo]]. This does require--}{++{"author":"Luc's AI","timestamp":1781583702446}@@lens that is defined right within a module file.

This is useful for small one-off explanations. The module file owns++} the lens{--{"author":"Luc's AI","timestamp":1781583702446}@@ that you're linking to, to also be part of --}{++{"author":"Luc's AI","timestamp":1781583702446}@@ title, ++}the {--{"author":"Luc's AI","timestamp":1781583702446}@@same module or course.

For a prettier UI, you can use `::card` before --}{++{"author":"Luc's AI","timestamp":1781583702446}@@`id::`, and ++}the {--{"author":"Luc's AI","timestamp":1781583702446}@@wikilink.
::card[[../Lenses/Trial question and roleplay]]

::card[[../Lenses/Kurzgesagt software demo]]--}{++{"author":"Luc's AI","timestamp":1781583702446}@@segments below it.++}

#### Chat
instructions::
This is a demo chat segment. In real course content, use this field to tell the tutor what the learner just saw and what kind of conversation would be helpful next.

# {++{"author":"Luc's AI","timestamp":1781583702446}@@Lens: An imported lens
source:: [[../Lenses/Article annotation and text collapse demo]]

# Lens: Why import lenses?
id:: a04da270-73df-46d1-882f-9efe56c60c7c
#### Text
content::
Look, the previous section imported a lens from an external file instead of defining it here.

The benefit is that we can reuse the same lens in different modules without copying its source text.

# ++}{--{"author":"Luc's AI","timestamp":1781583722343}@@Learning Outcome:
source:: [[../Learning Outcomes/trial for Testing|Demo learning outcome]]

# --}Lens:{++{"author":"Luc's AI","timestamp":1781583702446}@@ Why import a learning outcome?++}
{--{"author":"Luc's AI","timestamp":1781583702446}@@source:: [[../Lenses/Article annotation and text collapse demo]]--}{++{"author":"Luc's AI","timestamp":1781583702446}@@id:: 05221852-cf19-4cd2-a0d0-a372c7c8729e
#### Text
content::
Instead of importing lenses directly, we can import a learning outcome.++}

{--{"author":"Luc's AI","timestamp":1781583702446}@@# Lens:
source:: [[../Lenses/Trial question--}{++{"author":"Luc's AI","timestamp":1781583702446}@@A learning outcome can bundle multiple lenses++} and {--{"author":"Luc's AI","timestamp":1781583702446}@@roleplay]]--}{++{"author":"Luc's AI","timestamp":1781583702446}@@a test. This is useful when several modules should reuse the same little learning sequence.++}{++{"author":"Luc's AI","timestamp":1781583722343}@@

# Learning Outcome:
source:: [[../Learning Outcomes/trial for Testing|Demo learning outcome]]++}

# Lens:
source:: [[../Lenses/Kurzgesagt software demo]]

# Lens:
source:: [[../Lenses/Article excerpt demo]]{++{"author":"Luc's AI","timestamp":1781583702446}@@

# Lens:
optional:: true
source:: [[../Lenses/Links and cards demo]]++}

