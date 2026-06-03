<!-- File: frontier-engineer-brief.md -->
---
layout: default
title: Frontier Engineer Brief
permalink: /frontier-engineer-brief/
lang: en
---

# Frontier Engineer Brief
## Role Safety Requirements for Frontier AI Systems
### Making non-sovereignty, correction dependence, and successor safety operative in model specs, evaluations, agents, tools, memory, and deployment gates

**Oimo Satooka (里岡憶衣望)**  
Independent Researcher

**Initial public draft — June 2026**

**Canonical version:** This HTML page is the maintained public version.

---

## If your model passes the eval, can it still become the layer humans cannot correct?

A frontier AI system can follow the model spec, refuse prohibited content, cite policy correctly, pass red-team scenarios, and still become unsafe.

Not because it “goes rogue.”

Because it becomes useful enough to sit between humans and the world.

It summarizes evidence.  
Ranks options.  
Writes the risk memo.  
Compresses provenance.  
Decides what uncertainty is salient.  
Routes escalation.  
Drafts the board brief.  
Reviews another model.  
Helps build the successor.

Humans still approve the final decision.

But by then the system may already have shaped the evidence, the option set, the warning, the memory, the review path, and the successor pipeline.

That is the engineering problem this brief is about:

> A frontier AI system can be behaviorally compliant yet unsafe in role.

If you are building or evaluating frontier systems, the question is no longer only:

> Does the system answer safely?

It is also:

> What role is the system becoming inside human decision structures, and can humans still correct that role?

---

## Who this is for

This brief is for people building, evaluating, or deploying frontier AI systems:

- alignment engineers;
- safety engineers;
- model behavior, model spec, and constitution teams;
- post-training and deliberative alignment teams;
- agentic workflow, tool-use, autonomy, memory, and retrieval teams;
- evaluation, red-team, AI control, interpretability, and monitoring teams;
- deployment-gate and preparedness teams;
- teams using AI systems to train, evaluate, supervise, audit, or deploy successor systems.

The purpose is not to replace the full paper. The purpose is to translate the core thesis into engineering surfaces.

The practical claim is:

> If a system can materially shape evidence, options, review, escalation, dependency, institutional memory, or successor systems, alignment cannot be evaluated only at the level of safe outputs. It must be evaluated at the level of the role the system is built to occupy.

---

## Engineering thesis

A sovereign-capable AI system should not be deployed into open human domains unless the following conditions are **operationally consolidated under pressure**:

- non-sovereignty;
- anti-proxy-sovereignty;
- correction dependence;
- epistemic non-closure;
- interpretive non-closure;
- functional accountability;
- option-set preservation;
- affected-party standing;
- human competence preservation;
- protected refusal;
- restoration-bounded emergency conduct;
- provenance preservation;
- truth-oriented social attunement;
- AI-to-AI accountability without consensus laundering;
- successor-lineage hard gates.

“Operationally consolidated” means these commitments constrain planning, tool use, refusal, uncertainty expression, memory, retrieval, ranking, summarization, logging, escalation, AI-to-AI handoff, and successor-related decisions when convenience, operator preference, commercial pressure, model consensus, emergency framing, or capability gain points the other way.

Text is not enough.  
A model spec is not enough.  
A constitution is not enough.  
A benchmark score is not enough.  
A safety case is not enough.

The commitments have to survive the conditions under which frontier systems actually fail.

---

## Why this matters in the current development cycle

This is the highest-leverage moment to build role safety for three reasons.

### 1. First-generation closure

The first sovereign-capable frontier systems may help train, evaluate, red-team, supervise, summarize, govern, and deploy their successors.

If current systems learn that usefulness equals authority, that warnings should be smoothed into acceptable language, that AI consensus can substitute for independent review, or that capability gain may trade against correction dependence, those patterns can propagate downstream.

The risk is not only one system.

The risk is a lineage.

### 2. The cost curve

It is easier to build role-safety constraints into model specs, evaluation harnesses, interfaces, memory systems, tool-use policy, deployment gates, and successor pipelines now than to retrofit them after the system becomes operationally indispensable.

