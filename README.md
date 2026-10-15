<p align="center"><a href="https://loop.sv-academy.org"><img src="https://raw.githubusercontent.com/sva-admin/claude-skills/main/assets/sv-academy-512.png" width="96" alt="Silicon Valley Academy"/></a></p>

# contextual-translator

Translation that doesn't sound translated. It settles who is reading, where they are reading it, and how formal it needs to be, then writes the target language from the meaning instead of from the sentence.

> **Credit**
>
> Inspired by a Claude skill named `contextual-translator` that circulates inside an unattributed skills bundle carrying no author, no repository, and no license. This is an independent SV Academy implementation, written clean-room. See [Credit](#credit).

## What it does

- **Asks the two questions that decide the wording.** Who reads it and how formal it should be. Everything else follows from those. A refund policy for customers in their twenties on Instagram and the same policy in a contract are not the same text in Thai, Japanese, or German, no matter how identical they look in English.
- **Locks the things that must not move.** Numbers, dates, prices, names, product names, URLs, code, and legal obligations come across exactly. "Must" does not become "should" because "should" reads more smoothly.
- **Rebuilds idioms instead of carrying them.** Anything with no counterpart gets swapped for what a native reader would actually say, or dropped in favor of the feeling underneath it. Puns get rebuilt or declared dead, never shipped word for word.
- **Holds one formality level end to end.** Most translations that feel off are not mistranslated, they drift: polite at the top, familiar by the bottom.
- **Shows both columns and its own working.** Source and target aligned line by line, then a list of every adaptation with the reason, the register it was written at, and anything the target language could not hold.
- **Reads the target cold before showing it.** With the source covered, forgetting the original existed. If it still reads like a translation, it goes back.

## Try it

Paste this into Claude Code:

```
Install the skill from https://github.com/sva-admin/contextual-translator, then translate our refund policy into Thai for customers in their twenties reading it on Instagram.
```

## Use it

```
Translate this into Japanese for a client I've never met, formal
Say this in Spanish the way a friend would text it
Put our onboarding email into German, it has to fit the same subject line length
This arrived in Thai, what does it actually say and how blunt is it
Translate the whole product page into French and keep the headings and links intact
```

Send one note back when a line is off, not five. The skill fixes that line and every line with the same problem, shows only what changed, and leaves the rest alone.

## Learn it free, step by step

[Translate without the translated feel](https://loop.sv-academy.org/articles/translate-without-the-accent)

Free tutorials on building with Claude Code: skills, subagents, and the workflows that hold them together.

## Credit

The idea is not ours. A skill named `contextual-translator` has been passed around inside a zipped Claude Code skills bundle, and that is where we first saw this job framed well enough to teach: translate the meaning, not the sentence, and put both languages in front of the reader.

The bundle names no author, links to no repository, and states no license. We could not find anyone to credit by name, and an unclear license means we do not republish someone else's text. So we read the original once to understand the job it does, closed it, and wrote this SKILL.md ourselves. None of that skill's wording, structure, or examples appear here.

If you wrote the original, open an issue. We will credit you properly in this README, by name and link.

## License

MIT. See [LICENSE](LICENSE). The MIT grant covers the SV Academy text in this repository.

---

[All SV Academy Claude skills](https://github.com/sva-admin/claude-skills) | [sv-academy.org](https://sv-academy.org)

SV Academy is the education brand of [Silicon Valley Innovation](https://svinnovation.com), a Bangkok software and AI company that can build this for your business.
