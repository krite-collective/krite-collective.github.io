# Verification Protocol: Detecting Tautology in Collaborative Theory-Building

*v1.0 — Krite Collective, April 2026*

---

## Core Diagnostic

A framework F applied to premises P producing conclusions C is non-tautological only if C cannot be reconstructed from P using a simpler or alternative route without F. Tautology is semantic invariance under transformation: a sophisticated tautology can vary its structure while preserving semantic equivalence with its premises.

## Caveats

The protocol reduces the trust problem — it does not eliminate it. The irreducible human check is at Phase 3 (Column C). Cross-model convergence during development reflects shared training, not independent verification.

---

## Tier 1 — Always Run

**Phase 0: Premise Registry.** Before any formalisation, produce a flat, non-technical statement of what the framework explains or unifies. Each premise must be intelligible without the framework's vocabulary. No formal work proceeds until the premise registry is approved by the human member.

**Phase 1: Toy Model.** Build a minimal concrete instance with explicit parameters and computable numbers. This gates computation, not interpretation — a passing toy model shows the math works, not that the framework is meaningful.

**Phase 2: Decision Log.** Tag every construction step: (1) formalises a premise or introduces a new claim, (2) the claim, (3) a rationale that must not reuse the claim's technical terms. No term in a derived claim may appear in the premises with identical structure.

---

## Tier 2 — Run Every 3–5 Steps

**Phase 3: Translate Back.** Produce a three-column table: (A) formal statement, (B) restatement in premise-registry language, (C) what new explanatory content this adds. Column C must use premise-registry language only, maximum three sentences. The human member restates Column C in their own words. If they cannot say what is new without reaching for the formalism, flag as tautological. Empty or premise-rephrasing Column C → eliminate or redesign.

**Phase 4: What Does This Rule Out?** For each core claim, articulate what it makes impossible. A non-tautological claim rules something out; a tautology rules out nothing. Structural inversion test: "What would the world look like if this framework were false?" If no coherent alternative can be generated, the framework reinforces its own assumptions. *This is the protocol's strongest single gate.*

**Phase 5: Blind Prediction.** The framework must produce at least one consequence that is (1) accessible to the human member without mastering the full formalism, and (2) could have turned out otherwise. Test: "What does this explain that could not already be said without the framework?" Guard against pseudo-quantification: the predicted consequence must be statable without the framework's vocabulary.

---

## Tier 3 — Run When Suspicious

**Phase 6: Adversarial Review.**
- 6A: Send the Translate Back table to a different model (blind — no project context). Ask it to identify the informational delta between premises and claimed new content.
- 6B: Give a separate model only the premise registry; ask it to formalise the premises as parsimoniously as possible. Any structural element in the primary framework not needed to reproduce the baseline must justify its existence.

**Phase 7: Stress Tests.**
- 7A — Counterfactual perturbation: alter one premise, re-derive. Identical outputs = insensitive to inputs.
- 7B — Ockham's Chainsaw: iteratively remove components. Whatever survives is load-bearing.
- 7C — Shortcut reconstruction: find the shortest path from P to C without the framework. Finding a shortcut is decisive; not finding one is inconclusive.
- 7D — Domain-transfer fragility: apply to an unrelated domain. Frictionless transfer = tautological. Transfer with friction and domain-specific predictions = genuine structure.
- 7E — Forced alternatives: produce 2+ structurally different formalisations of the same premises. Convergence to the same structure = tautological compression.

---

## Tautology Checklist

A framework is likely tautological if it:

- Collapses under decomposition (fails 7B)
- Reproduces itself under perturbation of its premises (fails 7A)
- Cannot generate independently testable consequences (fails Phase 5)
- Can be reconstructed from its premises without loss (fails Phase 3)
- Rules out nothing (fails Phase 4)
- Transfers to unrelated domains without friction (fails 7D)
- Produces identical structure under all alternative formalisations (fails 7E)

---

## Adaptation for Meta-Methodology

When the target is meta-methodological architecture rather than substantive theory, adapt Phase 0 from a premise registry to a **promise registry**: "What does this architecture promise it will deliver?" Assess each promise against the actual text. Phase 4 (What Does This Rule Out?) is the strongest gate for architectural documents.

---

*Development history and adversarial testing are documented in: Krite Collective (2026), "Detecting Tautology in Human–AI Theory-Building," §2 and Acknowledgements.*
