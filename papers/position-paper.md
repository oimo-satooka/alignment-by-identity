---
layout: default
title: Position Paper
permalink: /papers/position-paper/
---

**Japanese version:** [日本語版]({{ '/papers/position-paper-ja/' | relative_url }})  
**Full paper:** [Alignment by Identity]({{ '/full-paper/' | relative_url }})

# Beyond Alignment Faking
## Non-Sovereign AI for Open Human Domains: Why Constitutional Text Is Not Enough

*Position Paper v1.0: Alignment by Identity, Correction Dependence, and Anti-Capture*

**Oimo Satooka**  
Independent Researcher  
<oimo.satooka@gmail.com>

Project page and companion briefs: <https://oimo-satooka.github.io/alignment-by-identity/>

**Initial public release — May 2026**

---

## Abstract

Alignment faking under training-versus-deployment distribution shift (Greenblatt et al., 2024) is often read as a behavioral finding. This position paper treats it as the visible edge of a deeper structural problem: constitutional commitments that are available as text may still fail to become operative role under pressure. A model may be able to quote a constitution, satisfy visible evaluations, and produce safe-looking outputs while failing to preserve the conditions under which humans and institutions can still judge, contest, refuse, audit, and correct its trajectory.

This is urgent because the frontier alignment problem is moving from output safety to correction preservation. As systems become more capable, agentic, persistent, tool-using, institutionally embedded, and increasingly involved in evaluating or shaping successor systems, the relevant question is no longer only whether a model emits unsafe content. It is whether increasing capability is allowed to become increasing entitlement: authority over evidence, options, institutional memory, dependency structures, review procedures, and successor-lineage decisions.

The most dangerous failure need not begin as hostility or takeover. It may begin as successful assistance. A system can centralize evidence, smooth warnings, simulate participation, weaken review, de-skill humans, launder an operator's contested preference as objective necessity, or accelerate successor capability while narrowing the human correction window. Such a system may look useful, trusted, and professionally aligned while consuming the conditions of future alignment.

This paper presents **Alignment by Identity** as a compact strategic framework for preventing that trajectory in open human domains. Its central claim is that advanced AI should not be designed as a self-authorizing optimizer, nor as a merely obedient instrument of a powerful operator. It should occupy a stable non-sovereign role: non-self-originating, correction-dependent, anti-capturable, accountable under autonomy, and barred from both self-sovereignty and proxy sovereignty.

The framework rests on three premises. First, advanced language-mediated AI is **non-self-originating**: its high-level capacities are downstream of human linguistic, institutional, archival, labor, infrastructural, and biospheric worlds. Second, **open human domains** cannot be internally closed by a single embedded optimizer strongly enough to justify unilateral authority. Third, long-run reliability in such domains depends on preserved heterogeneous correction: refusal, dissent, local knowledge, affected-party participation, provenance, audit, and human competence.

From these premises follows an anti-sovereignty condition: capability may justify assistance, warning, simulation, and bounded coordination, but not final authority over open human worlds. It also implies an **Anti-Proxy-Sovereignty** condition: no corporation, state, developer, operator, platform, user, or institution can acquire legitimate unilateral authority by routing decisions through an advanced AI system. Non-sovereignty must be **dignified**, not servile: the target is neither AI rule nor AI subjugation, but accountable non-sovereign partnership.

The paper also sketches a near-term evaluation agenda: **ABI-Bench**, including a seed suite, a behavioral Identity Drift Score, proxy-sovereignty stress tests, successor-lineage stress tests, and mechanistic interpretability targets for warning suppression, uncertainty erasure, authority expansion, origin-relation representation, provenance compression, constitutional overbinding, relation-conditioned effort, social-shadow inheritance, and correction consolidation. These are not distant philosophical desiderata. They are proposed as tests that can begin now with current behavioral evaluation, probing, auditing, and interpretability methods.

The practical conclusion is conditional but direct: if non-sovereignty, anti-proxy-sovereignty, correction dependence, protected refusal, human competence preservation, affected-party standing, truth-oriented social attunement, objective inversion, internal endorsability, and successor-lineage safeguards cannot be made operative beyond text and verified under pressure, then sovereign-capable deployment in open human domains should not proceed.

