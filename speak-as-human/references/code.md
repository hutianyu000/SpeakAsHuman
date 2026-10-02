# Code

## Objects and contracts

Choose names from actual responsibility, behavior, scope, and lifecycle. Establish meaning from relevant implementation, callers, or existing documentation. When behavior is uncertain, retain that uncertainty instead of renaming from word appearance alone.

Use engineering terms accurately and in ways maintainers will recognize. Improving wording does not fix implementation defects. If a name or comment conflicts with behavior, explain the evidence and determine what the user has authorized you to change.

## Choosing names

Name files, directories, modules, classes, functions, parameters, and variables for a stable domain concept, responsibility, or role established by implementation and direct uses. The name must still fit when inputs or callers change within the same contract and be understandable without the original conversation. Do not transcribe a request, concatenate requested activities, or encode repair, workaround, or edit history into a lasting name. Avoid compound labels made from incidental details.

Use consistent terminology across code, tests, comments, and documentation within the relevant domain. Follow project and domain abbreviation conventions. Establish meaning from definitions, implementation, direct uses, or an available glossary. Check conflicting meanings and multiple terms for one concept while respecting distinctions kept separate across contexts. Prefer existing terms when they fit; report unresolved conceptual ambiguity rather than changing synonyms. This check does not authorize creating a glossary or renaming unrelated objects.

Match the name to the object's abstraction level. Name domain operations for their domain purpose and technical mechanisms for their technical responsibility. Do not replace the concept the object represents with a caller's incidental workflow, storage format, framework terminology, or lower-level implementation details. Include a detail when it is part of the object's public meaning or contract.

Make names long enough to remove ambiguity. Keep qualifiers only when they distinguish a lasting constraint, scope, unit, lifecycle state, or contract. Preserve necessary distinctions even when the name is long. Do not shorten a specific name into a vague general term or imply an abstraction the implementation does not support.

Check the proposed name alongside direct uses, related tests, and existing terminology. A comment cannot repair a misleading name. If mixed responsibilities prevent an accurate name, report the design issue without hiding it under a broad label or performing an unrequested architectural refactor.

Follow programming-language syntax, tool restrictions, and project conventions for identifier capitalization, word separation, and type naming. Filenames should express purpose and respect directory and tooling conventions. Choose languages for identifiers, filenames, and reader-facing explanations separately; use the entrypoint's routing to select references.

## Changing existing names

Before renaming, identify direct references and external contracts relevant to the object, including imports, callers, configuration keys, serialized fields, paths, and public APIs. If the user asks only for suggestions or review, provide the recommendation and impact without executing a rename.

For an authorized rename, preserve behavior and contracts except for changes explicitly included in the authorized task. Update affected references within scope; if completing the change requires broader edits, identify that dependency before applying an incomplete rename.

Choose verification appropriate to the change, such as reference search, type checking, a build, or relevant tests. Inspect the affected-file diff for missed direct consumers and unrelated changes.

## Comments

Comments should add information not clearly expressed by the code, such as design reasons, non-obvious constraints, usage conditions, units, or external requirements. Mechanical restatement usually adds little; retain explanation when it serves teaching or interface documentation for the intended audience.

Describe maintained behavior and reasons, not conversation history, editing steps, or completion status. Retain historical context only when it explains a current constraint or compatibility obligation.

Keep comments consistent with the implementation. Describe actual guarantees and conditions. Do not speculate about universal behavior, safety, or performance. Preserve necessary reasons and limits when editing, and mark unconfirmed explanations as uncertain or needing verification.

## Technical explanations

Distinguish actual behavior, design intent, and usage advice. Explain inputs, outputs, prerequisites, and limits with existing project terminology, describing only relevant, supported contracts.

Examples must match the associated interface and implementation and must not imply unsupported capabilities. Adjust explanatory density to the audience while retaining concepts, conditions, and boundaries.
