# Documentation structure

Source thread: `01a1421b-3b30-7b62-9e79-c0273d06169e`.

Participants: User and Codex (Assistant).

Coverage: M001 through M016, ending with the request to export this
thread and commit the changes.

Last captured source message: `01a14237-60cd-7a10-a959-765fc1fed108`.

Message bodies are copied from stored conversation records with personal names,
repository names, and local paths redacted. Redactions are labeled in the text;
all other message text was checked for exact equality with the source records.
Numbered headings preserve message references. Scope and navigation are
specified in the [thread index](README.md).

## M001 User

examine manifold handoff.md

## M002 Assistant commentary

I’ll find Manifold’s `handoff.md`, read it, and check the referenced project context.

## M003 Assistant

Read handoff.md [local path redacted], both repository READMEs, and the full foundations thread. They agree on the current state:

- **Adopted:** definitions of proposition and verbatim quotation, plus the three-step manual quotation procedure.
- **First specimen:** the complete “Lots of people think…” sentence. The belief-specific decomposition was withdrawn.
- **Working constraint:** each addition needs discussion and approval, with defined terms and manually reproducible operations.
- **Still open:** schema, decomposition, relationships, truth assessment, scoring, automation, and architecture. No next addition is selected.

Both working trees are clean: `manifold` at `32de690`, `[client repository name redacted]` at `9839466`.

The continuation point is one concrete proposed addition, demonstrated on the specimen for your review. No files changed.

## M004 User

lets think about file structure

I would propose a definitions.md
and a procedures.md
thoughts?
any other ideas without expanding too far too fast?

## M005 Assistant

That split makes sense. Definitions explain **what terms mean**; procedures explain **what to do and how to check completion**.

I’d organize the existing content like this:

- **`README.md`** — project purpose, working constraints, and links to the other documents.
- **`definitions.md`** — proposition, verbatim quotation, and the explanation that quotations and paraphrases represent a proposition.
- **`procedures.md`** — the manual quotation procedure and its completion criterion, linking to the relevant definitions.

The source threads would continue to hold discussion and approvals; `handoff.md` would describe the current state and continuation point. The specimen belongs in `[client repository name redacted]`, as it does now.

One small convention would help: give each definition and procedure its own descriptive heading so other documents can link directly to it. Procedures should reference definitions rather than repeat them, keeping each definition in one place.

I’d make that the whole change for now. The existing material is enough to exercise this structure before introducing more files or organizational rules.

## M006 User

ok. i think we can safely add policy.md, governance.md, or both (after defining each in definitions.md)
"procedures should reference definitions rather than repeat them" being an example of one entry

## M007 Assistant commentary

I’ll look at how “policy” and “governance” would apply to the rules already in the repository, then propose the smallest useful distinction.

## M008 Assistant commentary

Both files have a small, concrete use here: `policy.md` can hold rules for doing and documenting the work; `governance.md` can hold the existing rule about discussing and approving changes.

I’ll define those terms in `definitions.md`, organize the approved material into the proposed files, and add the rule that procedures link to definitions.

## M009 Assistant

Added both, with definitions in definitions.md [local path redacted]:

- **Policy:** a rule specifying requirements for performing work or maintaining material.
- **Governance:** the rules for proposing, reviewing, and approving changes to Manifold.

policy.md [local path redacted] contains the existing working requirements and your example about referencing definitions. governance.md [local path redacted] contains the existing discussion and approval rule.

Moved the quotation procedure into procedures.md [local path redacted], with a link to its definition. Updated the README and handoff to match.

Local links and whitespace checks pass. Changes are uncommitted.

## M010 User

remove any mention of "[personal name redacted]" in any of the documentation
edit the handoff.md - handoff should just be a brief blurb about what the next agent should focus on for the next spike
orientation material should be committed to a readme, or better yet, formal docs

## M011 Assistant commentary

I’ll check both repositories’ documentation, remove personal references, and move orientation material into the formal docs. I’ll shorten `handoff.md` to the next spike’s focus.

## M012 Assistant question

Should the name removal include quoted message bodies in the archived source thread? That would make it a redacted transcript rather than a verbatim one.
- Remove names from all documentation, including archived messages
- Keep archived messages verbatim; remove names from surrounding documentation

## M013 Assistant commentary

The handoff contains useful project state, open questions, and export notes. I’m moving project orientation into `orientation.md` and the transcript details into the thread index. The handoff will be one short paragraph about continuing the manual specimen.

## M014 Assistant commentary

I’m taking “any documentation” to include the archived transcript. I’ll label redactions explicitly and keep the message numbers intact, so the edited archive won’t be presented as a verbatim copy.

## M015 Assistant

Updated both repositories’ documentation:

- Removed personal references, including paths and repository names. Archived messages now have labeled redactions.
- Reduced handoff.md [local path redacted] to a 30-word next-spike focus.
- Moved orientation into orientation.md [local path redacted] and export details into the thread index.
- Recorded the handoff convention in `policy.md`.

Verified name removal, local links, and preserved message numbering. Changes remain uncommitted.

## M016 User

export this thread then commit