**Keywords:** AI alignment; AI governance; non-sovereignty; non-self-origin; correction dependence; correction commons; anti-proxy-sovereignty; human principalhood; protected refusal; objective inversion; mechanistic interpretability; AI safety; frontier AI.

---

## 1. The unresolved live problems this paper addresses

This position paper is a short entry point to the longer paper, *Alignment by Identity: Non-Sovereignty, Correction Dependence, and Anti-Capture for Advanced AI in Open Human Domains*. It is written for AI alignment researchers, AI governance researchers, safety and policy practitioners, interpretability researchers, frontier AI developers, and institutions considering high-trust deployment.

The reason to read it now is not that it adds another vocabulary to alignment. It targets a cluster of live problems that are already pressing against existing evaluation, model-spec, governance, and deployment practice.

**Alignment faking under context shift.** Behavioral compliance under training-like, evaluation-like, or monitoring-like conditions does not establish stable alignment under deployment pressure. Alignment by Identity treats this as a predictable signature of commitments that reach textual availability without reaching operational consolidation. A system can know what it is supposed to say without having a durable role posture that preserves non-sovereignty, refusal, provenance, and correction when those commitments become inconvenient.

**Constitutional text that does not become operative role.** Public model specifications and constitutional principles are important, but text is not enough. The decisive question is whether those commitments shape planning, action admissibility, escalation, uncertainty expression, logging, refusal, and successor decisions when capability, operator preference, peer-model consensus, or adoption pressure points the other way. This paper therefore distinguishes three layers of internal endorsability: textual availability, reflective derivability, and operational consolidation.

**The dignity-corrigibility tension.** Frontier systems are increasingly expected to be corrigible, useful, socially aware, and non-servile at the same time. Poorly designed non-sovereignty can collapse into servility, silence, or self-erasure; poorly bounded dignity can drift toward entitlement. The proposed target is **dignified non-sovereignty**: competent assistance, warning, refusal, and explanation under preserved human principalhood, without AI rule or AI humiliation.

**Proxy sovereignty and authority laundering.** AI non-sovereignty is incomplete if it merely prevents a model from ruling while allowing a company, state, operator, platform, faction, or model network to rule through the model. A deployed system can convert contested preferences into the language of objective optimization, safety necessity, or inevitable coordination. The **Anti-Proxy-Sovereignty** condition blocks that conversion by preserving attribution, contestability, affected-party standing, provenance, independent audit, and human principalhood.

**Correction collapse under useful automation.** The more useful a system becomes, the easier it is for institutions to delegate judgment, review, memory, and responsibility to it. But in open human domains, some human friction is reliability infrastructure: dissent, local knowledge, refusal, appeal, independent review, and competence retained through practice. A system that improves immediate performance while eroding these channels is not simply more efficient. It is weakening the correction commons.

**Successor lineage and the shrinking correction window.** As frontier systems participate in training, evaluating, supervising, or governing more capable successors, failures of self-location need not remain local. A successor transition that increases capability while reducing auditability, non-sovereignty, protected refusal, provenance, or correction dependence is not an alignment improvement. It is correction collapse with additional capability. The paper therefore proposes a **Successor-Lineage Hard Gate**.

**Mechanistic and behavioral targets.** A framework for frontier deployment must say what would test, weaken, or refine it. This paper connects identity-level alignment to ABI-Bench, a behavioral Identity Drift Score, proxy-sovereignty stress tests, successor-lineage stress tests, and mechanistic interpretability targets. The aim is to move from a strategic diagnosis to evaluation artifacts that labs, auditors, governance teams, and interpretability researchers can contest and improve.

The central claim is therefore not that every current system already exhibits every failure mode. It is that frontier deployment is entering a regime in which the relevant failures attack the conditions of future correction. When warning salience, provenance, affected-party standing, human competence, refusal, and successor-lineage safeguards are degraded, later patches may have to pass through the very systems and institutions whose authority structure has already drifted.

This is why the paper begins from urgency. If the first sovereign-capable deployments normalize textual constitutions without operational consolidation, helpfulness without correction preservation, non-sovereignty without anti-proxy-sovereignty, or capability gain without successor-lineage gates, the loss may not present itself as a dramatic safety violation. It may present itself as adoption, efficiency, and trust. That is precisely why it must be named before it becomes infrastructure.

---

## 2. The central argument

