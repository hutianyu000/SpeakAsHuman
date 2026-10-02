# Evaluation

Load this reference when evaluating or modifying the skill's instructions. It is not part of the workflow for ordinary generation, revision, or content review.

## Evaluation scope

Record the skill versions or baseline, model, requested operation, language, loaded references, and how the skill was activated. It is intended to apply by default without an explicit request. State whether the host loaded it, whether host instructions required loading, and whether the user disabled it or requested another style. Permission to invoke it automatically does not ensure loading on every turn. Compare under the same conditions or explain differences. Do not credit the expression rules for an effect caused by different activation settings.

Distinguish reviewing the instructions, checking files and configuration, and testing actual output. If outputs have not been compared, say that the available evidence does not show whether expression improved or by how much. A valid directory structure, a shorter entrypoint, or a review of the rules does not show how well the skill works in practice.

## Output comparison

Compare the revised skill with the previous version or a baseline without the skill on the same inputs. Include text that needs repair, suitable text that should remain unchanged, choices that allow several valid treatments, and material whose meaning or engineering contract must be preserved. Determine what must remain from the material and task, without relying on the proposed edits.

The annotated [examples](examples.md) explain the intended decisions; they do not show that the skill performs well. Test with different inputs and keep expected judgments out of the evaluator's material. Vary names, quantities, wording, and context while preserving the relationship being tested. Reproducing an example's suggested wording is not a measure of success.

Assess useful repairs, unnecessary edits, lost quantities, conditions, negation, attribution or uncertainty, and invented additions. Judge the final output. Where practical, withhold the proposed diagnosis and intended answer from evaluators, and compare outputs without revealing which version produced them. This helps limit preference for the revised skill. Independent reader testing requires a separate reader who has not received the original conversation or intended verdict.

Judge mandatory compliance separately from clarity, necessary information, naturalness, suitable style, and comprehension effort. Correcting a prohibited Chinese sentence dash satisfies an output constraint; English sentence dashes and quotation marks are assessed by function, meaning, and target conventions. Removing permitted punctuation is not inherently an improvement. Assess the effect on meaning, readability, and author voice. Punctuation alone does not establish defective reasoning or AI authorship. Do not use a human-likeness score or detector result as the quality verdict.

Model judgments and mechanical checks alone cannot establish overall quality. Report observed results and limits; do not generalize from a small comparison to every task. No framework, permanent test files, fixed scores, sample count, or additional agents are required.

## Instruction maintenance

Keep each rule in one primary maintenance location: shared requirements in the entrypoint, language differences in zh or en, task differences in scenario files, and skill evaluation here. A scenario reminder should add a concrete condition or operation; otherwise reference the shared rule rather than repeat it.

Add a rule only if it changes an observable decision under clear conditions. Combine overlapping instructions and state when each reference should be read. Keep project settings in their configuration files instead of repeating them in the skill. Create a separate reference only for a distinct responsibility that will remain useful across tasks. Preserve mandatory rules and limits on changing meaning when shortening instructions. Fewer characters alone do not make a better skill.

Prefer existing examples when adding illustrations. Compare each suggested edit with its input for lost distinctions, changed quantities, added actors or claims, and altered certainty. Establish the meaning of engineering examples from the implementation or interface. Check existing examples too; their suggested answers may be wrong. If the context cannot support a suggested answer, state what is unresolved or omit the example. Do not invent facts, behavior, or reasons to complete a pair.
