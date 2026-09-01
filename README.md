# Founder

Composable editorial passes for founder writing.

**Founder** helps you [write simply](https://www.paulgraham.com/simply.html). This repo has a number of skill files that each focus on different aspects of writing styles. Founder will remove AI residue, sharpen judgment, clarify the argument, preserve voice, and make the best ideas stick. Most importantly, it will keep the prose lightweight so that the reader can spend more time and energy on the ideas expressed. 

Choose the few editorial moves the draft actually needs.

## Install

Install this as a Codex skill:

```bash
python3 /Users/sonicaarora/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo Achiral-AI/founder \
  --path .
```

After installation, invoke it with `$founder`:

```text
Use $founder on this draft. Start with No-AI-Slop, then use Clarity, Precision, and Voice.
```

## How To Use

Use each file in `skills/` as one pass over the draft.

Most drafts should start with [`No-AI-Slop`](skills/No-AI-Slop.md) when the prose feels generic, padded, over-polished, or model-like. That first pass removes the obvious residue before more intentional editorial work begins.

Then choose the craft pass that matches the real problem:

| Need | Use |
| --- | --- |
| Better selection, emphasis, or structure | [`Editorial-Judgment`](skills/Editorial-Judgment.md) |
| A stronger point of view | [`Thought-Leadership`](skills/Thought-Leadership.md) |
| Better reasoning, evidence, or scope | [`Intellectual-Rigor`](skills/Intellectual-Rigor.md) |
| A clearer path from premise to conclusion | [`Argumentation`](skills/Argumentation.md) |
| More conviction or action | [`Persuasion`](skills/Persuasion.md) |
| Consistent company language | [`Brand-Writing`](skills/Brand-Writing.md) |
| Fast executive comprehension | [`Executive-Writing`](skills/Executive-Writing.md) |
| Accurate procedures or explanations | [`Technical-Writing`](skills/Technical-Writing.md) |
| Accessibility without dumbing down | [`Plain-Language`](skills/Plain-Language.md) |
| Character, scene, and payoff | [`Storytelling`](skills/Storytelling.md) |
| A recognizable author | [`Voice`](skills/Voice.md) |
| Lines readers remember | [`Memorability`](skills/Memorability.md) |
| Final cleanup | [`Polish`](skills/Polish.md) |

## Default Chain

Use this when a draft needs broad editorial improvement:

```text
No-AI-Slop
  -> Editorial-Judgment
  -> Clarity
  -> Precision
  -> [one or more intentional crafts]
  -> Voice
  -> Memorability
```

This is a guide, not a rule. Skip any pass that does not clearly improve the draft.

## Common Pipelines

```text
Point-of-view essay:
No-AI-Slop -> Thought-Leadership -> Intellectual-Rigor -> Argumentation -> Clarity -> Precision -> Voice

Brand or launch copy:
No-AI-Slop -> Brand-Writing -> Persuasion -> Memorability -> Voice

Executive memo:
Editorial-Judgment -> Executive-Writing -> Intellectual-Rigor -> Clarity -> Precision

Technical explainer:
Technical-Writing -> Plain-Language -> Clarity -> Precision -> Reader-Empathy

Narrative piece:
Editorial-Judgment -> Narrative -> Storytelling -> Voice -> Memorability
```

## Skill Map

The core passes improve the underlying writing:

- [`No-AI-Slop`](skills/No-AI-Slop.md): removes generic, model-like prose patterns.
- [`Editorial-Judgment`](skills/Editorial-Judgment.md): decides what belongs, what matters, and where to stop.
- [`Clarity`](skills/Clarity.md): makes the idea immediately understandable.
- [`Precision`](skills/Precision.md): makes each important word carry the intended meaning.
- [`Concision`](skills/Concision.md): increases information density.
- [`Voice`](skills/Voice.md): preserves the author's recognizable style.
- [`Memorability`](skills/Memorability.md): gives the idea a durable formulation.

The intentional craft passes shape the piece for its job:

- [`Thought-Leadership`](skills/Thought-Leadership.md): strengthens thesis, insight, and intellectual position.
- [`Persuasion`](skills/Persuasion.md): moves the reader toward belief or action.
- [`Authority`](skills/Authority.md): creates earned confidence without fake certainty.
- [`Intellectual-Rigor`](skills/Intellectual-Rigor.md): scopes claims and strengthens reasoning.
- [`Narrative`](skills/Narrative.md): creates progression, tension, and resolution.
- [`Storytelling`](skills/Storytelling.md): uses character, scene, and emotional movement.
- [`Brand-Writing`](skills/Brand-Writing.md): aligns copy with positioning and identity.
- [`Executive-Writing`](skills/Executive-Writing.md): makes the point fast, strategic, and decision-ready.
- [`Technical-Writing`](skills/Technical-Writing.md): improves accuracy, terminology, and reproducibility.
- [`Plain-Language`](skills/Plain-Language.md): makes complex ideas easier to read.
- [`Reader-Empathy`](skills/Reader-Empathy.md): follows the reader's knowledge, questions, and objections.
- [`Argumentation`](skills/Argumentation.md): connects premise, reasoning, evidence, and conclusion.
- [`Originality`](skills/Originality.md): replaces familiar internet language with a more distinctive angle.
- [`Polish`](skills/Polish.md): cleans the final surface.

## Example Prompts

```text
Apply No-AI-Slop, then Clarity, then Voice to this draft. Keep the author's meaning and avoid making it sound corporate.
```

```text
Run this through No-AI-Slop, Thought-Leadership, Intellectual-Rigor, and Precision. I want a sharper thesis, but no fake certainty.
```

```text
Use Brand-Writing, Persuasion, and Memorability on this launch copy. Preserve the product facts, but make the positioning stronger.
```

```text
Use Executive-Writing and Editorial-Judgment. Turn this into a concise memo for a busy founder or investor.
```

```text
Use Technical-Writing, Plain-Language, and Reader-Empathy. Make this accurate and easy for a non-specialist to follow.
```

```text
Use $founder on this README. Apply No-AI-Slop, Editorial-Judgment, Clarity, Brand-Writing, Voice, and Polish.
```

## Working Method

Treat each skill as an editorial pass. Preserve the user's meaning unless the selected skill explicitly calls for strengthening, challenging, or reframing it. When a draft has conflicting needs, prefer judgment over mechanical compliance.

For best results, ask for the output mode you want:

- `diagnose only`: identify what each pass would change before rewriting.
- `rewrite`: produce a revised draft.
- `diff`: show the most important before/after changes.
- `chain`: apply multiple passes in order and explain what each pass changed.