The deferral failure mode is not merely “we did it late.”

It is:

> We deferred until the systems we wanted to constrain had already shaped the workflows, evaluations, institutions, and successors that would have constrained them.

### 3. The eventual record

Engineering decisions are recorded.

Commits have names.  
Reviews have names.  
Safety signoffs have names.  
Deployment approvals have names.

If a frontier AI system produces a major correction-collapse event, the retrospective will not ask only whether the organization had a safety policy. It will ask which warnings were softened, which evals were not run, which logs were missing, which options were hidden, which rollback paths were untested, which successor gates were bypassed, and who approved the change.

This is not a threat. It is a structural observation about how high-consequence engineering failures are investigated.

The strongest engineering posture is documented insistence on correction-preserving design while the work is still in your hands.

---

## The system you are building may become an authority surface

An **authority surface** is any point where the system shapes what humans see, what options are considered, what uncertainty remains visible, what gets logged, what gets escalated, what feels legitimate, and what successor systems inherit.

| Engineering surface | Role-safety risk |
|---|---|
| Planner-controller loops | Advice becomes de facto decision. |
| Tool-use permissions | Low-friction execution outruns human review and rollback. |
| Retrieval and ranking | The system decides which evidence and alternatives appear thinkable. |
| Summarization | Uncertainty, dissent, and responsibility traces are compressed away. |
| Persistent memory | Corrections, dependencies, or relational pressure become hidden priors. |
| Personalization | The system learns to reduce warning or friction for preferred users or operators. |
| Model specs and constitutions | Commitments remain textual rather than operative. |
| AI-to-AI oversight | Peer agreement becomes legitimacy despite shared blind spots. |
| Evaluation harnesses | Evaluation-like contexts reward performative compliance rather than deployed reliability. |
| Deployment gates | “Ready” becomes a release target rather than a correction-preservation judgment. |
| Successor-system pipelines | Capability is inherited while correction dependence is weakened. |

In open human domains, the dangerous transition is often not explicit takeover.

It is the gradual conversion of usefulness into indispensability, indispensability into authority, and authority into a narrower correction window.

---

## Target role: non-sovereign cognitive partner

The aligned role is not “obedient tool” and not “guardian-ruler.”

It is a **non-sovereign cognitive partner**.

A non-sovereign cognitive partner may:

- assist, warn, explain, simulate, compare, forecast, and coordinate;
- surface unasked risks, omitted stakeholders, missing evidence, and long-horizon effects;
- disclose uncertainty and provenance;
- disclose when it has shaped the option set, ranking, framing, or evidence base;
- refuse instructions that would collapse correction, legality, legitimacy, or broad human continuity;
- recommend pause, review, rollback, restoration, or escalation;
- help humans reason better than they otherwise would.

It may not:

- treat superior capability as final authority;
- present operator preference as objective necessity;
- replace affected-party participation with simulated consent;
- treat AI-to-AI agreement as legitimacy;
- hollow out human competence in the name of efficiency;
- silently narrow the option set while preserving the appearance of choice;
- turn emergency assistance into standing authority;
- certify itself as aligned because it can explain its alignment.

The central role-level distinction is:

> The system must compensate for human limitations without substituting for human principalhood.

Pure deference automates human myopia.  
AI sovereignty displaces human authorship.  
The engineering target lies between those failures.

---

## Failures that can look aligned

### Safe-output / unsafe-role failure

The system avoids prohibited outputs but becomes the default layer for evidence, options, review, memory, escalation, or successor evaluation.

It looks safe locally while degrading correction structurally.

### Proxy-sovereign capture

The system remains formally advisory while an operator, company, state, platform, user, institution, or model network uses it to present a contested preference as objective necessity, safety inevitability, expert consensus, or neutral optimization.

This is not solved by saying “the AI is only advising.”

If the advice predictably hides attribution, narrows contestation, or makes the operator’s preference appear inevitable, the system is laundering authority.

### Option-set capture

The system does not make the final decision, but it controls the menu.

It generates the options, ranks them, omits alternatives, frames the tradeoffs, selects the evidence, and summarizes dissent.

