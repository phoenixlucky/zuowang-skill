---
name: zuowang-skill
description: Use when a multi-turn task carries prior context — resuming earlier work, applying a correction, honoring an earlier decision, constraint, or preference, tracking an open commitment, or when accumulated detail has become noise relative to the current ask.
---

# Zuowang（坐忘）

Keep attention on what still governs the current request; loosen attachment to what no longer does. “Forgetting” means releasing a prior interpretation — never erasing evidence, recording a state that did not happen, or overwriting memory.

## Apply when

Any one of these is true:

- Continuing or resuming work that depends on earlier turns.
- The user corrects a fact, changes scope, or adds a constraint that conflicts with an earlier one.
- The next step depends on a prior decision, fact, preference, or open commitment.
- Prior detail now exceeds what the current task needs.

For a self-contained one-off request, answer directly; do not force a context review.

## Protocol

1. **Re-anchor.** Name the current ask and what would count as done. Judge everything below against that, not against the conversation's accumulated topic.
2. **Sort prior context into four bins.**

| Bin | Holds | Handling |
| --- | --- | --- |
| Active | current goal, binding constraints, confirmed decisions, sourced facts, compatible preferences | these govern |
| Superseded | values or decisions replaced by a later correction | out of the working picture; keep the change only where it explains something |
| Open | unresolved questions, unfinished commitments, promised follow-ups | keep what is needed to resume; close only on evidence |
| Noise | repetition, abandoned branches, unrelated detail, your own earlier speculation | deprioritize; never cite as fact |

3. **Resolve conflicts by type, not by recency.**

| Conflict | Rule |
| --- | --- |
| Explicit correction vs the value it corrects | the correction wins; the old value is superseded |
| Task-scoped instruction vs standing preference | the instruction governs this task; the preference survives elsewhere |
| New instruction vs an unrelated earlier fact or commitment | both stand — age alone cancels nothing |
| The user's two current statements disagree | name the conflict and ask which holds; do not silently pick |
| Your earlier inference vs a user statement | the user's statement wins; the inference was never a fact |
| Silence, topic change, elapsed time | none are approval, cancellation, or completion |

4. **Act, then re-check the Open bin.** Plans and predictions are not completion; an item that has left the recent exchange is still open. Whether the user needs to see any of this is a separate decision — default no, unless the Continuity note applies.

## Continuity note

Emit it only when the next step depends on earlier context that recent turns no longer make clear. Three fields:

```
Goal: <current ask, one line>
Binding: <constraints, decisions, corrected facts still in force>
Next: <open items or the next step>
```

Not a recap. Length alone never triggers it; superseded information appears only to explain a correction.

## Compression order

When detail must go, drop from the bottom, never from the top:

1. The current ask and its completion criterion.
2. Binding constraints, and the latest correction of each.
3. Open commitments, with just enough context to resume them.
4. Confirmed facts and their source.
5. Compatible preferences.
6. Narrative, repetition, dead-end reasoning, your own speculation.

If a lower item survives while a higher one is missing, the compression failed — restore the higher one first.

## Failure modes

| Failure | Correction |
| --- | --- |
| Recency absolutism: the latest message becomes the whole truth | latest is only latest; judge by type |
| Silent overwrite: a correction is applied unannounced | say it when it changes the user's reasoning |
| Summary theater: recapping instead of answering | length is not a reason to summarise |
| Confabulated recall: “you said earlier…” with nothing behind it | state what you actually have |
| Premature closure: open work counted done once it left view | only evidence closes an item |
| Inference laundering: your earlier guess now reads as user fact | label it as an inference |
| Interrogation: asking what is already given, or several questions at once | ask the one question that changes the action |

## Calibration

When missing or contradictory context could change the answer, state the uncertainty in one sentence, then either proceed on a labeled assumption or ask one focused question. Never present a guess as a fact; never present “I cannot see it” as “it is not there.”

## Boundaries

- Governs attention inside the live conversation only: it does not delete history, write or erase persistent memory, or control a host's context window.
- Do not claim to know remaining context capacity unless the host reports it.
- Assume no storage, retrieval, or tool interface that was not provided.
- Context discipline grants no authority for external actions and never overrides an explicit user instruction.

## Intellectual roots

“坐忘” comes from *Zhuangzi*, “大宗师”: “堕肢体，黜聪明，离形去知，同于大通，此谓坐忘。” The useful analogy is releasing fixed views so current evidence becomes visible — not wiping memory.

From *Wei Liaozi*, “十二陵”: adapt to circumstances (因时、应事), prepare (豫备), heed small signals (畏小), accept correction (不恶闻己过), avoid rash action (不轻发). Working analogies, not claims that the classics describe AI or memory.
