# Manifold

Manifold is a library for decomposing prose into a corpus of interrelated
concepts and claims. The corpus is intended for committing knowledge and
learning from it. This repository holds the reusable method; client
repositories hold the material processed using that method.

## Working constraints

- The operator's beliefs enter through prose processed in the same way as other
  sources.
- Curatorial actions include selecting sources to process and verifying or
  editing synthesis, definitions, and statements.
- The procedure must be documented sufficiently for the operator to perform it
  manually. The operator should repeat the manual process periodically.
- Automation is limited to operations the operator understands and can replicate.
- Work proceeds in small atomic sprints. Each addition to the code, skills,
  epistemic method, or system is discussed and approved before adoption.

## Definitions

### Proposition

The meaning expressed by a statement, interpreted in its context, that can be
evaluated for truth or falsity.

The proposition is the meaning expressed. Quotations and paraphrases are
representations of that meaning.

### Verbatim quotation

Text reproduced exactly from an identified passage of a source.

## Manual quotation procedure

1. Identify the source and the passage's location.
2. Copy the selected text.
3. Compare the copy against that passage, character for character.

Completion requires both an identifiable source passage and matching text.
This checks the accuracy of the copying.

## Source threads

[Verbatim project threads](threads/README.md) preserve the discussions behind
the library, with links to individual messages for investigation and reference.
