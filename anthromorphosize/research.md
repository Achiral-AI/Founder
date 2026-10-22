# Research pre-prints

The bar: Anthropic's research publications, both its arXiv pre-prints and its
long-form interpretability papers. They say exactly what was found, in which
model and setup, how sure they are, what failed, and what the work does not
show. They also publish enough for someone else to check.

## What these papers do

- **The abstract is a complete argument in one paragraph**, roughly 150 to 250
  words: the problem, what was done, the headline results with numbers, a
  sentence on what the work does not claim, and the implication. Long-form
  papers may replace it with a short introduction and a bulleted list of key
  results.
- **Contributions are numbered** in the introduction, each pointing to the
  section that supports it.
- **Findings are tied to their setup.** "We find" introduces an observation in a
  named model, dataset and configuration. Proof-of-concept constructions are
  called demonstrations, not findings.
- **Confidence is graded.** Speculation is labelled as hypothesis or conjecture
  and kept in its own paragraphs, apart from results. Causal language appears
  only where the evidence is causal (an intervention, an ablation).
- **The paper says what it does not show**, and reports negative results and
  failure rates in the main text.
- **Methods are reproducible.** Models and versions, dataset sizes, run counts,
  thresholds and hyperparameters are stated; full detail goes in lettered
  appendices referenced from the text. Prompts, rubrics and judge instructions
  are published verbatim, and any automated judge is checked against human
  labels on a random subset. Code, data or a replication path is linked.
- **Examples are honest.** Illustrative examples are marked as selected, and
  randomly sampled ones are given too.
- **Evidence carries its uncertainty.** Every quantitative figure and table names
  its uncertainty method (confidence interval type, standard error, number of
  seeds or runs), or says it is omitted and where to find it. Each main result
  has a baseline and an ablation, or a stated reason why none applies.
- **Captions stand alone.** A caption says what is plotted, how to read the
  encoding, which model and condition, the uncertainty measure, and the
  takeaway.
- **Limitations get their own section**, a summary first, then each limitation
  with a concrete case. Related work is its own section and says how this work
  differs. Work with misuse potential has a short impact or disclosure note.
- **Notation is disciplined.** Every symbol is defined in prose at first use;
  typography stays consistent; a coined term is introduced next to the standard
  name and never renamed. Notation-heavy papers carry a notation table.
- **The register is formal and plain.** First person plural, short sentences
  where possible, glosses for non-specialists, and footnotes that disclaim
  anthropomorphic wording when it is used as shorthand.
- **Citation is complete.** Inline links or a reference list, an author
  contributions section when there is more than one author, and a citation
  block with a stable key and URL.

## First, name the paper type

Every check below applies to one or both types. Decide which the paper is
before running them, and say so in the review.

- **Empirical**: it reports measurements, experiments or benchmark results.
- **Architecture**: it proposes a design, framework or analysis and reports
  no measurements. Frontier labs hold these papers to a different bar, not a
  lower one: in place of results, they must make the claim falsifiable and
  the future evaluation concrete.

A paper that mixes both is empirical for every result it reports.

## Disclosure boundaries

Work tied to patents or products may withhold estimators, thresholds or
implementation details. In an architecture paper, a stated disclosure boundary
(what is withheld, and that it is withheld on purpose) satisfies check 13. In an empirical paper, nothing needed to check a reported number may be
withheld.

## Paper and companion page

These checks apply to the paper itself (the PDF or its source). A web page
that presents the paper is reviewed with `writing.md`, plus checks 4, 5 and
8 here, and must use the paper's names for every coined term and symbol.

## Checks

Each check is marked for both types, **[E]** empirical only, or **[A]**
architecture only.

1. **B** The abstract states, in order, the problem, the method, then either the headline results with numbers **[E]** or the central claim and how it could be falsified **[A]**, then what the work does not show and the implication, in 250 words or fewer.
2. **P** The abstract is a single paragraph.
3. **P** The introduction lists numbered contributions, each linked to its section, and each verb matches what the paper does ("argue" for an argument, "derive" only for a derivation).
4. **B** Speculation is labelled and kept apart from results; no causal claim without causal evidence.
5. **B** The paper states explicitly what it does not show.
6. **B** A Limitations section exists (any heading that plainly means it) and gives a concrete case for each limitation, including the limits of the paper's own method.
7. **B** Every caption says what is plotted or drawn, how to read it, the condition, and the takeaway.
8. **B** Every symbol is defined at first use, typography is consistent, and coined terms keep one name across the paper, its web page and its citation metadata.
9. **B** **[E]** Every "we find" or "we show" names the model, data and setup it holds for.
10. **B** **[E]** Negative results and failure rates appear in the main text.
11. **B** **[E]** Models, versions, data sizes, run counts, thresholds and hyperparameters are stated, with full detail in an appendix.
12. **B** **[E]** Every quantitative figure or table reports uncertainty and names its method, or says it is omitted and where it is.
13. **P** Code, data or a replication path is linked, or the paper says why not.
14. **B** **[E]** Each main result has a baseline and an ablation, or a stated reason why not.
15. **B** **[E]** All prompts, rubrics and judge instructions are published verbatim; automated judges are checked against human labels.
16. **P** **[E]** Illustrative examples are marked as selected, and random samples are provided.
17. **B** **[A]** The paper says up front, in the abstract or introduction, that it reports no measurements.
18. **B** **[A]** It states the conditions under which its claim would be narrowed or falsified.
19. **B** **[A]** It specifies the evaluation that would test it: named baselines including ablations, tasks, and metrics.
20. **B** **[A]** It states its claim boundary against prior work: what it claims as new and what it does not.
21. **P** Related work is its own section and says how this work differs.
22. **P** Work with misuse potential carries a short impact or disclosure note.
23. **P** The paper ends with author contributions (when there is more than one author) and a citation block with a stable key and URL.

## Sources read (2026-10-22)

- https://transformer-circuits.pub/2022/toy_model/index.html
- https://transformer-circuits.pub/2025/attribution-graphs/biology.html
- https://transformer-circuits.pub/2025/attribution-graphs/methods.html
- https://transformer-circuits.pub/2021/framework/index.html
- https://arxiv.org/abs/2212.08073
- https://arxiv.org/html/2401.05566
- https://arxiv.org/html/2412.14093
- https://www.anthropic.com/research
- https://www.anthropic.com/research/alignment-faking
- https://www.anthropic.com/research/many-shot-jailbreaking
- https://www.anthropic.com/research/mapping-mind-language-model
