# Evaluation

Load this reference when evaluating or modifying the skill's instructions. It is not part of the workflow for ordinary generation, revision, or content review.

## Evaluation scope

Record the skill versions or baseline, model, task operation, language, loaded references, and activation policy relevant to the comparison. State whether a personal or host instruction enables the skill for ordinary conversation beyond its default task triggers. Keep these conditions comparable or explain their differences; do not attribute an activation-policy effect to the expression rules alone. Default conversation activation remains a host or user preference rather than a required installation behavior.

Distinguish inspection of instruction design, mechanical validation, and observed output behavior. If outputs have not been compared, state that the available evidence cannot establish an improvement in expression quality or its magnitude. A valid directory structure, a shorter entrypoint, or an evaluator's reading of the rules does not establish behavioral effectiveness.

## Output comparison

Compare the candidate with the previous version or a baseline without the skill on the same inputs. Include defective expression, already suitable text that should remain intact, context-dependent choices with different valid treatments, and material whose meaning or engineering contract must be protected. Derive preservation expectations from the material and task rather than the candidate's proposed changes.

The annotated [examples](examples.md) clarify intended boundaries; they are not evidence that the skill performs well. For behavioral comparisons, use distinct inputs and keep expected judgments separate from the evaluator's material. Vary names, quantities, wording, and context while preserving the relationship under examination. Do not score success by reproducing the examples' preferred wording.

Assess useful repairs, unnecessary edits, lost quantities, conditions, negation, attribution or uncertainty, and fabricated additions. Evaluate actual final artifacts. Where practical, let evaluators see them without the proposed diagnosis or intended answer, and use blind comparisons to reduce preference for the candidate. Independent reader testing requires a separate reader who did not receive the original conversation or the intended verdict.

Judge mandatory compliance separately from clarity, necessary information, naturalness, suitable style, and comprehension effort. Correcting punctuation satisfies an output constraint; it does not by itself establish a more natural expression, defective reasoning, or AI authorship. Assess how a required recast affects meaning, readability, and author voice within the mandatory rules. Do not use a human-likeness score or detector result as the quality verdict.

Model-only judgments and mechanical checks do not certify overall quality. Report observed outcomes and limits without converting a small comparison into a universal claim. These requirements do not prescribe a framework, permanent test files, fixed scores, a fixed sample count, or additional agents.

## Instruction maintenance

Keep each rule in one primary maintenance location: shared requirements in the entrypoint, language differences in zh or en, task differences in scenario files, and skill evaluation here. A scenario reminder should add a concrete condition or operation; otherwise reference the shared rule rather than repeat it.

Add a rule only if it changes an observable decision under clear conditions. Consolidate overlapping instructions, keep reference-loading conditions explicit, and leave discoverable project configuration in its owning files. Split a new file only when its requirements have an independent, stable responsibility. Preserve mandatory rules and semantic boundaries when shortening instructions; a reduced character count is not sufficient evidence of a better skill.

Prefer available existing examples when adding illustrations. Check each suggested edit against the input for lost distinctions, changed quantities, added actors or claims, and altered certainty. For engineering examples, establish the meaning from the relevant implementation or interface. An existing example still needs this check; do not treat its suggested answer as automatically correct. If the available context does not support a preferred answer, state the unresolved condition or omit the example rather than invent facts, behavior, or reasons to complete the pair.