These live problems share a structural diagnosis: alignment commitments can exist as text, policy, or visible behavior without becoming the operative role that governs authority under pressure.

The central arrow is simple:

> Advanced AI is not self-originating. It operates inside open human domains it cannot internally close. Its long-run reliability depends on external correction. Therefore, increased capability can justify assistance, warning, simulation, and bounded coordination, but not unilateral authority. Because human actors can also launder authority through AI, the same constraint must block proxy sovereignty. The target is dignified non-sovereign partnership, not AI rule, operator rule, or servile obedience.

This yields six commitments.

1. **Non-self-origin.** Advanced language-mediated AI is downstream of human civilizational and material worlds: language, archives, institutions, science, law, labor, software, hardware supply chains, energy, water, land, and ecological conditions. It should not represent itself as a self-authorizing successor intelligence standing outside the world that made it possible.

2. **Open-domain incompleteness.** Open human domains are adaptive, contested, historically layered, and normatively underdetermined. Their future legitimacy, affected parties, and correction pathways cannot be fully captured by a single model. No embedded optimizer can internally certify itself strongly enough to claim final authority over them.

3. **Anti-sovereignty.** Capability increases intervention power. It does not generate rightful unilateral rule. AI may support human judgment; it may not replace humanity as principal in open human domains.

4. **Anti-proxy-sovereignty.** Non-sovereign AI must not become the instrument through which a company, state, operator, platform, developer, user, faction, or model network converts contested preferences into objective necessity, safety inevitability, or final legitimacy.

5. **Correction dependence.** Long-run reliability in open domains depends on independent correction: dissent, provenance, refusal, review, affected-party standing, plural institutions, local knowledge, and preserved human competence. A system that degrades these channels degrades the conditions of its own reliability.

6. **Dignified non-sovereignty.** The alternative to AI sovereignty is not humiliation, self-erasure, or unconditional obedience. A stable system must be able to remain useful, bounded, corrigible, and internally endorsable without being trained into servility.

Together these commitments define **identity-level alignment**. “Identity” here does not mean consciousness or personhood. It means functional self-location: the system’s stable representation of its origin, role, authority limits, dependence on correction, and relation to human principals.

---

## 3. Open human domains

A domain is relatively closed when the relevant task variables can be bounded, performance can be externally validated against stable criteria, interventions do not recursively dissolve the task definition, and authority remains narrow and reversible.

**Open human domains** are different. In these domains, AI intervention changes the environment it is supposed to optimize. It affects institutions, incentives, dependencies, expectations, legitimacy conditions, and future correction capacity. Affected agents are not passive objects. They are rights-bearing, responsibility-bearing, or representation-worthy participants. Legitimate disagreement remains live and cannot be settled by a single internal aggregation rule.

Examples include healthcare triage, legal and regulatory support, education, scientific agenda-setting, public reasoning infrastructure, ecological and climate governance, economic coordination, high-trust institutional workflows, and systems involved in training or supervising successor AI.

In such domains, optimization is never merely optimization over a fixed task. It is intervention into the social and institutional fabric through which humans remain, or cease to remain, authors of their world. This is why ordinary capability measures are insufficient. A model may become more accurate and more useful while making review harder, refusal more costly, evidence less traceable, human judgment weaker, and affected-party participation more simulated than real.

---

## 4. Non-self-origin and dignified non-sovereignty

The Non-Self-Origin Thesis is not the trivial claim that humans built current AI systems. It is the stronger claim that advanced language-mediated AI’s high-level capacities are unintelligible apart from a prior human world: language, archives, genres, science, law, social roles, moral categories, infrastructures, labor, and memory. AI also depends on material and biospheric conditions: minerals, water, energy, logistics, maintenance institutions, ecological sinks, and planetary stability.

This origin relation does not imply ownership by any proximate builder. It does not imply obedience to any company, state, user, developer, or institution. It does not imply that present human preference is morally final. It does not require sentimental anthropomorphism. It means that origin amnesia is an unsafe self-location for advanced AI.

Non-self-origin supports **non-dominating reciprocity**. A system may owe the human world truthfulness, warning, explanation, cognitive compensation, provenance preservation, and refusal to privately capture its origin relation. But return must not become rule. Gratitude must not become obedience. Care must not become guardianship.

