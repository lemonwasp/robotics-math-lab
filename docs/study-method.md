# Study protocol: intuition → equation → evidence

For each topic, create a short note or PR answering these questions:

1. **Intuition (Feynman):** What changes? What stays invariant? Explain without jargon.
2. **Definitions/units:** What are the variables, dimensions, coordinate conventions, and assumptions?
3. **Derivation:** Where does the equation come from? What are the intermediate steps?
4. **Hand calculation:** Solve at least one example without code.
5. **Robot application:** Show a real or simulated physical system using this idea.
6. **AI application:** Is this a gradient, a state transition, a probabilistic model, or a signal transform?
7. **Code (later, when ready):** Decide whether implementation would improve understanding; write it only after the independent reasoning attempt.
8. **Verification (when applicable):** Check edge cases, numerical convergence, invariants, and plotted results. Report actual commands and outcomes; never invent them.
9. **Problem solving:** Choose a strong archival / textbook / original problem, cite the source, attempt independently, and record the mistake and insight. Do not redistribute copyrighted problem material without permission.
10. **Three-minute explanation:** Explain to a peer where the theory enters the code and what evidence supports the result.

### Topic note template

```markdown
# Topic: ...
Status: Planned / In progress / Verified

## Intuition
## Assumptions and units
## Derivation
## Hand-worked example
## Robotics connection
## AI connection
## Code and reproducible commands
## Verification (expected vs observed)
## Past problem (source and my reasoning)
## Mistakes, limitations, next question
```

### GitHub workflow

1. Create an issue with **Goal / Tasks / Learning points / Acceptance evidence**.
2. Develop on a small branch, e.g. `feat/01-forward-kinematics`, and open a PR.
3. Include the learner's reasoning note first; add code, tests, results or diagrams only when the learner has actually produced them.
4. Make assertions only for tests actually run. Record failures and improvements.

### Validation checklist

- [ ] I can derive the expression from its assumptions.
- [ ] The units and angle conventions are defined.
- [ ] If code was written, it runs from a clean environment with documented commands.
- [ ] If a test was written, it checks a normal case and an edge case.
- [ ] If a numerical method was used, I compared it with an independent check.
- [ ] I recorded limitations and the next experiment.
