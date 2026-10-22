---
name: anthromorphosize
description: Hold docs, blog posts, concept pages, essays and research pre-prints to the quality bar of the best AI-lab publishing (Anthropic's product docs, Anthropic and OpenAI's news and engineering writing, Anthropic's research papers). Use when writing, editing or reviewing any of these; produces checks a reviewer can pass or fail, without replacing the author's voice.
---

# Anthromorphosize

Raise a draft to the standard of the best published work in AI: product docs
that a developer can follow without guessing, posts whose every number can be
checked, and pre-prints that say what they found, how, and what they did not
show.

The standards here were derived from reading public pages by Anthropic and
OpenAI (listed in each reference file). They are written in our own words as
checks. Nothing here is copied from those pages, and this skill is not
affiliated with or endorsed by either company.

## Pick the standard

| The draft is                                                                                                          | Read          | Voice                                                         |
| --------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------- |
| Product docs: quickstarts, guides, concept docs, API reference, changelogs                                            | `docs.md`     | Plain second person. No authorial voice.                      |
| Blog posts, essays, concept and explainer pages                                                                       | `writing.md`  | The author's own. This skill raises the bar, never the voice. |
| Research pre-prints and papers (web pages that present a paper use `writing.md` plus three checks from `research.md`) | `research.md` | Formal "we", plain words.                                     |

Only one standard applies to a page. When a page mixes kinds (a blog post with a
setup guide in it), apply the standard of its main job and borrow the specific
checks the other part needs.

## How to use

**Writing or editing.** Read the reference file, draft or revise, then run its
checks yourself before you hand the draft back. Fix what fails. Do not add
facts, numbers or sources to make a check pass; if a check needs something the
author has not given you, ask for it.

**Reviewing.** Run every check in the reference file against the draft. For
each failure, quote the line, name the check, and say what would fix it. Each
check is marked:

- **B**, blocking: the page should not publish while it fails, because a
  reader would be misled, stuck or unable to verify a claim.
- **P**, polish: report it, but do not hold the page for it.

Report at most the five most useful P findings. Never block on taste.

## With the Founder passes

This skill sets the bar; the Founder passes in `../skills/` do the editing.
For voice-led writing, run `No-AI-Slop` first and `Voice` last, so the
author still sounds like themselves after the bar is met. For docs, pair this
with `Technical-Writing`. For pre-prints, pair it with `Intellectual-Rigor`
and `Precision`.

## What this skill does not do

- It does not check facts against the world or against code. Pair it with a
  source check (for product docs: read the implementation).
- It does not make a founder's post sound like a company announcement.
- It does not set visual design.
