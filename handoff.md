# Handoff

Manifold is at the first manual specimen. Continue through small discussions and
approved additions. The current deliverable is documentation and source material.

## Repositories and reading order

- `manifold` holds the reusable method and its source threads. Remote:
  [markreveley/manifold](https://github.com/markreveley/manifold), branch `main`.
- `manifold-mark` holds Mark's client collection. Remote:
  [markreveley/manifold-mark](https://github.com/markreveley/manifold-mark), branch
  `main`. Locally, it is a sibling of this repository.

Read [README.md](README.md) for the adopted definitions and procedure, then the
[thread index](threads/README.md) for the relevant discussion and approvals.
Read `manifold-mark/README.md` for the first specimen.

## Purpose and operator requirements

The intended corpus makes arguments, claims, definitions, information, and
questions from prose investigable through their relationships and source
material. It is intended for committing knowledge and learning from it.

- Mark's beliefs enter through prose processed in the same way as other sources.
- Curatorial work includes selecting sources and verifying or editing synthesis,
  definitions, and statements.
- Every automated operation must be understandable and manually reproducible by
  the operator. Periodic manual work is part of using the system.
- Discuss and obtain approval for each code, skill, epistemic, or systemic
  addition. Approval of one addition does not select the rest of an architecture.
- Define terms before making them part of the method. Procedural requirements
  should state required operations and completion checks. Put counterexamples in
  a separate section when they are used.
- Keep the library README factual and concise. Preserve discussion, corrections,
  and approvals in the source threads.

These requirements are expressed in the source thread's
[operator constraints](threads/2026-10-15-foundations.md#m008-user) and
[feedback](threads/2026-10-15-foundations.md#m011-user).

## Adopted method and specimen

The README defines **proposition** and **verbatim quotation**, and gives a
three-step manual quotation procedure with a completion criterion.

A proposition is the meaning expressed. Quotations and paraphrases are
representations of that meaning. The complete source quotation is the initial
representation of the specimen's proposition.

The specimen is the sentence beginning “Lots of people think” in Sean Goedecke's
article [Human-AI partnerships are for alignment, not capability](https://www.seangoedecke.com/human-ai-partnerships-are-for-alignment-not-capability/).
Its location is the final sentence of the first paragraph of the article body.
The client README contains the exact quotation and source information.

The earlier proposal to split this sentence into a reported belief and an
embedded proposition was withdrawn. “Lots of people think” remains part of what
the complete sentence says. The grammatical and belief-specific fields in the
earlier assistant table were exploratory, not an adopted schema.

## Open decisions

- A structured data schema and further manual decomposition procedures.
- How to represent source context, paraphrases, synthesis, definitions, and
  relationships between propositions.
- What truth means operationally, what evidence permits an assessment, and what
  filing and provenance checks certify. “Established” is not a defined state.
- How to measure support or contradiction. No numerical rubric or interpretation
  of model confidence has been adopted.
- Whether the library contains code, skills, or both; the graph model; and
  whether to reuse Socrates or introduce formal logic such as Lean.

These are discussion topics, not an approved implementation backlog. No next
epistemic addition has been selected.

## Prior work and candidate tools

The local Socrates repository is at
`/Users/mark/dev/repos/z_repos_archive/socrates`. It has typed statements,
preserved sources, dependency traversal, and a proposal/ratification workflow.
Its suitability for Manifold remains a design question. The
[initial discussion](threads/2026-10-15-foundations.md#m007-assistant) contains the
inspection findings and candidate directions; those suggestions are not adopted
requirements.

JEV and the [System One Adapter](https://github.com/typesafe-ai/system-one-adapter-python)
were discussed as candidates for applying a manually defined rubric. No model
runs or integration have been performed for Manifold. A model's probability or
confidence has not been defined as a measure of a claim's support. See the
[JEV discussion](threads/2026-10-15-foundations.md#m010-assistant).

A related local evaluation proposal is
`/Users/mark/dev/repos/evals/eval-resources/experiment-candidates/jev-unsupported-claims.md`.
It describes defining manual reference judgments before evaluating a model grader.

## Source thread persistence

[Manifold foundations](threads/2026-10-15-foundations.md) preserves messages M001
through M029, ending with the request to commit, push, and create this handoff.
It includes user messages, assistant replies, and progress updates. Tool calls
and results are outside the transcript's scope.

The message bodies were extracted from stored conversation records and checked
for exact text equality. Numbered headings provide stable references. Retain
existing message numbers and text when extending the thread; later corrections
remain later messages.

For continuing the export on this machine, the source thread ID is
`01a13c07-24b1-7513-8b9a-f1029a7298df`. Its visible messages are available in
`/Users/mark/.codex/thread_history_1.sqlite`, table `thread_items`, as
`userMessage` and `agentMessage` records ordered by `rollout_ordinal`. The
transcript header identifies the last captured source message. This export used
a one-off local operation; no exporter has been added to the library.

## Resuming

Check both repositories' Git status and current commits before editing. Continue
the manual specimen by discussing one concrete addition with Mark. Present its
definition or operation and a worked application for review before adopting it.
