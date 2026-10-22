# Docs

The bar: Anthropic's Claude product docs. A developer lands on any page, knows
in one sentence what it covers, can copy a sample that runs, and finds every
limit, status and failure stated rather than implied.

## What these docs do

- **Pages say their job at once.** Titles are short, sentence case, and either
  name the thing or the task. A one-sentence description says what the reader
  will be able to do. The first sentence defines the feature or the page's
  scope, and points readers who need something else to the right page.
- **Guides follow a fixed order.** What it is, a minimal working example, how it
  works, limits and pricing, configuration, patterns, troubleshooting, next
  steps. The example comes before the deep explanation.
- **Steps are single actions.** Each step has an imperative title and does one
  thing. Prerequisites sit before the first step as two or three linked items.
- **Samples run.** A quickstart sample is a complete file with install and run
  commands. Shorter samples are runnable or clearly marked as fragments.
  Secrets come from an environment variable; the only placeholder is an obvious
  one. Comments in samples explain intent. One realistic scenario is carried
  through the page. Each sample that produces output shows that output.
- **Every client gets the same example.** Samples are offered in every
  supported client or SDK, in the same order on every page. A client that can't
  do the job is said to be unable, not silently dropped.
- **Callouts are rare and single-purpose.** Notes carry scope and exceptions,
  tips carry one shortcut, warnings are kept for silent failure, data loss and
  cost.
- **Reference pages are uniform.** Each field gives its name, type, whether it is
  optional, its default, its constraints with units in human terms, and a
  description. Enums list every value. Deprecated values carry a date and a
  replacement. Errors live in one place, keyed by status and type, with the
  exact message text and the fix.
- **Limits are numbers.** Every limit has a unit, a scope (per what, per tier),
  and a statement of what happens when it is hit, including the error.
- **Status is labelled where the feature appears.** Beta, preview, deprecated
  and retired features say so inline, with a date or version and a migration
  link. Version-dependent behaviour says which version it requires.
- **What is not supported is said outright**, usually in a Limitations section.
- **Troubleshooting starts from the symptom.** Headings name what the reader
  sees; each entry gives the cause and the fix, and quotes the exact error.
- **Pages tell readers how to verify** that it worked: what to run, what field to
  read, what success looks like.
- **Guides link to reference instead of restating it**, and every guide or
  concept page ends with next steps: two to four links, each with a reason.
- **Release notes are dated and atomic.** One dated heading per release, newest
  first, one change per bullet, each linked to its doc and labelled with its
  status.
- **Voice is plain.** Second person, present tense, imperative for actions,
  short sentences, no marketing adjectives. A defined term is bolded once and
  then used the same way everywhere. Uncertain behaviour is called uncertain.

## Checks

1. **B** The title is sentence case and the frontmatter description states the reader's outcome in one sentence.
2. **P** The first sentence defines the feature or states the page's scope. No preamble.
3. **B** Prerequisites come before the first step as a short linked list, or the page needs none.
4. **P** Each step has an imperative title and does one action.
5. **B** Every code sample runs as given or is marked as a fragment. No secret is inlined; placeholders are obvious.
6. **P** Each runnable sample that produces output shows its output (truncation is fine).
7. **P** Samples cover every supported client in a fixed order, or the page says which client can't do it.
8. **P** No more than three callouts per screen; each carries one point; warnings only for silent failure, data loss or cost.
9. **B** On reference pages, every field has name, type, optional or not, default, constraints with units, and a description; enums list all values.
10. **B** Every limit is a number with a unit and a scope, and the page says what happens when it is hit.
11. **B** Beta, preview, deprecated and retired features are labelled where they appear, with a date or version and a migration link.
12. **P** Version-dependent behaviour names the version it requires.
13. **B** Unsupported cases are stated explicitly, not left to inference.
14. **P** Troubleshooting entries are headed by the symptom and quote the exact error text.
15. **P** The page tells the reader how to confirm it worked.
16. **P** The page ends with two to four next-step links, each with a reason, and links to reference rather than duplicating it.
17. **P** Defined terms keep one name throughout; no marketing adjectives.

## Sources read (2026-10-22)

- https://platform.claude.com/docs/en/get-started
- https://platform.claude.com/docs/en/build-with-claude/prompt-caching
- https://platform.claude.com/docs/en/build-with-claude/streaming
- https://platform.claude.com/docs/en/agents-and-tools/tool-use/overview
- https://platform.claude.com/docs/en/agents-and-tools/tool-use/how-tool-use-works
- https://platform.claude.com/docs/en/agents-and-tools/mcp-connector
- https://platform.claude.com/docs/en/api/messages/create
- https://platform.claude.com/docs/en/api/beta/files/upload
- https://platform.claude.com/docs/en/api/errors
- https://platform.claude.com/docs/en/api/rate-limits
- https://platform.claude.com/docs/en/release-notes/overview
- https://code.claude.com/docs/en/quickstart
- https://code.claude.com/docs/en/settings
- https://code.claude.com/docs/en/cli-reference
