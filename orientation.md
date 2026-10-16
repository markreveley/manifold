# Project orientation

Manifold is at the first manual specimen. The current deliverable is
documentation and source material. This repository holds the reusable method
and its source threads; client repositories hold material processed using the
method.

## Reading order

1. [Definitions](definitions.md) gives the meanings of the method's terms.
2. [Procedures](procedures.md) describes operations and completion checks.
3. [Policy](policy.md) records requirements for source treatment, manual
   reproducibility, and documentation.
4. [Governance](governance.md) records how additions are discussed and approved.
5. The [thread index](threads/README.md) links to foundational discussion,
   corrections, and approvals.

Check the library and relevant client repository's Git status and current
commits before editing. The client README contains the first specimen and its
source information.

## Manual specimen

The specimen is the sentence beginning “Lots of people think” in Sean Goedecke's
article [Human-AI partnerships are for alignment, not capability](https://www.seangoedecke.com/human-ai-partnerships-are-for-alignment-not-capability/).
Its location is the final sentence of the first paragraph of the article body.
The complete source quotation is the initial representation of the specimen's
[proposition](definitions.md#proposition).

The earlier proposal to split this sentence into a reported belief and an
embedded proposition was withdrawn. “Lots of people think” remains part of what
the complete sentence says. The grammatical and belief-specific fields in the
earlier assistant table were exploratory, not an adopted schema. See the
[correction](threads/2026-10-15-foundations.md#m013-assistant) and
[approval](threads/2026-10-15-foundations.md#m014-user).

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

Socrates has typed statements, preserved sources, dependency traversal, and a
proposal/ratification workflow. Its suitability for Manifold remains a design
question. The [initial discussion](threads/2026-10-15-foundations.md#m007-assistant)
contains the inspection findings and candidate directions; those suggestions
are not adopted requirements. In the original workspace, Socrates is located at
`../z_repos_archive/socrates`, relative to this repository.

JEV and the [System One Adapter](https://github.com/typesafe-ai/system-one-adapter-python)
were discussed as candidates for applying a manually defined rubric. No model
runs or integration have been performed for Manifold. A model's probability or
confidence has not been defined as a measure of a claim's support. See the
[JEV discussion](threads/2026-10-15-foundations.md#m010-assistant).

A related evaluation proposal is at
`../evals/eval-resources/experiment-candidates/jev-unsupported-claims.md`, relative
to this repository in the original workspace. It describes defining manual
reference judgments before evaluating a model grader.
