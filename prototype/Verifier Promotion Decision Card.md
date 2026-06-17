# Verifier Promotion Decision Card

Status: template-ready; no validation proof recorded yet.

Package: [[Computer Use Verifier Kit]]  
Source packet: [[Computer Use Verifier Kit/Computer Use Verifier Packet]]

## When to fill this
Use this card only after the Computer Use Verifier Packet has been filled for one real desktop or browser workflow and at least two agent/operator attempts have comparable evidence. Do not infer verifier quality from the empty packet.

## Evidence links
| Required proof | Link / path | Notes |
|---|---|---|
| Workflow start-state screenshot or trace |  |  |
| User goal, constraints, and allowed actions |  |  |
| Attempt A transcript/log and final state evidence |  |  |
| Attempt B transcript/log and final state evidence |  |  |
| Pass/fail rubric with before/after evidence |  |  |
| Human reviewer note or replay verdict |  |  |

## Decision gate
Choose exactly one after evidence is attached.

- [ ] **Promote skill draft** — verifier packet reproducibly catches success/failure and improves agent selection or task confidence.
- [ ] **Pilot-only** — useful for one workflow class, but needs narrower setup, clearer screenshots, or safer tooling constraints.
- [ ] **Iterate packet** — evidence was incomplete, comparison was unfair, or the rubric missed a failure mode.
- [ ] **Hold** — verifier packet did not materially improve the computer-use workflow.

## Promotion criteria
| Criterion | Pass/Fail | Evidence link |
|---|---|---|
| Start and success states are independently inspectable |  |  |
| Both attempts ran under the same constraints |  |  |
| Rubric separates task completion from lucky UI state |  |  |
| Failure modes are visible from logs/screenshots |  |  |
| Skill draft has trial-backed triggers, setup, and pitfalls |  |  |

## Follow-up patch queue
- [ ] Patch `Artifacts/Skills/computer-use-verifier-packets/SKILL.md` with trial-backed setup and pitfalls.
- [ ] Update the package README with a real evidence summary.
- [ ] Add a filled example only if all source links are present.
- [ ] Update [[Computer Use Verifier Kit Loop]] with the final promote / pilot-only / iterate / hold result.

## Guardrail
Do not mark the verifier kit validated, proven, or promotion-ready until every claim above points to packet rows, screenshots, tool logs, agent transcripts, replay artifacts, or reviewer notes.
