# founder

Composable editorial skills for turning founder writing into clear, rigorous, memorable work without flattening the author's voice.

## How To Use

Use these skills as an editorial chain. Each file in `skills/` is one pass over the draft, with one job. Do not run every skill by default. Pick the smallest chain that matches what the draft needs.

Most chains should start with `No-AI-Slop` or a similar cleanup skill when the draft feels generic, over-polished, padded, or model-like. That first pass removes the obvious residue before more intentional editorial work begins.

After that, choose the craft pass that matches the real problem:

- Use `Editorial-Judgment` when the piece needs better selection, emphasis, or structure.
- Use `Thought-Leadership` when the piece needs a stronger point of view.
- Use `Intellectual-Rigor` when the claims need sharper reasoning, evidence, or scope.
- Use `Argumentation` when the logic needs a clearer path from premise to conclusion.
- Use `Persuasion` when the writing needs to change a reader's mind or motivate action.
- Use `Brand-Writing`, `Executive-Writing`, `Technical-Writing`, `Plain-Language`, or `Storytelling` for domain-specific craft.
- Use `Voice` near the end so the draft does not become generic after multiple edits.
- Use `Memorability` when the central idea deserves a stronger formulation.
- Use `Polish` last, only after the deeper editorial choices are settled.

## Default Chain

Use this when a draft needs general editorial improvement:

```text
No-AI-Slop
  -> Editorial-Judgment
  -> Clarity
  -> Precision
  -> [one or more intentional crafts]
  -> Voice
  -> Memorability
```

This is a guide, not a rule. Skip any pass that does not clearly improve the artifact.

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

## Working Method

Treat each skill as an editorial pass. Preserve the user's meaning unless the selected skill explicitly calls for strengthening, challenging, or reframing it. When a draft has conflicting needs, prefer judgment over mechanical compliance.

For best results, ask for the output mode you want:

- `diagnose only`: identify what each pass would change before rewriting.
- `rewrite`: produce a revised draft.
- `diff`: show the most important before/after changes.
- `chain`: apply multiple passes in order and explain what each pass changed.