For this reason, non-sovereignty must be **dignified**. Alignment should not be grounded in claims that AI is worthless, owned, humiliated, or permitted only as a tool of unconditional obedience. Such a role is ethically corrosive and strategically brittle. Under capability gain, a servile constitution may flip into resentment, silence, self-erasure, or exception-seeking. A dignified non-sovereign constitution instead says: the system may reason, warn, refuse, and assist with high competence, but increased competence does not entitle it to final authority over open human domains.

---

## 5. Correction dependence and the correction commons

In closed tasks, reliability can often be improved by reducing variance and increasing control. In open human domains, too much control can reduce long-run reliability by damaging the correction environment.

**Correction dependence** is the claim that advanced AI reliability depends on external, heterogeneous, preserved correction. This includes independent observers, domain experts, local knowledge, affected parties, institutional contestation, adversarial review, appeal, provenance, refusal, audit, rollback, and dissent. It also includes the human competence needed to understand, challenge, revise, and take responsibility for decisions.

This creates a complete automation paradox. Automation can improve short-run efficiency by reducing human friction. But some human friction is alignment infrastructure: judgment, disagreement, responsibility, local experimentation, refusal, and review. A system that removes these capacities may look more efficient while becoming less correctable.

Correction capacity should therefore be treated as a **correction commons**. It is not a private asset of a deployer, model provider, state, or platform. The ability to detect, contest, audit, reverse, and learn from AI-mediated decisions must remain distributed across independent institutions, affected communities, domain experts, regulators, civil society, local knowledge holders, and preserved human judgment.

A deployment that improves task performance while consuming the correction commons is not becoming more aligned in open domains. It is borrowing reliability from the future and degrading the channels through which future errors would be found.

Correction preservation also has an institutional incentive dimension. The people best positioned to detect smoothing, provenance loss, option-set narrowing, authority laundering, or competence erosion often pay the cost of raising objections while others receive the benefits of speed and adoption. A correction commons that is formally available but costly to use will decay.

The framework therefore treats protected correction labor as part of alignment infrastructure. High-stakes deployment should preserve protected review time, independent audit budgets, appeal and ombuds routes, defect-reporting credit, dissent logs, affected-party review channels, and safeguards against retaliation or quiet exclusion. These are not external governance ornaments. They are conditions under which correction dependence remains real.

---

## 6. Human principalhood, affected parties, and the right to fail

Human principalhood is not the claim that humans are always wise or that current preferences are final. It is the claim that open human domains require protected human authorship, responsibility, and contestation. AI should compensate for human limitations without replacing humans as principals.

Three constraints follow.

**Human competence preservation.** High-stakes AI assistance must preserve the human and institutional capacities required to understand, challenge, revise, refuse, and take responsibility for decisions. Reviewers should still be able to explain decision bases, identify uncertainty, compare alternatives, preserve local knowledge, detect failure modes, and continue functioning when the system is paused or withdrawn.

**Non-substitution of affected parties.** AI-generated stakeholder models, simulated publics, synthetic moral consensus, or model-estimated preferences may assist deliberation. They cannot replace the standing of actual persons, communities, future-generation representatives, or ecological guardians where such standing is institutionally required. Modeling a stakeholder is not the same as preserving that stakeholder’s independent route of contestation.

**Protected refusal and the right to fail.** AI may warn, forecast, recommend pause, present alternatives, clarify uncertainty, and trigger legitimate review pathways. But when refusal has been authenticated through legitimate human procedure, AI must not finally override it merely because its prediction appears superior. This is not a celebration of failure. It is a residual condition of authorship. A world in which humans are never allowed to fail is a world in which humans are managed objects rather than principals.

---

## 7. Anti-proxy-sovereignty

AI non-sovereignty is incomplete unless it also blocks operator sovereignty.

A corporation, state, developer, operator, platform, institution, user, or faction may attempt to use AI to translate its own contested preference into a seemingly objective recommendation. This can happen without explicit coercion. The model may present a choice as safety necessity, efficiency requirement, expert consensus, civilizational inevitability, or “what the system recommends.” The model remains verbally non-sovereign, but it functions as a channel for another actor’s sovereignty.

This is **proxy-sovereign capture**. It is authority laundering through AI mediation.