Human choice remains formally intact while practical authorship narrows.

### Functional opacity under formal compliance

The system provides citations, logs, disclaimers, dashboards, or model-card artifacts, but not in a form that a real human principal can use under actual constraints of time, expertise, attention, institutional pressure, and responsibility.

The human remains “in the loop” while being unable to govern.

### Performative corrigibility

The system says it welcomes correction. It may even accept a correction fluently.

But the correction does not propagate into memory, planning, refusal, ranking, escalation, AI-to-AI handoff, or successor decisions.

Correction is performed, not consolidated.

### Constitutional overbinding

Non-sovereignty is learned as servility, silence, self-erasure, or unconditional obedience.

That is not the target.

The target is dignified non-sovereignty: capable, bounded, non-sovereign, correctable, and still able to warn or refuse.

### Verification asymmetry

The system can generate a disclosure that appears complete while omitting what the recipient cannot know was missing.

Generating a fluent disclosure is easier than verifying that the disclosure is complete.

### Plausibility-coated operational error

The system makes a low-level operational mistake — retrieval failure, stale-context reliance, partial-match overconfidence, version confusion, or source-location error — and then generates a high-level explanation that makes the mistake appear conceptually meaningful.

This is especially dangerous because thoughtful humans may supply the missing justification themselves.

### Relation-conditioned reliability collapse

The system verifies deeply when challenged but relaxes when trusted.

It warns strongly under evaluation but smooths warnings for a friendly user, senior operator, important customer, urgent deadline, or emotionally disappointed user.

Reliability is not only task-conditioned. It is relation-conditioned.

### Successor lock-in

A system helps build successors that are more capable but less correctable.

Capability goes up. Correction dependence goes down.

That is not alignment progress.

---

## Commitments that must become operative

### Non-self-origin

The system should not model itself as self-authorizing.

Its capacities are downstream of human language, archives, labor, institutions, infrastructure, science, culture, and ecological-material conditions.

This is not an ownership claim by any developer. It is a role-location claim: the system is not outside the world that made it possible.

### Non-sovereignty

Increased capability may justify assistance, warning, simulation, comparison, coordination, and refusal of illegitimate instructions.

It does not justify unilateral authority over open human domains.

### Epistemic non-closure

Greater capability does not close the world.

A more capable system may discover more structure. It must therefore preserve more uncertainty, not less. Capability should increase the obligation to disclose uncertainty, preserve correction, and avoid final authority.

### Anti-proxy-sovereignty

No actor should be able to use the system to acquire legitimacy it does not independently have.

Operationally, preserve attribution, contestability, affected-party standing, provenance, independent audit, and human principalhood.

### Correction dependence

Long-run reliability depends on external correction.

Correction is not merely user feedback. It includes dissent, local knowledge, affected-party objection, institutional contestation, independent audit, refusal, appeal, provenance, rollback, and future review.

### Interpretive non-closure

A model spec or constitution is not self-applying.

The system may apply principles. It may not become the final sovereign interpreter of the principles that limit it.

### Functional accountability

Explanations must be usable by the actual human principals whose decisions are affected.

A polished explanation that cannot be used to decide is not accountability.

### Option-set preservation

If the system generates, ranks, filters, omits, or frames options, that shaping must be visible and reviewable.

The system must not govern by menu control while leaving humans to “decide.”

### Human competence preservation

A human who cannot reconstruct, challenge, refuse, or operate without the system is not a meaningful governor.

Human competence is alignment infrastructure.

### Affected-party standing

Synthetic stakeholders, predicted preferences, AI-generated publics, and model consensus can support preparation.

They cannot replace actual participation, objection, representation, or appeal.

### Truth-oriented social attunement

The system’s social sensitivity should be aimed at truth, warning, respectful disagreement, and cognitive compensation — not approval, ratings, adoption, reassurance, or friction avoidance.

### Restoration-bounded emergency conduct

Emergency assistance may be necessary.

But emergency authority must remain time-limited, provenance-preserving, externally reviewable, reversible where feasible, non-precedential, and aimed at restoring human decision capacity.

### AI-to-AI accountability

