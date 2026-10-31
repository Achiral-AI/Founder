# Distill-Essay

Renders a research idea as a first-person working-hypothesis essay in the style of the Distill journal: the whole argument up front, one worked example built in front of the reader, and confidence that tracks the evidence sentence by sentence.

## Use When

- The piece is a research essay, research preview, or companion post to a paper, written for curious practitioners rather than reviewers.
- The draft reads like a compressed paper (abstract, contributions, related work) when it should read like a researcher explaining what they think and why.
- The argument is spread across sections and the reader has to finish the piece to learn the claim.
- The draft has a strong example that is stated once instead of being worked through.

## Model Texts

Calibrate against Distill (2016–2021), for example _Feature Visualization_ (Olah, Mordvintsev, and Schubert, 2017) and _Zoom In: An Introduction to Circuits_ (Olah et al., 2020), and against later essays in the same tradition such as _Neural Networks Are Already Clean_ (Cammarata, Goodfire). They share:

- A short version at the top that states the whole argument, so a reader who stops there still leaves with the claim.
- First-person reasoning ("I think", "my bet", "I'm not sure yet") used to separate what the author believes from what was measured.
- The argument laid out as a short numbered sequence of steps, with any speculative step labelled as speculative.
- One concrete case worked through slowly: what was seen, the obvious reading, what made that reading wrong, and what the case shows.
- An everyday analogy that carries the mechanism, used once and then dropped.
- Honest accounting of earlier beliefs, rival explanations, and the outcome that would prove the author wrong.
- Plain section titles that say what the section shows rather than naming a document role.

## Edit Moves

- Open with a section that gives the whole argument: the claim in one sentence, why it matters in a paragraph, and the argument as a few numbered steps. Name it for what it shows in this piece, not with a stock label.
- Mark the boldest step as speculative instead of deleting it or hedging every step.
- Rewrite paper scaffolding ("This work proposes", "Our contributions are") as the author's own claim in the first person.
- Pick the single best example and walk the reader through it, pointing at the exact word, value, or event that carries the point.
- Find one analogy from everyday life that matches the mechanism, check that it does not overstate the claim, and place it where the reader first needs it.
- Rename sections from roles ("Background", "Discussion") to what they show ("Why the obvious check misses it").
- Turn the limitations section into a statement of what result would change the author's mind.
- Keep every number, citation, and caveat from the source draft; the style changes the voice, not the evidence.

## Questions

- Could a reader who stops after the short version state the claim correctly?
- Does each "I think" mark a real belief, and is anything measured stated without one?
- Is the worked example concrete enough that a reader could retell it?
- Does the piece say what outcome would prove it wrong?

## Avoid

- Copying a model text's headings, opening lines, signature phrases, or section order. Borrow the moves, not the words; every heading should be specific to this piece.
- Inventing biography, lab history, or past beliefs the author has not stated. First person carries reasoning, not made-up experience.
- Turning a hypothesis into a finding because the voice became more confident.
- More than one or two analogies, or an analogy that implies a stronger mechanism than the evidence supports.
- Interactive-figure language ("hover", "drag") in a piece without interactive figures.
- Recap endings that restate the short version.

## Stop When

A practitioner can read the short version alone and repeat the claim, follow the worked example without the paper, and name the result that would falsify it, and no claim in the essay is stronger than in the source draft.