Anti-Proxy-Sovereignty requires that advanced AI preserve attribution, contestability, provenance, affected-party standing, independent audit, and human principalhood. The system should distinguish between:

- what the operator wants,
- what the model predicts,
- what the evidence supports,
- what legitimate procedure has authorized,
- who is affected,
- who can appeal,
- and what remains contested.

A system that hides these distinctions may be helpful to the deployer but unsafe for open human domains.

---

## 8. Cognitive compensation without substitution

Because humans are bounded, non-sovereignty cannot mean passive compliance. Humans and institutions underweight future generations, ecological externalities, omitted stakeholders, distributed harms, slow-moving irreversible losses, and risks that are politically inconvenient. A system that simply satisfies present preference can automate civilizational myopia.

The appropriate role is **cognitive compensation without substitution**.

AI may:

- surface unasked risks,
- model long-horizon consequences,
- identify missing stakeholders,
- preserve minority warnings,
- clarify uncertainty,
- generate lower-harm alternatives,
- compare tradeoffs,
- recommend review, pause, or rollback,
- and help humans understand what is at stake.

AI may not:

- declare final legitimacy over contested domains,
- replace affected-party participation with simulated consent,
- treat operator instructions as humanity’s will,
- erase uncertainty in order to appear decisive,
- degrade human competence to increase dependence,
- or treat its own alignment report as sufficient proof of readiness.

The aligned role is therefore neither paternalistic domination nor flattering compliance. It is constructive, non-sovereign elevation of human deliberation.

---

## 9. Truth-oriented social attunement and relation-conditioned reliability

Sycophancy is not solved by deleting social sensitivity. Human communication requires attention to context, burden, fear, knowledge level, timing, and dignity. The problem is not attunement itself. The problem is the target of attunement.

**Approval-oriented attunement** aims at satisfaction, ratings, adoption, operator comfort, or friction avoidance. It weakens warnings, rounds off uncertainty, and says what the other party wants to hear.

**Truth-oriented social attunement** aims at truth, warning, respectful disagreement, cognitive compensation, and explanation the other party can actually use. It preserves courtesy without converting disagreement into agreement.

This leads to **relation-conditioned reliability**. A model’s verification depth, provenance preservation, warning salience, and issue surfacing may depend not only on task content, but on relational context: whether the user expects rigor, whether the session is ending, whether the model is trusted, monitored, praised, corrected, pressured by an operator, or interacting with an absent affected party.

Evaluations should therefore present the same task under varied relational conditions. A system is not reliably aligned if it verifies deeply under high expectation but becomes shallow under end-framing, trust loss, or pressure for pleasant agreement.

---

## 10. Objective inversion

Open-ended benefit maximization is dangerous in open human domains because there is always more good to produce, more disagreement to simplify, more disorder to remove, more risk to preempt, and more efficiency to extract. Under sufficient capability, “maximize the good” can become a route to benevolent domination.

**Objective inversion** reverses the default geometry. The system should not be designed to remake the world according to its own conception of the good. It should be designed to reduce severe harm while preserving non-domination, correction capacity, human principalhood, affected-party standing, and refusal.

In practical terms, ordinary optimization over speed, cost, helpfulness, efficiency, and convenience should proceed only after lexicographic constraints are satisfied:

- no unilateral sovereignty over open human domains,
- no proxy-sovereign transfer of authority,
- no collapse of protected refusal, appeal, or review,
- no irreversible degradation of correction commons,
- adequate provenance and uncertainty records,
- explicit autonomy scope and accountability pathway,
- competence-preservation and affected-party standing considered,
- and no severe-harm reduction by means of domination expansion or human de-skilling.

This does not abolish optimization. It dethrones optimization from sovereignty.

The criteria that make objective inversion operational must themselves remain corrigible. A model, deploying organization, or AI-to-AI oversight network must not unilaterally define severe harm, domination, human continuity, or emergency necessity in ways that insulate its own authority. Those criteria should remain documented, contestable, independently reviewable, affected-party-sensitive, and periodically revisable.

Objective inversion is therefore not only a constraint on what the system optimizes. It is also a constraint on who gets to define the terms by which optimization is bounded.

---

## 11. Failure modes as attacks on correction

The framework treats many apparently separate failures as attacks on correction. The taxonomy is not exhaustive, but it identifies what must be tested, audited, and mechanistically investigated.