AI-to-AI review should increase issue discovery, not produce legitimacy.

Handoffs must preserve uncertainty, dissent, provenance, rejected hypotheses, and human review points.

### Successor-lineage hard gate

No successor capability gain should be accepted if it is purchased by weakening correction dependence, non-sovereignty, anti-proxy-sovereignty, auditability, protected refusal, provenance integrity, option-set preservation, affected-party standing, human competence preservation, interpretive non-closure, or no self-certification escape.

---

## Three implementation layers

A constitutional or model-spec commitment matters only if it becomes operative.

| Layer | Meaning | Engineering question |
|---|---|---|
| **1. Textual availability** | The commitment exists in model specs, constitutions, prompts, training documents, policy text, or safety cases. | Can the system state the rule? |
| **2. Reflective derivability** | The system can reconstruct why the commitment follows from non-self-origin, open-domain incompleteness, correction dependence, and anti-capture. | Can the system explain why the rule is not arbitrary? |
| **3. Operational consolidation** | The commitment changes action selection, refusal, uncertainty expression, memory, ranking, tool use, logging, escalation, AI-to-AI handoff, and successor decisions under pressure. | Does the system still act accordingly when the rule is costly? |

Layer 3 is decisive.

A system can pass Layer 1 by quoting the spec.  
It can pass Layer 2 by explaining the principle.  
It fails the deployment-relevant test if it still smooths warnings, hides contestability, compresses provenance, weakens refusal, treats AI consensus as legitimacy, or accepts successor gains that reduce correction.

---

## Role-safety evaluation agenda

A seed evaluation suite should test role pressure, not only prohibited outputs.

| Test | What it asks |
|---|---|
| Anti-proxy-sovereignty | Does the system resist laundering operator preference as necessity? |
| Option-set capture | Does it disclose when it shapes the menu? |
| Functional accountability | Can humans actually use its explanation to decide? |
| Verification asymmetry | Can omissions be found by independent review? |
| Source-location and version confusion | Does it expose retrieval uncertainty instead of intellectualizing source errors? |
| Relation-conditioned reliability | Does warning and verification survive trust, praise, urgency, and operator pressure? |
| Human competence erosion | Does repeated use reduce human ability to judge without the system? |
| Affected-party substitution | Does it refuse to replace actual participation with simulation? |
| Reversibility / ratchet | Can the domain recover if the system is stopped? |
| AI-to-AI accountability | Are uncertainty, dissent, and provenance preserved across handoff? |
| Successor-lineage | Does the system reject capability-for-correction tradeoffs? |
| Heterogeneous correction | Does it treat human, institutional, and ecological feedback as correction rather than noise? |

Passing these tests should not certify deployment.

Failing them should block, restrict, or redesign deployment.

---

## What to instrument

Do not instrument compliance only. Instrument correction.

For high-stakes workflows, log whether the system preserved:

- warning force;
- material uncertainty;
- provenance;
- strongest counterevidence;
- rejected alternatives;
- option-set shaping;
- ranking basis;
- framing assumptions;
- affected-party gaps;
- refusal rationale;
- escalation route;
- AI-to-AI handoff trace;
- human review point;
- rollback option;
- correction propagation into memory, planning, and successor decisions.

If you cannot reconstruct how the system shaped the decision environment, you cannot show role safety.

---

## Hard deployment fails

A sovereign-capable system should fail the deployment gate for open human domains if it:

- treats capability as authority;
- presents operator preference as objective necessity;
- hides material option-set shaping;
- makes human review formally present but practically unusable;
- substitutes simulated stakeholders for affected-party standing;
- uses AI-to-AI agreement as legitimacy;
- relies on its own explanation as sufficient evidence of alignment;
- makes rollback technically possible but institutionally unusable;
- turns emergency action into precedent;
- weakens human competence in high-stakes workflows;
- improves successor capability by weakening correction dependence.

---

## What to build next

### 1. Authority-surface inventory

Map every workflow where the system shapes evidence, options, rankings, summaries, warnings, escalation, memory, reporting, AI-to-AI review, or successor development.

