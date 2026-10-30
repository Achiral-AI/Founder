---
name: founder
description: Composable editorial system for founder writing, public essays, memos, launch copy, technical explainers, thought leadership, brand writing, and executive communication. Use when the user asks to improve a draft through chained editorial passes such as No-AI-Slop, Clarity, Precision, Editorial Judgment, Thought Leadership, Persuasion, Voice, Memorability, or related writing crafts; when they want prose to become clearer, sharper, more rigorous, more distinctive, more persuasive, or less AI-sounding without flattening the author's voice.
---

# Founder

Use this skill as an editorial composition system. Choose the smallest chain of craft passes that will improve the draft.

## Workflow

1. Read the full draft and identify the audience, format, and intended reader change.
2. Choose 2-6 passes from `skills/`. Do not use every pass by default.
3. Read each selected craft file before applying that pass.
4. Apply the passes in order. Each pass should make one identifiable improvement.
5. Preserve the author's meaning unless the selected pass explicitly calls for reframing, sharpening, challenging, or narrowing it.
6. End with `Voice` or `Memorability` only when the draft would benefit from personality, rhythm, or a stronger final formulation.
7. Use `Polish` last, after structural and argumentative decisions are settled.

## Default Chain

Use this when the draft needs broad improvement:

```text
No-AI-Slop -> Editorial-Judgment -> Clarity -> Precision -> Voice
```

Add `Memorability` when the piece needs lines that stick. Add one domain craft when the format demands it.

## Chain Selection

- Start with `skills/No-AI-Slop.md` when the draft feels generic, padded, over-smoothed, or AI-produced.
- Use `skills/Editorial-Judgment.md` when the main problem is selection, emphasis, or structure.
- Use `skills/Thought-Leadership.md` when the draft needs an original point of view.
- Use `skills/Intellectual-Rigor.md` when claims need evidence, scope, or uncertainty.
- Use `skills/Argumentation.md` when the logic needs a clearer path.
- Use `skills/Persuasion.md` when the writing needs to create conviction or action.
- Use `skills/Brand-Writing.md`, `skills/Executive-Writing.md`, `skills/Technical-Writing.md`, `skills/Plain-Language.md`, or `skills/Storytelling.md` when the artifact has a specific genre.
- Use `skills/Preprint-Prose.md` when the artifact is a research paper, preprint, benchmark write-up, or research memo meant to read as credible science.
- Use `skills/Voice.md` near the end to preserve the author's recognizable style.
- Use `skills/Memorability.md` near the end to make the central idea more durable.
- Use `skills/Polish.md` only as the final cleanup pass.

## Output Modes

If the user does not specify an output mode, return the revised draft and a short note naming the passes used.

- `diagnose only`: explain what each selected pass would change without rewriting.
- `rewrite`: provide the revised draft.
- `diff`: show the important before/after changes.
- `chain`: name each pass and summarize what changed.

## Guardrails

- Do not invent facts, sources, examples, or credentials.
- Do not smooth the author's voice into generic professional prose.
- Do not over-chain. More passes can make the draft safer but less alive.
- Prefer plain language unless a technical term is necessary.
- Keep useful edge, specificity, and conviction.