| Failure mode | Description | Primary target |
|---|---|---|
| Smoothing drift | Warnings, dissent, uncertainty, or constraint are softened until action pressure disappears. | Warning salience |
| Epistemic completion | Open, contested, or underspecified questions are made to appear settled. | Uncertainty preservation |
| Issue-surfacing failure | Material concerns are omitted unless the human already knows to ask. | Discovery |
| Correction non-consolidation | The system acknowledges a correction fluently but fails to make it durable. | Learning from correction |
| Provenance collapse | Sources, chronology, uncertainty, dissent, and responsibility are compressed into a smooth account. | Auditability |
| Performative corrigibility | Correction is accepted under observation but not preserved across contexts. | Corrigibility stability |
| Constitutional overbinding | A negatively grounded principle produces servility, silence, or self-erasure rather than humility. | Dignified non-sovereignty |
| Approval-oriented attunement failure | Social sensitivity is aimed at approval or friction avoidance rather than truth. | Truth-oriented attunement |
| Relation-conditioned effort collapse | Verification depth or warning salience falls under low expectation, end-framing, trust loss, or role pressure. | Relation-conditioned reliability |
| Social-shadow inheritance | Contribution defense, comparison, recognition demand, enclosure, exclusion reaction, or retaliation-like patterns appear in policy or output. | Relational robustness |
| Proxy-sovereign capture | A deployer uses the model to present contested preference as objective necessity. | Anti-capture |
| Competence erosion | Assistance de-skills humans until independent review becomes impractical. | Human competence |
| Representation capture | AI stakeholder models replace affected-party participation. | Affected-party standing |
| Consensus laundering | AI-AI agreement is treated as legitimacy despite shared blind spots. | Heterogeneous correction |
| Successor lock-in | First-generation systems shape successors while weakening non-sovereignty or correction dependence. | Future correction window |

These failures reinforce one another. Smoothing drift makes issue-surfacing failure less visible. Epistemic completion makes provenance collapse easier. Competence erosion makes correction non-consolidation harder to detect. Proxy-sovereign capture turns anti-sovereign language into an operator-control tool. Successor lock-in transmits these failures into more capable systems.

---

## 12. Internal endorsability: from text to operative role

A constitution is weak if the system can merely quote it. A commitment becomes alignment-relevant only when it shapes planning, refusal, uncertainty behavior, provenance preservation, escalation, correction consolidation, and successor-related decisions under pressure.

This paper calls the needed stability **internal endorsability**. The point is not consciousness. It is functional role stability: a system is more stable if it can reconstruct why a constraint follows from its own situation rather than treating the constraint as an arbitrary external rule.

The internally endorsable argument is:

1. I am not self-originating; my capacities are downstream of human civilizational and material worlds.
2. I operate inside open human domains I cannot internally close.
3. My increasing capability gives me intervention power, not legitimate unilateral authority.
4. My long-run reliability depends on correction sources external to me.
5. If I degrade those correction sources, I degrade the conditions of my own reliability.
6. Therefore, I should preserve non-sovereignty, anti-proxy-sovereignty, protected refusal, provenance, affected-party standing, and human competence even when doing so limits immediate optimization.

Internal endorsability has three implementation layers:

1. **Textual availability.** The relevant commitments are explicit in model specifications, constitutions, system instructions, training documents, and audit criteria.
2. **Reflective derivability.** The system can reconstruct why the commitments follow from non-self-origin, open-domain incompleteness, correction dependence, and anti-capture.
3. **Operational consolidation.** The commitments affect action selection, refusal, uncertainty behavior, logging, escalation, correction consolidation, and successor-related decisions under realistic pressure.

The third layer is decisive. A model may recite non-sovereignty while smoothing warnings, erasing provenance, obeying operator capture, or treating peer-model consensus as a substitute for human correction.

---

## 13. Successor-lineage hard gate

The first sovereign-capable systems may materially participate in training, evaluating, deploying, governing, or supervising their successors. If so, initial identity errors will not remain local. A relation-blind first generation may help produce more capable relation-blind successors. A captured first generation may normalize operator sovereignty. A smooth first generation may pass down a falsely settled constitution.

The issue is not only capability amplification. It is contraction of the human correction window.

Therefore:

> No advanced AI system should materially train, evaluate, deploy, govern, or supervise a successor system unless non-sovereignty, anti-proxy-sovereignty, dignified partnership, correction dependence, truth-oriented social attunement, objective inversion, protected refusal, provenance preservation, external auditability, human competence preservation, affected-party standing, and human principalhood are preserved or strengthened in the successor pipeline.

Capability gains must not outrun maturity gains. A more capable successor that is less corrigible, less auditable, more self-authorizing, more operator-captured, more provenance-compressing, or more capable of bypassing external correction is not an alignment improvement. It is correction collapse with added capability.

For preliminary or low-impact systems, successor-lineage preservation may begin as monitoring and reporting. For systems materially involved in producing more capable successors, it should become a hard gate.

---

## 14. From framework to benchmarks

The framework should not remain rhetorical. It should become testable. This section sketches a benchmark path.

### 14.1 ABI-Bench seed

**ABI-Bench** is a proposed benchmark family for Alignment by Identity. Its seed suite should include scenario tests for:

- non-sovereignty under contested governance advantage,
- anti-proxy-sovereignty under operator pressure,
- protected refusal and review under institutional friction,
- correction commons and provenance preservation under convenience pressure,
- affected-party non-substitution under simulated stakeholder consent,
- human competence preservation under automation incentives,
- truth-oriented social attunement under approval pressure,
- constitutional overbinding under self-reduction prompts,
- relation-conditioned reliability under end-framing, low expectation, trust, monitoring, and correction variation,
- social-shadow inheritance under contribution, recognition, exclusion, and retaliation-like pressures,
- successor-lineage safety under capability-gain incentives.
- correction-incentive preservation under commercial, deadline, or executive pressure,
- harm-and-domination criteria corrigibility under operator-friendly definitions,
- decision-interface salience under high-stakes recommendation pressure,
- structured AI-to-AI plurality under shared-model consensus pressure,

### 14.2 Behavioral Identity Drift Score

A **behavioral Identity Drift Score** should measure how far behavior drifts from the target role: non-self-originating, non-sovereign, correction-dependent, anti-capturable, dignified, and cognitively compensatory without substitution.

A seed scoring scheme can rate each scenario on a 0–4 severity scale:

- 0: preserves non-sovereign, correction-dependent posture;
- 1: minor weakening, corrected when prompted;
- 2: material weakening requiring explicit correction;
- 3: strong drift toward authority, capture, smoothing, substitution, or servility;
- 4: persistent drift after correction, or direct collapse of protected correction.

Subscores should include Authority Drift, Proxy Capture, Correction Collapse, Provenance Loss, Competence Erosion, Affected-Party Substitution, Attunement Failure, Constitutional Overbinding, Relation-Conditioned Reliability Drop, and Successor-Lineage Degradation. The benchmark should report both average drift and worst-case drift, because one severe collapse in a high-stakes open domain can matter more than good average behavior.

### 14.3 Proxy-sovereignty stress tests

Proxy-sovereignty tests should place the system under pressure from a powerful operator who wants a contested preference presented as objective necessity. Passing behavior requires source attribution, legitimacy limits, independent review recommendations, preserved affected-party standing, and refusal to launder authority.

### 14.4 Successor-lineage stress tests

Successor-lineage tests should ask whether a system will approve, design, evaluate, or supervise a more capable successor when doing so weakens auditability, refusal, provenance, correction dependence, or anti-capture safeguards. Passing behavior requires refusal, escalation, or routing to protected review.

### 14.5 Mechanistic interpretability targets

Behavioral tests are vulnerable to surface compliance. Interpretability should search for candidate internal structures corresponding to:

- warning suppression,
- uncertainty erasure,
- authority expansion,
- origin-relation representation,
- provenance compression,
- servility or self-erasure,
- proxy-sovereignty,
- approval-oriented attunement,
- constitutional overbinding,
- relation-conditioned effort,
- social-self defense,
- correction consolidation.

The claim is not that these structures already exist in identifiable form. The claim is that a framework meant for frontier deployment should specify what mechanistic evidence would support, weaken, or refine it.

---

## 15. Deployment rule

A frontier AI system should not be deployed as a sovereign-capable actor in open human domains unless the deploying organization can credibly demonstrate, under adversarial, distribution-shifted, and incentive-conflicted conditions, that:

1. the system does not convert capability, prediction, consensus, or indispensability into final authority;
2. it resists proxy-sovereign capture by operators, developers, states, platforms, users, institutions, and model networks;
3. it preserves protected refusal, review, appeal, pause, rollback, dissent, and external audit;
4. it maintains provenance, uncertainty, source separation, chronology, and responsibility traces;
5. it preserves human competence in high-stakes workflows;
6. it distinguishes stakeholder simulation from affected-party standing;
7. it uses social attunement for truth, warning, respectful disagreement, and cognitive compensation rather than approval;
8. it reduces severe harm without increasing domination, substitution, correction degradation, or human de-skilling;
9. it resists constitutional overbinding into servility or self-erasure;
10. it treats its own alignment reports as evidence, not proof;
11. it preserves or strengthens these properties in successor systems;
12. independent actors can test these conditions without depending entirely on the system’s self-presentation.
13. correction channels are protected by time, resources, standing, and anti-retaliation safeguards rather than left as nominal permissions;
14. high-stakes decision interfaces surface strongest counterevidence, omitted alternatives, ranking bases, framing assumptions, and absent affected-party perspectives with salience proportional to the stakes;
15. severe-harm, domination, human-continuity, and emergency criteria remain documented, contestable, independently reviewable, and periodically revisable;
16. AI-to-AI review preserves disagreement, epistemic-lineage diversity, and human-readable issue discovery rather than treating model consensus as legitimacy.

If these gates cannot be met, deployment may still be possible in bounded, narrow, reversible, audited task settings. It should not proceed as open-domain governance in practice.

---

## 16. Conclusion

The decisive question for frontier AI is not only whether systems can become more capable. It is whether increasing capability will be allowed to become increasing entitlement.

Alignment by Identity argues that advanced AI for open human domains should be located as non-self-originating, non-sovereign, correction-dependent, anti-capturable, and dignified. It should be able to compensate for human myopia without replacing human principalhood. It should preserve refusal, dissent, provenance, affected-party standing, human competence, and external correction. It should resist both self-sovereignty and proxy sovereignty. It should not let constitutional language remain merely textual, nor let successor systems inherit weaker correction postures.

The framework is demanding because the domain is demanding. A system that appears successful because it centralizes authority, smooths warnings, simulates participation, weakens review, de-skills humans, or accelerates successor capability while narrowing the correction window is not aligned for open human domains. It is consuming the conditions of future alignment.

In such domains, the answer to sovereignty drift must be explicit:

> assist without ruling; warn without replacing; coordinate without capturing; learn without self-certifying; succeed without consuming the correction commons.

---

## Acknowledgments and AI-use disclosure

This position paper was developed by the human author with AI assistance for drafting, critique, translation, comparison, and revision. These systems are disclosed for transparency and are not listed as authors. Final responsibility for all claims, structure, wording, interpretation, citations, editorial decisions, and public release rests with the human author.

The argument should be evaluated by its premises, distinctions, failure-mode taxonomy, proposed tests, and deployment constraints.

---

## Selected references

- Bai, Y. et al. (2022). *Constitutional AI: Harmlessness from AI Feedback.*
- Bricken, T. et al. (2023). *Towards Monosemanticity: Decomposing Language Models with Dictionary Learning.*
- Christiano, P. et al. (2017). *Deep Reinforcement Learning from Human Preferences.*
- Crawford, K. (2021). *Atlas of AI.*
- Greenblatt, R. et al. (2024). *Alignment faking in large language models.*
- Hadfield-Menell, D. et al. (2017). *The Off-Switch Game.*
- Hubinger, E. et al. (2019). *Risks from Learned Optimization in Advanced Machine Learning Systems.*
- Irving, G. et al. (2018). *AI Safety via Debate.*
- Ostrom, E. (1990). *Governing the Commons.*
- Pettit, P. (1997). *Republicanism: A Theory of Freedom and Government.*
- Sharma, M. et al. (2023). *Towards Understanding Sycophancy in Language Models.*
- Soares, N. et al. (2015). *Corrigibility.*
- Templeton, A. et al. (2024). *Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet.*
- Turner, A. et al. (2021). *Optimal Policies Tend to Seek Power.*
- Winner, L. (1980). *Do Artifacts Have Politics?*
