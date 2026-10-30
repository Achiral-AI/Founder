# Preprint-Prose

Renders research writing in the register of landmark machine-learning and science preprints: terse, claim-first, evidence-calibrated prose that earns authority through restraint rather than assertion.

## Use When

- The draft is a paper, technical report, research memo, benchmark write-up, or documentation meant to read as credible science, not as explanation or persuasion.
- The prose hedges to sound careful instead of stating exactly what is known.
- The draft reaches for adjectives ("powerful", "robust", "novel", "significant") where a number, a named mechanism, or a citation would do the work instead.

## Model Texts

Calibrate against the register of *Attention Is All You Need* (Vaswani et al., 2017) and Anthropic's own research writing (e.g. *Constitutional AI*, *Towards Monosemanticity*, model cards). Both share:

- An abstract that states contribution, method, and result in four or five sentences, in that order, with no throat-clearing sentence before the first claim.
- Claims carried by numbers and named objects (a BLEU score, a GPU count, a feature count) rather than by intensifying adjectives.
- Confidence calibrated to evidence: "we show" or "we find" for a measured result, "we believe" or "preliminary evidence suggests" for an interpretation — never the same verb for both.
- Limitations and negative results stated flatly in their own place, not folded into a defensive aside.
- Short paragraphs built around one claim each; the next paragraph does not restate the previous one in different words.

## Edit Moves

- Open with the claim, not with background the reader doesn't need yet.
- Replace an intensifying adjective with the number, named mechanism, or citation that would let a reader verify it themselves.
- Match the verb to the evidence: "we show" / "we find" only for something measured in this work; "we believe" / "we expect" for an interpretation or hypothesis; "we propose" for a mechanism not yet evaluated.
- Cut a sentence that restates the previous sentence's claim in different wording — rhythm belongs in the transition, not in redundant content.
- Put every limitation, negative result, and unresolved question in its own visible place; do not bury it inside a qualifying clause.
- Prefer one worked example or one number over three adjectives.
- Delete a sentence if removing it costs the reader no information.

## Questions

- Would a careful reader of this field find one unsupported superlative?
- Does every claim's verb match the kind of evidence behind it (measured vs. believed vs. proposed)?
- If a skeptical reviewer struck every adjective, would the sentence still make its claim?

## Avoid

- Marketing cadence: "cutting-edge", "seamless", "unlock", "revolutionize".
- Hedges that exist to sound careful rather than to carry real uncertainty ("may potentially", "it is worth noting that").
- Restating the work's importance instead of stating its result.
- Smoothing a genuinely surprising or flat result into safer, rounder language.

## Stop When

A domain expert could read the draft and find no sentence that claims more, or hedges more, than the evidence in hand supports — and no sentence that could be deleted without losing a claim.
