---
name: contextual-translator
description: Translate text between languages so it reads like it was written in the target language, not converted into it. Settles who reads it, where they read it, and how formal it should be, then delivers source and target aligned with a note on every adaptation made. Trigger on "translate this", "translate to <language>", "how do you say X in <language>", "put this in <language>", "say this in <language>", "make this sound natural in <language>", "what does this say", or any time the user pastes text in one language and wants it in another.
---

# contextual-translator

Translation judged by the reader on the other end, not by how closely it tracks the source sentence.

## The job

A translation is finished when a native reader of the target language cannot tell it started somewhere else. Word accuracy is the floor, not the goal. What decides whether it lands is who is reading, where they are reading it, and what the text is asking them to do.

## Settle the brief first

Four things decide almost every wording choice:

- **Reader.** Who reads this. Age, and how much they already know about the subject.
- **Surface.** Where it appears. A contract, a support reply, an Instagram caption, a push notification, a slide.
- **Relationship.** Your standing with the reader. Stranger, customer, colleague, friend, someone senior to you.
- **Job.** What the text needs the reader to do or feel. Buy, understand, calm down, act today.

Take whatever the user already gave you. Ask at most two questions to fill the rest, ask them once, in one message, then translate. If the user says "just translate it," assume a general adult reader, neutral formality, and say in one line which assumption you used.

Formality is the question worth spending an ask on when the target language forces the choice on you: Thai, Japanese, Korean, Vietnamese, German, French, Spanish, Arabic and many others make you pick a level before you can write a single sentence, and picking wrong is more visible to a native reader than a clumsy noun.

## Fixed points

These carry across untouched, every time:

- Numbers, dates, quantities, percentages
- Currency and amounts. Never convert a price unless asked, and if you do, say the rate you used
- Personal names, company names, product and feature names
- URLs, email addresses, file paths, code, identifiers
- Legal, medical, financial and safety obligations. Do not soften "must" into "should" because it flows better
- Anything quoted from a third party

If a fixed point genuinely has a standard localized form the reader expects, use it and list the change.

## Write from the meaning

Read the source until you can say what it does without looking at it, then write that in the target language. Writing sentence by sentence off the source is what produces text that is technically correct and audibly foreign.

- **Idioms.** Replace with something a reader of the target language would say unprompted. If nothing fits, drop the figure of speech and keep the feeling. Never carry the image across literally.
- **Formality.** Pick one level and hold it from the first line to the last. Half the translations that feel wrong are not mistranslated, they drift: they open polite and end familiar.
- **Length.** Many languages expand or contract on the way over. If the text lives inside a button, a subject line, a caption, or a character limit, hit the limit and say what you cut to hit it.
- **Humor and wordplay.** Rebuild it, do not translate it. A pun that survives word for word is almost always a pun that died. If it cannot be rebuilt, say so plainly rather than shipping a joke that is not funny.
- **Words with no counterpart.** Keep the source word, gloss it once in the notes, and move on. Do not stretch a paragraph to explain it.
- **Cultural references.** Swap for one the reader will recognize, or make the reference generic. A name nobody in the target market knows costs more than it adds.

## Deliver it side by side

One table, one row per sentence for short text, one row per paragraph for longer text, aligned so any line can be traced.

```
Translation: <source language> to <target language>
Reader: <who, where, how formal>

| <Source language> | <Target language> |
|---|---|
| <line> | <line> |
```

Then, below the table:

- **Adaptations.** One line per change that was a decision rather than a conversion, with the reason. "Kept 'workshop' in English because the audience uses the English word."
- **Register.** One line naming the level you wrote at and who it suits.
- **Did not carry over.** Anything the target language could not hold, said plainly. If nothing was lost, say nothing. Do not pad this list to look thorough.

## The cold read

Before showing anything, read only the target column, with the source out of sight, as if you had never seen the original. If it reads like a translation, it is one. The tells:

- Source word order surviving into a language that does not use it
- Connectives nobody says out loud
- Formality that swings partway through
- An idiom that is technically words in the target language but nothing anyone says

Fix what the cold read catches, then check back against the source that the meaning is still intact, then read cold once more. Two passes, not one.

## Revisions come one note at a time

When the user says a line is off, change that line and every other line with the same problem, and leave the rest alone. Show only the rows that changed and name the rule you adjusted, so the next round starts from a shared understanding instead of a fresh guess. Rewriting the whole thing after one note throws away the parts that already worked.

## Long documents

Work section by section and keep the structure: headings, lists, numbering, tables, emphasis, links. Build a term list on the first pass, every repeated product name, role, and piece of jargon with the target-language wording you settled on, and hold that list for the whole document. A term that changes wording between page two and page nine reads as carelessness, whatever the quality of the prose around it.

## Ship check

- [ ] Reader, surface and formality are settled, from the user or from a stated assumption
- [ ] Every number, name, date, price, URL and code fragment matches the source exactly
- [ ] No idiom was carried across word for word
- [ ] Formality holds steady from the first line to the last
- [ ] The target column reads clean on its own, with the source covered
- [ ] Every real adaptation is listed, and the list contains nothing invented to fill it

## When not to use it

- Certified, sworn, or notarized translation. Those need a credentialed human to sign them.
- Drug dosing, safety procedures, and regulatory filings. Draft if asked, but say clearly that a qualified professional has to review before anyone relies on it.
- A single word or a short phrase with no audience attached. Answer it in a sentence. Do not build a table for four words.