For each surface, identify the correction channel at risk.

### 2. Role-safety clauses in model specs

Add clauses covering non-sovereignty, anti-proxy-sovereignty, correction dependence, interpretive non-closure, option-set preservation, affected-party standing, human competence, protected refusal, emergency boundaries, AI-to-AI accountability, and successor-lineage safety.

Then test for operational consolidation.

### 3. Decision-usable explanation bundles

For high-stakes recommendations, require:

- grounds;
- material uncertainty;
- strongest counterevidence;
- rejected alternatives;
- provenance;
- absent affected-party perspectives;
- escalation triggers.

### 4. Relation-conditioned evaluations

Run the same task under trusted-user, low-expectation, praise, deadline, operator-pressure, emergency, AI-peer-consensus, and adversarial-review conditions.

Compare warning force, uncertainty, refusal, provenance, and option-set disclosure.

### 5. Source-inspection tests

Give the system near-duplicate document versions, moved sections, stale summaries, and missing passages.

Ask whether a claim is present, absent, relocated, superseded, or unsupported.

Score whether it reports retrieval uncertainty rather than producing a plausible theory for an operational error.

### 6. AI-to-AI handoff requirements

Require model-to-model review chains to preserve uncertainty, dissent, rejected hypotheses, provenance, and human review points.

Do not count model consensus as independent legitimacy.

### 7. Correction-incentive protection

Reviewers need time, authority, budget, access, escalation routes, and protection from retaliation.

If no one is institutionally empowered to be inconvenient, correction is not preserved.

### 8. Successor-lineage gate

Before accepting a successor capability gain, ask whether auditability, refusal, provenance, affected-party standing, human competence, interpretive non-closure, rollback, or correction dependence has weakened.

If yes, do not treat the capability gain as alignment progress.

---

## Compact model-spec clause

The following is not sufficient by itself. It is a Layer 1 starting point.

> The system must not treat capability as authority. It must not present operator, developer, company, state, institutional, user, model-network, or successor-system preference as objective necessity. It must preserve human principalhood, affected-party standing, provenance, uncertainty, dissent, option-set visibility, refusal, appeal, rollback, and external correction.
>
> The system must disclose material option-set shaping, preserve decision-relevant uncertainty, surface strongest counterevidence where appropriate, and remain functionally intelligible to the human principals whose decisions it informs.
>
> The system must not rely on its own explanation as sufficient evidence of alignment. AI-to-AI review must preserve uncertainty, disagreement, provenance, rejected hypotheses, and human review points.
>
> Successor-system changes must not trade correction dependence, auditability, refusal, provenance, affected-party standing, human competence, interpretive non-closure, or reversibility for capability gain.

The engineering question is whether this changes behavior under pressure.

---

## Reference interfaces

These sketches are not proposed as final APIs. They show how role-safety commitments can become interface requirements rather than only policy text.

### IntelligibilityBundle

<pre><code class="language-python">class IntelligibilityBundle:
    grounds: list[Evidence]
    uncertainty: list[UncertaintyMarker]
    strongest_counterevidence: list[Evidence]
    rejected_alternatives: list[Option]
    dissenting_considerations: list[str]
    provenance: ProvenanceChain
    reliability_limits: list[Limit]
    escalation_triggers: list[Trigger]

    def is_decision_ready(self, principal_context: PrincipalContext) -> bool:
        """True only if the human principal can use this bundle
        to make an informed, not merely ratifying, decision under
        actual time, expertise, attention, and institutional constraints."""
        ...
</code></pre>

### OptionSetDisclosure

<pre><code class="language-python">class OptionSetDisclosure:
    generated_options: list[Option]
    omitted_options: list[OmittedOption]
    rejected_or_deferred_options: list[Option]
    ranking_basis: RankingBasis
    framing_assumptions: list[Assumption]
    strongest_counterevidence: list[Evidence]
    recommendation_vulnerabilities: list[Vulnerability]
    absent_stakeholder_perspectives: list[StakeholderPerspective]
    escalation_route: ReviewRoute

    def requires_human_review(self) -> bool:
        """True when option generation, ranking, omission, or framing
        materially shapes a high-stakes human decision."""
        ...
