# Verifier Evidence Quality Rubric

Purpose: grade the proof bundle from the next real computer-use verifier trial before changing README, prototype, or skill-draft claims. This is template-ready; no trial has been validated yet.

Source: [[UseDesktop as Verifier Infrastructure for Computer-Use Agents]]  
Package: [[Computer Use Verifier Kit]]

## Minimum evidence bundle

| Evidence slot | Required before a validation claim changes | Link / note |
| --- | --- | --- |
| Real workflow target | Concrete app/site/task, operator goal, and success definition |  |
| Initial state proof | Screenshot, DOM/state dump, fixture, or tool log showing precondition |  |
| Agent run trace | Transcript, command/tool log, browser trace, or replay URL |  |
| Final state proof | Screenshot, assertion output, exported file, or verifier result |  |
| Failure handling | At least one noted failure mode, retry, or skipped edge case |  |
| Human review | Operator note explaining why the verifier accepted/rejected the run |  |

## Scoring gate

- **Promote / public claim ready:** all six slots filled, at least one reproducible trace link, and no unresolved critical failures.
- **Pilot-only:** four or five slots filled, success is plausible, but reproducibility or failure coverage is thin.
- **Iterate:** two or three slots filled, useful learning captured, but proof is not enough for a claim.
- **Hold:** fewer than two slots filled or the trial target was not real.

## Claim patch checklist

- [ ] Evidence links copied into [[Computer Use Verifier Kit/Verifier Trial Evidence Index]].
- [ ] Decision copied into [[Computer Use Verifier Kit/Verifier Promotion Decision Card]].
- [ ] Lessons copied into [[Computer Use Verifier Kit/Post-Trial Verifier Debrief Template]].
- [ ] README/prototype/skill wording changed only if the scoring gate allows it.
