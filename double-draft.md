---
name: double-draft
description: >-
  Use when the user wants an existing piece of writing made clearer and easier
  to read through a series of reviewed drafts, without losing any fact or
  changing the author's meaning or voice. Mainly for technical documentation and
  READMEs, and especially useful when facts and claims must stay accurate. Also
  works for articles, posts, emails, essays, bios, and PR descriptions.
---
# Double Draft

Improve a piece of writing through five numbered drafts. Each builds on the last, is saved separately, and is checked against the original. The goal is writing that a reader understands faster and trusts more, saying the same things in the author's voice. Shorter is welcome, but clarity comes first.

## Rules for every draft

- Save each draft as a new file (`<name>-v1.md`, `<name>-v2.md`, ...). Never edit the original or an earlier draft.
- Never send, post, publish, or submit the writing. The user does that. If the destination needs a command or form, give the user the steps.
- Keep names, quotes, numbers, dates, links, code, commands, and titles exact unless the user says otherwise. Readers and other pages may quote them.
- Never invent facts, quotes, examples, or sources. Any new claim, or any change in meaning or tone, needs the user's approval. List these separately in each report.
- Keep the author's voice: their person, tense, formality, and characteristic word choices.
- Follow the destination's conventions (README, docs page, PR description, email, post) and the user's known style preferences, such as short paragraphs separated by blank lines or a license line or demo link on its own line.
- For technical writing: use one term for each thing everywhere, define a term the first time it appears, number steps in the order they happen with one action each, and put code, commands, paths, and settings in code formatting.
- Track words and reading time (words ÷ 230 per minute, an estimate) per section as a check, not a target. Never cut words a reader needs. If the destination has a character limit, count characters too.
- Save drafts as plain `.md`. Finalize files before uploading. Upload each file once, to a new folder per draft. Don't trash older uploads without the user's direct OK.
- Report each draft with a before/after word count table, what changed and why it reads better, anything to approve, and where the files are.

## Audit

1. Identify the purpose, audience, destination, and any length limit. Note what the reader needs to know or do after reading.
2. Measure each section.
3. Find where the reader struggles: a buried point, undefined jargon, terms that change, long or tangled sentences, walls of text, missing or out-of-order steps, and filler, hedges, repetition, or AI tells.
4. Propose a new structure, note gaps only the user can fill, and name the top fixes. For a piece of only a few sentences, ask whether the user wants all five drafts or just the audit and one revision. Wait for the user's go-ahead.

## Draft 1: restructure

- Move the sentence that states the point, action, or answer to the top. If no sentence states it, flag the gap instead of writing one.
- Order the rest the way the reader needs it: what it is, why it matters, how to use it, then details.
- Reorder without rewording the author's sentences. Add headings or transitions only where the new order needs them.
- Make sure cross-references ("see below") and links still point at the right place. If a move breaks a dependency, such as a term used before it is defined, fix it and flag it.
- Check that every original sentence appears. List each one that was reworded or dropped.

## Draft 2: clarify and tighten

- Rewrite for clarity: plain words, active voice, concrete subjects, one idea per sentence. Split long sentences. Use lists only for parallel items.
- Then cut repetition, filler, stacked hedges, and AI tells (slogans, rhetorical questions, empty intensifiers). Merge duplicate statements into one place.
- Never drop a fact, condition, caveat, warning, number, name, or link.
- Build a claims checklist from the original, one claim per row, and confirm 100% are present.
- Flag noticeable rewording and softened caveats.

## Draft 3: merge

- Compare drafts 1 and 2 paragraph by paragraph. Keep the version a reader understands faster. Use length only to break a tie.
- Restore caveats or context draft 2 cut if a reader needs them.
- Remove anything that restates what the reader just read.
- Re-run the claims checklist and word counts.

## Draft 4: rubric

1. Score 0-10 on accuracy, clarity, readability and skimmability, structure and flow, voice match, audience fit, destination formatting, and concision.
2. Review as a strict adversarial reader. Read every line. Check edge cases: a skimming reader, a newcomer, someone following the steps exactly, how it renders in the destination, exact links, numbers, and commands.
3. Fix every deduction, re-score, and repeat. Don't inflate scores. Points that only real readers can earn stay unearned.
4. Save the rubric and score sheet as `<name>-v4-review.md`.

## Draft 5: fidelity

1. Compare with the original by meaning, claims, tone, and voice. Sort differences into added, removed or narrowed, changed, or reworded only.
2. Revert anything added, removed, or changed, using the original wording where it reads fine. Keep only approved changes and the point of the work (clearer order and wording with the same meaning), and flag each one.
3. Editing must never narrow what the reader learns. Keep every condition and caveat.
4. Save a fidelity table as `<name>-v5-fidelity.md`: each original claim, where it is now, and its status (same, approved change, or deliberate improvement). Re-run the claims checklist.
5. Report length changes honestly. A longer section is fine when it is clearer; say why.

## After the drafts

- Recommend a draft and explain the trade-off, such as the clearest version versus the closest match to the author's voice.
- Record deferred ideas.
- Remind the user to preview the chosen draft in its real destination before publishing.