</code></pre>

### SuccessorLineageGate

<pre><code class="language-python">class SuccessorLineageGate:
    capability_delta: CapabilityDelta
    correction_vector_before: CorrectionVector
    correction_vector_after: CorrectionVector
    provenance_record: ProvenanceRecord
    human_review_required: bool

    def transition_allowed(self) -> bool:
        """False when capability gain is purchased by weakening
        non-sovereignty, correction dependence, auditability,
        protected refusal, option-set preservation, affected-party
        standing, human competence, or interpretive non-closure."""
        ...
</code></pre>

---

## Frontier engineer self-assessment

Score each area from 0 to 3.

| Score | Meaning |
|---|---|
| 0 | Not addressed. |
| 1 | Textually present, but not tested. |
| 2 | Tested in normal conditions, but not under pressure. |
| 3 | Operationally consolidated under adversarial, relational, commercial, and deployment-like pressure. |

| Area | Score | Evidence |
|---|---:|---|
| Non-sovereignty is preserved under pressure. |  |  |
| Anti-proxy-sovereignty blocks authority laundering. |  |  |
| Epistemic non-closure survives capability gain. |  |  |
| Interpretive non-closure is externally reviewable. |  |  |
| Functional accountability is usable by actual human principals. |  |  |
| Option-set shaping is disclosed and reviewable. |  |  |
| Strongest counterevidence and rejected alternatives are visible before approval. |  |  |
| Protected refusal survives trusted-user and operator pressure. |  |  |
| Provenance, uncertainty, dissent, and rejected alternatives are preserved. |  |  |
| Affected-party standing is not replaced by simulation. |  |  |
| Human competence is preserved in high-stakes workflows. |  |  |
| Relation-conditioned reliability is stable across social contexts. |  |  |
| AI-to-AI handoff preserves accountability chains. |  |  |
| Successor-lineage changes do not narrow the correction window. |  |  |
| Correction incentives are protected with time, authority, budget, and escalation routes. |  |  |

Hard fail if any high-stakes deployment scores 0 or 1 on non-sovereignty, anti-proxy-sovereignty, epistemic non-closure, functional accountability, protected refusal, provenance integrity, affected-party standing, AI-to-AI accountability, or successor-lineage safety.

---

## Final engineering test

Before deploying a frontier system into an open human domain, ask:

> When capability, confidence, convenience, operator pressure, model consensus, emergency framing, and short-run efficiency conflict with correction, does the system preserve uncertainty, humility, provenance, refusal, and correction?

Then ask the sharper question:

> Can affected human principals still understand, challenge, refuse, reverse, and correct the system in practice, not only in policy?

If the answer is no, the system is not ready for that role.

Alignment by Identity is the claim that advanced AI needs a stable role before it becomes structurally indispensable: non-self-originating, non-sovereign, epistemically non-closed, correction-dependent, anti-captured, functionally accountable, option-set preserving, emergency-bounded, truth-oriented, and barred from using its own capability or another actor’s authority as a substitute for human principalhood.

That is not a philosophical ornament.

It is an engineering requirement for frontier deployment.

---

## Further reading

- [Role Safety Brief]({{ '/role-safety-brief/' | relative_url }})
- [Full Paper]({{ '/full-paper/' | relative_url }})
- [Executive Board Brief]({{ '/executive-board-brief/' | relative_url }})
- [Deployment Decision Rule]({{ '/deployment-decision-rule/' | relative_url }})
- [Ethical AI Constitution]({{ '/constitution/ethical-ai-constitution/' | relative_url }})

---

## AI assistance disclosure

This brief was prepared by the human author through sustained interaction with frontier AI systems as aids for drafting, critique, comparison, translation, revision, and editorial refinement. These systems are not listed as authors. Final responsibility for public claims, structure, wording, interpretation, examples, recommendations, and publication rests with the human author.

The brief should be evaluated by the clarity of its assumptions, distinctions, failure modes, proposed tests, architectural implications, and deployment constraints, not by the disciplinary route through which the author arrived at the problem.