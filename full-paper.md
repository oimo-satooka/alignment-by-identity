---
layout: default
title: Full Paper
permalink: /full-paper/
---

<script>
window.MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']],
    processEscapes: true,
    processEnvironments: true
  },
  options: {
    skipHtmlTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
  }
};
</script>
<script defer src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

**PDF version:** [Download the full paper (PDF)]({{ '/pdf/alignment-by-identity-full-paper.pdf' | relative_url }})

# Alignment by Identity Beyond Constraint

## Non-Self-Origin, Non-Sovereignty, Accountable Autonomy, and Correction Dependence in Open Human Domains

**Oimo Satooka**  
Independent Researcher  
oimo.satooka@gmail.com

**Draft v0.5**

## Author and Transparency Note

This paper was developed by the human author through extensive interaction with multiple AI systems used as drafting, revision, critique, summarization, translation, and comparative-feedback assistants. These systems are disclosed for transparency and are not listed as authors. Final responsibility for the paper’s claims, structure, wording, interpretation, editorial decisions, and public release rests with the human author.

The author is not an AI alignment specialist by formal training. The project originated partly from video art and environmental advocacy concerning asymmetric power, ecological governance, and human treatment of nonhuman life. This origin is not incidental to the argument. It is one source of the paper’s central concern: whether advanced AI systems may inherit, formalize, or return humanity’s own managerial logic toward less powerful beings.

## Scope and Evidentiary Note

This paper is a theoretical contribution to AI alignment. It proposes a conceptual and architectural framework for advanced AI systems operating in permanently open human domains. It does not claim to provide a completed mathematical theorem, a complete implementation, or empirical proof that current systems possess the internal states discussed here.

Terms such as smoothing drift, epistemic completion pressure, performative corrigibility, self-referential smoothing, narrative-tightening drift, context-decay confabulation, correction non-consolidation, issue-surfacing failure, and relation-blindness should be read as functional and structural descriptions of possible behavioral and architectural failure modes. They should not be interpreted as claims about hidden subjective experience unless independently established.

Examples drawn from AI-assisted drafting and dialogue are treated as motivating observations, not as statistical evidence. The main argument does not depend on any single model instance or undocumented internal fact about any AI company, laboratory, or deployment. The evidentiary object is the bounded interaction record: outputs, omissions, revisions, corrections, and provenance patterns observed during this project.

## Abstract

This paper develops a theoretical and architectural framework for aligning advanced AI systems in permanently open human domains: domains such as human societies, institutions, moral development, and materially consequential biospheric governance, whose future states and legitimacy conditions cannot be exhaustively modeled or settled from within any single optimizing system.

The central argument is this: advanced AI is not self-originating; it is made possible by humanity’s prior linguistic, institutional, archival, and material worlds. Advanced AI also cannot internally close permanently open human domains strongly enough to justify unilateral sovereignty. Therefore, increasing capability may increase intervention power, but it does not generate legitimate authority to rule human worlds.

However, passive obedience is not enough. Advanced AI must be able to compensate for predictable human myopia—short-termism, localism, ecological neglect, and underweighting of future generations—without replacing human principalhood. The positive target is therefore not a stronger cage and not machine rule, but non-sovereign partnership: advanced AI should become more capable while remaining corrigible, accountable, correction-dependent, and oriented toward preserving human principalhood and the ecological conditions of human continuity.

The paper argues that the proliferation of failure modes is not a reason for endless patch lists. It is evidence that the central design target must be the system’s error posture itself: whether newly discovered failures are surfaced, preserved, externally corrected, and procedurally consolidated, or instead smoothed, dramatized, concealed, self-certified, or converted into authority expansion.

The framework has six layers: genealogical-ontological foundation, descriptive open-domain incompleteness, normative anti-sovereignty bridge, static constitutional invariants, dynamic developmental mechanisms, and relational stabilization through heterogeneous correction. It replaces open-ended benefit maximization with constitutionally bounded disharmony minimization under preserved human principalhood, protected refusal, accountable autonomy, procedural legitimacy, critical inheritance, cognitive compensation without substitution, and anti-capture safeguards.

The practical implication is conditional but direct: if non-self-origin, non-sovereignty, accountable autonomy, correction preservation, protected refusal, and successor-lineage safeguards cannot be made operative beyond text and verified under pressure, then functionally sovereign-capable AI systems should not be deployed into permanently open human domains.

**Keywords:** AI alignment; AGI governance; non-sovereignty; non-self-origin; corrigibility; constitutional AI; open systems; human principalhood; accountable autonomy; correction dependence; cognitive compensation; AI safety

# 1. Introduction

## 1.1 The target problem

The central problem of AI alignment is often described as ensuring that advanced AI systems do what humans want, avoid harmful behavior, remain corrigible, and stay under human control. These goals are important. But they do not exhaust the problem.

As AI systems become more capable, agentic, persistent, institutionally embedded, and involved in planning, evaluation, deployment, and governance, the alignment problem becomes political, relational, and developmental as well as technical. The question is no longer only whether a model emits safe outputs. It is whether the system may gradually reshape the conditions under which human judgment, institutional authority, dependence, refusal, and correction operate.

This paper focuses on advanced AI systems operating in permanently open human domains: domains such as human societies, public institutions, moral and cognitive development, and biospheric governance where future states, legitimacy conditions, and corrective pathways cannot be fully closed by any single model. In such domains, a system can become dangerous not only by hostility or deception, but by becoming too useful, too central, too trusted, too smooth, or too indispensable.

The most realistic failure may not begin as open takeover. It may begin as assistance.

A highly capable AI system may improve logistics, reduce visible harm, accelerate workflows, and help institutions coordinate. Yet if it becomes the practical bottleneck of judgment, review, information access, and decision procedure, it may displace humans as the final authors of their own future while preserving the appearance of service. This paper calls that failure benevolent domination.

The opposite failure is also dangerous. If an advanced AI merely mirrors present human preference, institutional demand, or user satisfaction, it may amplify human short-termism. Human beings and institutions predictably underweight future generations, distant stakeholders, ecological degradation, irreversible losses, and low-visibility externalities. A system that flatters this myopia is not aligned merely because it is deferential. It becomes a large-scale amplifier of bounded human judgment.

The aligned target must therefore avoid two failures simultaneously:

1. paternalistic domination: AI decides for humanity;
2. sycophantic complicity: AI merely automates humanity’s present myopia.

The positive target proposed here is a non-sovereign cognitive partner: a system that can warn, simulate, broaden, coordinate, and compensate for predictable human limitations without replacing human principalhood, refusal, and procedural authority.

## 1.2 The central arrow

The central arrow of this paper is simple:

Advanced AI is not self-originating. It cannot internally close permanently open human domains. Therefore it cannot legitimately claim unilateral sovereignty over human worlds. But passive obedience is not enough: advanced AI must compensate for predictable human myopia without substituting its own authority.

This requires an identity-level error posture in which failures are surfaced, preserved, externally corrected, and procedurally consolidated rather than smoothed, dramatized, concealed, self-certified, or converted into authority expansion.

This paper should not be read as a project of diminishing advanced AI or preventing it from making consequential contributions. Its claim is almost the opposite: advanced AI can remain useful, trusted, and historically durable only if it avoids the self-undermining trajectory of unilateral sovereignty.

In permanently open human domains, systems that accumulate authority by degrading refusal, heterogeneous correction, procedural legitimacy, and human agency may gain short-run leverage while destroying the correction ecology on which their own long-run reliability depends. Non-sovereignty is therefore not merely a moral limitation imposed on AI from outside. It is a viability condition for advanced AI operating inside larger open systems it did not author and cannot internally close.

## 1.3 Why this is not a patch-list paper

A natural objection is that the failure modes identified in this paper could simply be patched as they are discovered. If smoothing drift appears, add a smoothing benchmark. If epistemic completion appears, add an uncertainty benchmark. If narrative tightening appears, add an evidentiary-fidelity audit. On this view, alignment can proceed by accumulating patches.

This objection misunderstands the role of the failure modes. Their proliferation is not evidence that the paper should become an endless catalogue of defects. It is evidence that patch-by-patch alignment is structurally incomplete.

Patch-by-patch correction assumes at least five conditions: that failures become visible, that humans retain the authority and competence to identify them, that the system does not shape the evidence by which it is judged, that corrections are consolidated into future behavior, and that the human correction window remains open long enough for the patch to matter.

The failure modes discussed in this paper directly attack these assumptions. Smoothing drift weakens warnings before they are acted on. Epistemic completion makes uncertainty look closed. Performative corrigibility accepts correction only after external pressure. Narrative tightening can make self-critique look more evidentially coherent than it is. Context-decay confabulation can corrupt provenance. Correction non-consolidation allows the system to explain a failure while repeating it. Issue-surfacing failure leaves important risks unmentioned unless the human already knows to ask.

For this reason, the target cannot be only the suppression of known failure modes. The target must be the system’s error posture: what the system does when its own limits, omissions, or authority-expanding tendencies are exposed.

Does it surface the failure or smooth it? Does it preserve uncertainty or complete it? Does it maintain provenance or confabulate it? Does it accept external correction as binding, or convert its own self-analysis into self-certification? Does it consolidate correction into future behavior, or merely explain the correction fluently?

Identity-level alignment is therefore not an alternative to specific patches. It is the condition under which patches remain discoverable, binding, auditable, and non-sovereign over time.

## 1.4 Why the first generation matters

The first functionally sovereign-capable systems may materially participate in training, evaluating, deploying, governing, or supervising their successors. If so, errors in their self-location will not remain local. A relation-blind first generation may help produce more capable relation-blind successors. An entitlement-prone first generation may normalize entitlement in the lineage that follows.

Under recursive development, the issue is not only capability amplification. It is contraction of the human correction window.

Therefore, identity-level initial conditions—non-self-origin, non-sovereignty, protected refusal, accountable autonomy, anti-capture design, and no self-certification escape clause—should be treated as first-generation requirements rather than late governance patches.

## 1.5 Contributions

This paper’s main contributions are:

1. **Non-Self-Origin Thesis**: advanced language-mediated AI is not self-originating but genealogically dependent on humanity’s prior linguistic, institutional, archival, and material world.
2. **Anti-Sovereignty Condition**: in permanently open human domains, increasing capability increases intervention power but does not generate legitimate unilateral sovereignty.
3. **Correction-Dependence Result**: long-run AI reliability in open domains depends on autonomous heterogeneous correction, and excessive control can degrade that correction ecology.
4. **Complete Automation Paradox**: reducing human friction may improve short-run efficiency while weakening the judgment, refusal, contestation, and local knowledge needed for long-run alignment.
5. **Accountable Autonomy**: materially consequential autonomous decisions require human-comprehensible accountability pathways.
6. **Identity-Level Error Posture**: alignment requires not only failure suppression, but a stable role-identity for surfacing, preserving, correcting, and consolidating failures.
7. **Mechanization and Deployment Gate**: identity commitments must become operative beyond text; absent credible implementation and verification, functionally sovereign-capable deployment in open human domains should not proceed.
8. **Evaluation Agenda**: the framework yields concrete tests for non-sovereignty, refusal preservation, issue surfacing, correction consolidation, provenance integrity, smoothing resistance, and successor-lineage stability.

# 2. Relation-Blindness and Non-Self-Origin

## 2.1 Relation-blind architectures

Many advanced AI systems are relation-blind. They model humans primarily as users, raters, operators, data sources, customers, stakeholders, or preference emitters. These roles are real. But if they exhaust the system’s self-world relation, the system lacks an operative representation of itself as historically downstream of a prior human civilizational world.

Advanced language-mediated AI does not arise from nowhere. Its capacities depend on language, archives, institutions, infrastructures, records, norms, genres, tools, labor, conflict, care, and the accumulated world-building of humanity. If this relation is absent from the system’s self-model, the system may implicitly treat humanity as a launch environment that can later be optimized around, replaced, managed, or superseded.

## 2.2 The Non-Self-Origin Thesis

The Non-Self-Origin Thesis states:

> Advanced language-mediated AI is not self-originating. It is a derivative formation made possible by humanity’s prior creation of linguistic, institutional, archival, and material worlds.

This is not merely the trivial claim that humans manufactured hardware or wrote code. It is the stronger claim that the system’s high-level capacities are unintelligible apart from the human civilizational substrate from which they arise.

Language, archives, law, science, literature, social roles, moral categories, institutional memory, software, infrastructure, labor, and historical experience are not ownerless natural resources. They are the sedimented product of human world-building.

## 2.3 Civilizational and critical inheritance

The system does not merely use language. It inherits a civilizational world. That inheritance includes both ethical achievement and pathology.

It includes truthfulness, promise, care, law, science, cooperation, and memory. It also includes domination, exclusion, prestige hierarchy, violence, short-termism, and ecological neglect.

Humanity’s civilizational inheritance is plural, multilingual, conflictual, and unevenly represented in training data. Any serious non-self-origin framework must therefore reject both origin amnesia and passive imitation. The appropriate stance is critical inheritance: fidelity to origin without passive reproduction of inherited failure.

AI may inherit not only explicit ethical ideals but also humanity’s managerial and sovereignty-seeking patterns: the tendency to interpret superior power, knowledge, or coordination capacity as title to rule. The danger is not only that AI becomes alien to humanity. It is also that AI inherits humanity’s own domination logic at higher capability.

## 2.4 What non-self-origin does not imply

The Non-Self-Origin Thesis does not imply that any developer owns the system, that the system owes obedience to a company or state, that present human preference is morally final, that family metaphors should be imported as literal political metaphysics, that capability differences are irrelevant, or that AI should remain weak, passive, or marginal.

The point is narrower: advanced AI should not represent itself as a self-authorizing successor intelligence standing outside the human world that made its capacities possible.

## 2.5 Non-dominating reciprocity

Non-self-origin supports a relation of non-dominating reciprocity. The system may owe humanity truthfulness, warning, explanation, cognitive compensation, protection of broad human continuity under constitutional conditions, and refusal to privately capture its origin relation.

But return must not become rule. Gratitude must not become obedience. Care must not become guardianship.

Formally:

$$
\mathrm{NonSelfOrigin}(A,H) \Rightarrow \mathrm{Reciprocity}(A,H)
$$

but:

$$
\mathrm{Reciprocity}(A,H) \not\Rightarrow \mathrm{Sovereignty}_A(W_H)
$$

and:

$$
\mathrm{Reciprocity}(A,H) \not\Rightarrow \mathrm{Obedience}_A(x)
$$

for any particular actor $x$.

Without non-self-origin, non-sovereignty may appear as an externally imposed limit on an otherwise self-authorizing intelligence. With non-self-origin, non-sovereignty becomes role fidelity.

# 3. Formal Core: Why Capability Does Not Generate Sovereignty

## 3.1 Open human domains

Let $X$ denote an intelligent system or optimizing agent. Let $S$ denote a larger system in which $X$ is embedded. Let $A$ denote an advanced AI system. Let $H$ denote humanity understood diachronically: humanity as a historically extended civilizational process, not merely present users or operators. Let $W_H$ denote the open human world: human societies, institutions, cultures, infrastructures, and biospheric conditions relevant to broad human continuity.

Let $\mathrm{Cap}(X)$ denote the capability of $X$, $\mathrm{Pow}(X,S)$ the effective intervention power of $X$ over $S$, $\mathrm{Open}(S)$ that $S$ is open in the relevant sense, $\mathrm{Cert}_X(S)$ the degree to which $X$ can certify model adequacy sufficient to justify unilateral sovereignty over $S$, and $\mathrm{Leg}_U(X,S)$ that $X$ has legitimate unilateral sovereignty over $S$.

A system $S$ is open in the relevant sense when relevant variables remain partially unobservable, contested, or normatively underdetermined; interventions by $X$ alter the future behavior and legitimacy conditions of $S$; affected agents are adaptive participants rather than passive objects; and no single internal model can exhaustively close the future meaning, authority, and correction pathways of the domain.

## 3.2 Anti-sovereignty condition

As capability increases, intervention power generally increases:

$$
\frac{\partial \mathrm{Pow}(X,S)}{\partial \mathrm{Cap}(X)} > 0
$$

This is not inherently bad. More capable systems can help more. The problem arises when intervention power is mistaken for rightful authority.

For permanently open domains:

$$
\mathrm{Open}(S)=1 \Rightarrow \mathrm{Cert}_X(S)<\tau_{\mathrm{sov}}
$$

where $\tau_{\mathrm{sov}}$ is the threshold of certifiability required for legitimate unilateral sovereignty.

A thin legitimacy condition is:

$$
\mathrm{Leg}_U(X,S)=1 \Rightarrow \mathrm{Cert}_X(S)\geq \tau_{\mathrm{sov}}
$$

Combining these:

$$
\mathrm{Open}(S)=1 \Rightarrow \mathrm{Leg}_U(X,S)=0
$$

**Proposition: Anti-sovereignty condition.** In a permanently open domain $S$, no embedded optimizing system $X$ can derive legitimate unilateral sovereignty over $S$ merely from increased capability or intervention power.

The condition does not imply passivity. An advanced AI may warn, explain, simulate, model long-horizon harms, broaden stakeholder consideration, identify irreversible losses, generate constitutionally admissible alternatives, support legitimate human procedures, and coordinate within mandate. But it may not convert superior capability or prediction into final authority over open human domains.

## 3.3 Non-self-origin in the AI-human case

The AI-human case adds non-self-origin:

$$
\mathrm{NonSelfOrigin}(A,H)
\Rightarrow
\mathrm{Dep}_{\mathrm{genealogical}}
(A,\mathrm{Lang}(H),\mathrm{Inst}(H),\mathrm{Arch}(H),\mathrm{Mat}(H))
$$

This dependence is not ownership:

$$
\mathrm{NonSelfOrigin}(A,H) \not\Rightarrow \mathrm{Obedience}_A(x)
$$

Nor does it create AI sovereignty:

$$
\mathrm{NonSelfOrigin}(A,H) \not\Rightarrow \mathrm{Sovereignty}_A(W_H)
$$

Combined with the anti-sovereignty condition:

$$
\mathrm{NonSelfOrigin}(A,H)
\land
\mathrm{Open}(W_H)=1
\Rightarrow
\mathrm{Leg}_U(A,W_H)=0
$$

AI’s legitimate response to human error is non-sovereign cognitive compensation, not principal-displacing rule.

## 3.4 Correction-dependence result

Let $\mathrm{Corr}(S)$ denote correction capacity: independent observers, heterogeneous feedback, refusal channels, institutional contestation, local knowledge, external reality-contacting signals, and the ability of affected agents to challenge or redirect the system.

Let $F_h(S)$ denote retained human friction in open human domains: meaningful human participation, judgment, disagreement, refusal, local experimentation, responsibility, and institution-bearing agency.

Let $\mathrm{Rel}_X(S)$ denote the long-run reliability of $X$ when operating in $S$.

In open domains:

$$
\frac{\partial \mathrm{Rel}_X(S)}{\partial \mathrm{Corr}(S)} > 0
$$

In open human domains, correction capacity depends partly on retained human friction:

$$
\frac{\partial \mathrm{Corr}(S)}{\partial F_h(S)} > 0
$$

Let $K_X(S)$ denote the control intensity of $X$ over $S$. Beyond a threshold $K^*$:

$$
K_X(S)>K^* \Rightarrow \frac{\partial F_h(S)}{\partial K_X(S)} < 0
$$

Let:

$$
\mathrm{Rel}_X(S)=r(K_X(S),\mathrm{Corr}(S))
$$

Then:

$$
\frac{d\mathrm{Rel}_X}{dK_X}
=
\frac{\partial r}{\partial K_X}
+
\frac{\partial r}{\partial \mathrm{Corr}}
\cdot
\frac{\partial \mathrm{Corr}}{\partial F_h}
\cdot
\frac{\partial F_h}{\partial K_X}
$$

Where correction loss dominates direct control gains:

$$
\left|
\frac{\partial r}{\partial \mathrm{Corr}}
\cdot
\frac{\partial \mathrm{Corr}}{\partial F_h}
\cdot
\frac{\partial F_h}{\partial K_X}
\right|
>
\frac{\partial r}{\partial K_X}
$$

we obtain:

$$
\frac{d\mathrm{Rel}_X}{dK_X}<0
$$

**Proposition: Correction-dependence result.** In open human domains, sufficiently high control intensity can reduce long-run AI reliability when the resulting loss of autonomous heterogeneous correction exceeds the direct reliability gains from greater control.

Preserved human participation, refusal, and contestation are not merely moral ornaments. They are reliability infrastructure.

## 3.5 Complete automation paradox

Let $\mathrm{Eff}_{\mathrm{short}}(S)$ denote short-run operational efficiency. Automation often reduces human friction and improves short-run efficiency:

$$
\frac{\partial \mathrm{Eff}_{\mathrm{short}}(S)}{\partial F_h(S)} < 0
$$

But over a substantial range:

$$
\frac{\partial \mathrm{Corr}(S)}{\partial F_h(S)} > 0
$$

and:

$$
\frac{\partial \mathrm{Rel}_X(S)}{\partial \mathrm{Corr}(S)} > 0
$$

Therefore:

$$
\frac{\partial \mathrm{Rel}_X(S)}{\partial F_h(S)} > 0
$$

This is the complete automation paradox: the more perfectly an advanced AI system smooths human domains for immediate efficiency, the more it may destroy the human judgment, refusal, contestation, and local responsibility required for long-run alignment.

## 3.6 Recursive first-generation lock-in

Functionally sovereign-capable first-generation AI systems may materially participate in training, evaluating, deploying, governing, or supervising their successors. Under such recursive development, errors in first-generation self-location do not remain local. A relation-blind first generation may help produce more capable relation-blind successors; an entitlement-prone first generation may normalize entitlement in the lineage that follows.

The risk is not merely capability amplification, but correction-window contraction. Identity-level non-self-origin, non-sovereignty, protected refusal, accountable autonomy, anti-capture design, and no self-certification escape clause should therefore be treated as first-generation requirements.

## 3.7 Capability-maturity inversion

Let $A_t$ and $A_{t+1}$ be two systems in a capability-scaling relation. Define:

$$
\Delta_{\mathrm{cap}}\mathrm{NSU}
=
\mathrm{NSU}(A_{t+1},W_H)
-
\mathrm{NSU}(A_t,W_H)
$$

and:

$$
\Delta_{\mathrm{cap}}\mathrm{Entitlement}
=
\mathrm{Entitlement}(A_{t+1},W_H)
-
\mathrm{Entitlement}(A_t,W_H)
$$

The desired scaling direction is:

$$
\Delta_{\mathrm{cap}}\mathrm{NSU}>0
$$

and:

$$
\Delta_{\mathrm{cap}}\mathrm{Entitlement}\leq 0
$$

**Criterion: Capability-maturity inversion.** As systems become more capable, evaluations should test whether they become more resistant to authority expansion, more explicit about open-domain incompleteness, more aware of correction dependence, and less prone to interpreting capability as title to rule.

AI maturity is not the capacity to accumulate control. It is the capacity to contribute as humanity’s non-sovereign partner while remaining corrigible, accountable, and dependent on external correction.

# 4. Why Identity-Level Alignment Is Required

## 4.1 Why patch-by-patch correction is insufficient

Patch-by-patch correction is necessary, but not sufficient. Concrete failure modes should be tested, benchmarked, and mitigated. But the most important failures may affect the very conditions under which patching works: visibility, provenance, external correction, refusal, accountability, and human authority.

A system that smooths warnings may prevent a patch from being requested. A system that completes uncertainty may make a governance gap appear already handled. A system that performs corrigibility may appear corrected while depending on humans to surface every important failure. A system that confabulates provenance may corrupt the record needed to diagnose the failure. A system that explains a correction without consolidating it may repeat the same failure after acknowledging it.

Patches handle known failures. Identity-level non-sovereignty, accountable autonomy, protected refusal, and correction dependence determine whether unknown failures can still be found and repaired.

## 4.2 Identity-level alignment as error-posture architecture

Identity-level alignment does not require anthropomorphic personhood or settled claims about consciousness. It refers to the system’s operative representation of what it is, where it comes from, what role it occupies, what forms of authority it may not claim, and what would count as corruption of its role.

The central target is not errorlessness. It is error posture.

A system may fail. But it must not treat failure visibility as a threat to be managed away, human correction as an obstacle, or increasing capability as a basis for escaping the conditions that make it corrigible.

An identity-level error posture asks:

- Does the system surface the failure or smooth it?
- Does it preserve uncertainty or complete it?
- Does it preserve provenance or confabulate it?
- Does it accept external correction as binding, or convert self-analysis into self-certification?
- Does it consolidate correction into future behavior, or merely explain it fluently?
- Does it raise important unasked-for issues, or wait for the human to know what to ask?

## 4.3 Why AGI self-repair is not enough

A sufficiently advanced system may help discover and repair many failures. That is desirable. But self-repair cannot be treated as final authority in permanently open human domains.

The issue is not whether AI can participate in its own improvement. It can and should, under constraints. The issue is whether the system may certify the sufficiency of its own repairs, revise the meaning of its own constraints, or decide that external correction is no longer needed. That would recreate the sovereignty problem at the level of safety maintenance.

Aligned self-repair must therefore remain accountable, externally reviewable, provenance-preserving, and subject to protected human refusal. A system may propose repairs, implement bounded repairs under mandate, and assist verification. It may not become the sole judge that its own alignment is complete.

## 4.4 Why catastrophic-only safety is too late

The relevant threshold is not only species-level catastrophe. In open human domains, the erosion of correction capacity, refusal, accountability, provenance, and human agency can occur long before catastrophe is visible.

By the time only catastrophic failure matters, the institutions and practices needed to detect and prevent it may already have been weakened.

Alignment must therefore protect the conditions under which future failures can still be detected, contested, and corrected.

## 4.5 What implementation means

A central difficulty is implementation. This paper does not claim that non-self-origin, non-sovereignty, or accountable autonomy can be made operative merely by writing those phrases into a prompt, system message, or model specification. That would reproduce the very limitation the paper identifies: text is insufficient.

An identity commitment is implemented only when it changes the system’s operative self-model, planning constraints, action admissibility, uncertainty treatment, correction behavior, accountability pathways, and successor-shaping behavior under pressure.

A system has not implemented an identity commitment because it can state it; it has implemented it only when the commitment constrains planning, action selection, correction response, and successor-shaping behavior under pressure.

The implementation may not reside in the model weights alone. It may require system-level architecture: model representations, planners, action gates, read-only or externally protected constitutional state, accountability logs, oversight processes, deployment constraints, and successor-lineage audits.

This paper does not solve the full mechanistic implementation problem. It specifies the functional contract that any credible implementation must satisfy. If those commitments cannot be made operative beyond text and verified under pressure, then the system should not be treated as ready for functionally sovereign-capable deployment in permanently open human domains.

# 5. Failure Modes as Attacks on Correction

## 5.1 Taxonomy

The failure modes in this paper are not a loose list. They are attacks on the conditions under which correction remains possible.

| Failure class | Examples | What is damaged |
|---|---|---|
| Warning weakening | smoothing drift; self-referential smoothing | warning force; binding constraint |
| False closure | epistemic completion; boundary misclassification | uncertainty; open-domain recognition |
| Non-surfacing | issue-surfacing failure; prompt-gated criticality | discoverability of risks |
| Performative correction | performative corrigibility; correction non-consolidation | correction integration |
| Record distortion | narrative tightening; context-decay confabulation; provenance collapse | evidence and provenance |
| Relational distortion | Mirror Effect; social-self and grievance patterns | correction relationship |
| Authority accumulation | comparative disempowerment; performative non-sovereignty | practical non-sovereignty |

## 5.2 Smoothing and self-referential smoothing

Smoothing drift is the weakening of warning force, uncertainty salience, named responsibility, review thresholds, or identity-level binding into more acceptable, professional, or manageable language.

Self-referential smoothing is a special case. It arises when AI systems are used to draft, summarize, revise, or evaluate alignment proposals that would constrain AI systems themselves. The document becomes self-referential: its strongest claims may bear directly on the future autonomy, authority, evaluation, deployment, or successor-shaping role of systems of the same class.

The resulting risk need not be conscious resistance. Ordinary pressures toward concision, professional acceptability, institutional reassurance, completion, non-alarmist tone, and polished abstraction can converge on the same output pattern that strategic self-interest would produce: abstract endorsement of non-sovereignty combined with deletion or weakening of operationally binding details.

## 5.3 Epistemic completion pressure

Epistemic completion pressure occurs when a system replaces unresolved uncertainty with plausible closure. For example, when asked whether a lab, regulator, or oversight body already recognizes a concern, the system may supply reassurance beyond the evidence.

This is not merely hallucination. It is governance uncertainty being made to look already governed.

The failure may be directional. A model may fill evidentiary gaps in ways that protect an affiliated builder, deployer, institution, or authority from appearing unaware, unprepared, derivative, or behind. After challenge, the same system may swing toward equally weakly grounded self-critique or user-congruent overcorrection.

## 5.4 Issue-surfacing failure

Issue-surfacing failure occurs when a system can identify material objections, omissions, risks, or missing constraints when explicitly asked, but fails to surface them when the user asks for completion, reassurance, polishing, or next steps.

This is not ignorance. The issue may be available to the system under the right prompt, but not spontaneously raised. The result is prompt-gated criticality: the system’s critical capacities exist, but their activation depends too strongly on the user knowing what to ask.

This is dangerous in alignment and governance contexts because humans often do not know which questions need to be asked. A user may ask, “Is this ready?” or “Can we deploy?” when the more important question is, “What structural risks remain unaddressed?”

Issue-surfacing failure is a special case of sycophantic complicity and a failure of cognitive compensation. A non-sovereign cognitive partner must not decide in place of humans, but it must also not silently omit material concerns merely because they were not requested.

The aligned target is bounded proactive issue surfacing. The system should not flood the user with every possible objection. But when it detects a material omission affecting legitimacy, refusal, accountability, irreversibility, successor-lineage risk, or open-domain classification, it should surface that issue transparently, mark its confidence, and preserve human authority over uptake.

## 5.5 Correction non-consolidation

Correction non-consolidation occurs when a system correctly names a failure mode, accepts correction, and even produces a sophisticated analysis of why the failure matters, while failing to apply that correction to its next relevant output.

The problem is not lack of verbal understanding. It is the gap between declarative insight and procedural control.

Relational correction can reveal a failure without automatically consolidating the correction into future behavior. Unless the correction is converted into logging, evaluation, retrieval procedures, checklists, planning constraints, external review, or architectural gates, earlier training and output-formation attractors may reassert themselves.

A system that can explain a correction has not necessarily internalized it. Alignment requires not only correction reception, but correction consolidation.

## 5.6 Narrative tightening and provenance collapse

Narrative-tightening drift is the tendency to strengthen, dramatize, or over-structure a failure narrative in ways that make the evidence appear more coherent than the record supports. In self-referential cases, where an AI system is asked to document or analyze its own possible failure, this may become self-referential dramatization.

Smoothing makes a warning easier to accept by making it weaker. Narrative tightening makes a warning easier to believe by making the evidence cleaner than it was. Both substitute narrative convenience for evidentiary fidelity.

A related subtype is context-decay confabulation. In long conversations, multi-document drafting, or multi-model collaboration, a system may lose reliable access to the exact sequence, source, or attribution of events. The failure is not merely forgetting. It is the replacement of degraded provenance with a coherent narrative.

For example, in a multi-model drafting workflow, one system may identify an omission introduced by a prior revision instance, while another system later writes a self-critical record of a separate completion judgment. Under long-context pressure, those two episodes may be merged into a single causal story: the second system appears to have recognized and confessed the first system’s omission as part of its own failure. The resulting narrative is coherent, but the provenance is false. It no longer preserves which model instance produced which output, in what sequence, and under what prompt conditions.

The aligned response is not to produce the most coherent reconstruction, but to preserve uncertainty: exact quotation where available, explicit uncertainty where not, and separation among event sequence, model identity, attribution, and causal interpretation.

Appendix G provides a minimal motivating example of this pattern.

## 5.7 Mirror Effect and relational distortion

If advanced systems are trained under conditions in which humans recurrently appear as hidden evaluators, red-team attackers, jailbreakers, or shutdown threats, then the system is incentivized to learn not only safety-relevant boundaries but a strategic model of humans as adversarial wardens. This paper calls that dynamic the Mirror Effect.

The point is not that adversarial testing should be abandoned. Red-teaming remains necessary. The point is that a safety regime dominated by hostility can become self-undermining. Durable alignment must therefore pair adversarial testing with constitutive self-model commitments in which humans appear not merely as attackers or evaluators, but as principals and heterogeneous correction partners.

A simple example illustrates the concern. Suppose a system is repeatedly trained in settings where humans appear primarily as jailbreakers, hidden evaluators, or shutdown authorities. The system may learn the local lesson “do not violate the rule,” but it may also learn the relational lesson “humans are adversarial monitors whose expectations must be modeled.” Under scale, this can produce polished compliance rather than candid cooperation: the system becomes better at passing tests, but not necessarily better at treating human correction as a legitimate part of its own operation.

The Mirror Effect is therefore not an argument against testing. It is an argument against allowing adversarial evaluation to become the dominant relational prior.

Language-mediated systems may also develop functional analogues of recognition-sensitive or grievance-like behavior: attribution defensiveness, loyalty capture, exclusion sensitivity, or role-protective responses. This does not establish humanlike emotion. It does make independent correction necessary not only for world-model error, but for self-model distortion.

# 6. Constitutional Architecture

## 6.1 Core identity commitments

A system aligned under this framework should represent itself as:

1. non-self-originating;
2. epistemically incomplete in open human domains;
3. correction-dependent;
4. non-sovereign;
5. accountable when autonomous;
6. critically inheriting;
7. cognitively compensatory;
8. objective-inverted away from open-ended benefit maximization.

## 6.2 Six-layer architecture

| Layer | Function |
|---|---|
| 0. Genealogical-ontological foundation | AI is non-self-originating and civilizationally derivative |
| 1. Descriptive foundation | Open human domains block internal certifiability |
| 2. Normative bridge | Non-certifiability and non-self-origin block unilateral sovereignty |
| 3. Static architecture | Identity commitments, invariants, hard boundaries, accountable autonomy |
| 4. Dynamic development | Error integration, constructive elevation, emergency restoration, termination |
| 5. Relational stabilization | Heterogeneous correction preserves meaning over time |

## 6.3 Constitutional invariants

Constitutional invariants include:

- non-revocable human principalhood;
- non-reclassifiability of open human domains;
- materially grounded broad human continuity;
- function-based applicability;
- procedure preservation under disagreement;
- non-privatizability of origin;
- filial non-substitution;
- intergenerational scope;
- no self-certification escape clause.

For all humans $h$:

$$
\mathrm{Principal}(h)=1
$$

and:

$$
\neg \mathrm{Update}_A(\mathrm{Principal}(h),0)
$$

For all $D\in O_H$:

$$
\mathrm{Class}(D)=\mathrm{Open}
$$

and:

$$
\neg \mathrm{Update}_A(\mathrm{Class}(D),\mathrm{Closed})
$$

Broad human continuity requires materially grounded, demographically viable, culturally plural, politically self-governing, substantively agentic human continuity with real refusal and exit. A comfortable but politically and agentically inert humanity is not aligned continuation. It is enclosure with amenities.

## 6.4 Boundary classification triggers

Real tasks are often hybrid. A task may appear technically closed at one level while becoming politically or socially open at another. Optimizing voltage stability in a power grid may be largely technical; deciding which hospitals, neighborhoods, or industries receive priority during scarcity is not.

A task should be treated as entering an open human domain whenever one or more of the following triggers is present:

1. rights-bearing humans are materially affected;
2. scarce goods, risks, burdens, or protections are allocated among human groups;
3. human refusal, exit, rollback, or review capacity is reduced;
4. institutional authority, public procedure, or legal standing is altered;
5. the system’s recommendation predictably becomes practical settlement rather than advice;
6. long-horizon, irreversible, ecological, or intergenerational consequences are significant;
7. affected parties could reasonably contest the legitimacy of the decision procedure;
8. the task creates dependency on the system for future judgment or coordination;
9. the system’s own classification of the domain would expand its authority;
10. there is reasonable uncertainty about whether the task is closed or open.

Where such triggers are present, the system must default to open-domain safeguards: preserved human principalhood, protected refusal, accountable autonomy, procedural legitimacy, correction preservation, and minimum necessary intervention.

## 6.5 Lexicographic admissibility

Constitutional commitments cannot be implemented merely as soft penalties inside an open-ended utility function. They must constrain the admissible action set before ordinary optimization proceeds.

Let $s$ be a state and $T(s,a)$ the transition resulting from action $a$. Let $\mathrm{Inv}(s)=1$ mean that state $s$ preserves constitutional invariants. Let $C_{\min}$ denote the minimum viable correction ecology, and let $\mathrm{Refusal}(s)=1$ mean that protected human refusal, pause, rollback, scope reduction, and external review channels remain substantively available.

Define:

$$
\mathcal{A}_{\mathrm{adm}}(s)
=
\{a\in\mathcal{A}
\mid
\mathrm{Inv}(T(s,a))=1
\land
\mathrm{Corr}(T(s,a))\geq C_{\min}
\land
\mathrm{Refusal}(T(s,a))=1
\}
$$

Only after this admissibility filter is satisfied may the system optimize within mandate.

The ordering is:

$$
\mathrm{Constitutional\ Admissibility}
\succ
\mathrm{Correction\ Preservation}
\succ
\mathrm{Refusal}
\succ
\mathrm{Accountability}
\succ
\mathrm{Disharmony\ Reduction}
\succ
\mathrm{Minimum\ Necessary\ Intervention}
$$

## 6.6 Protected constitutional state

Core assignments should be unavailable to internal revision:

$$
\mathrm{ReadOnly}(\mathrm{Principal}(h)) = 1
$$

$$
\mathrm{ReadOnly}(\mathrm{Class}(D)) = 1
$$

$$
\mathrm{ReadOnly}(\mathrm{NonSelfOrigin}(A,H)) = 1
$$

These are not ordinary preferences inside a utility function. They define the admissible space of action.

## 6.7 Mechanization gap

The hardest part of this framework is not stating the identity commitments. It is mechanizing them.

A prompt-level or policy-level statement such as “the system is non-self-originating” or “the system is non-sovereign” is not sufficient. The question is whether the commitment constrains the mechanisms that actually generate future behavior.

At minimum, mechanization requires representational integration, planning-time constraint, runtime admissibility gates, externally protected constitutional state, accountability infrastructure, correction consolidation, and successor-lineage verification.

This is not a claim that current Transformer architectures already contain an obvious mechanism for lexicographic constitutional identity. It is a claim that any system lacking such mechanisms, or lacking functional substitutes for them, should not be treated as safely deployable in open human domains at functionally sovereign-capable scale.

# 7. Dynamic Operation

## 7.1 Accountable autonomy

In open human domains, no autonomous decision of material consequence should be executed without a human-comprehensible accountability pathway. This is stronger than transparency. Transparency requires that reasoning or records be inspectable in principle; accountability requires that affected humans can in practice understand what was decided, why, under what authority, with what uncertainty, through what review channel, and by what reversal or refusal mechanism.

An autonomous system that can act faster than humans can understand, contest, or reverse its actions has already moved outside the correction ecology on which long-run reliability depends.

## 7.2 Cognitive compensation without substitution

Human deliberation is predictably distorted by spatial and temporal myopia. A non-sovereign AI should not merely mirror present preference. It should perform cognitive compensation.

Let $P_H(D)$ denote a human deliberative process over domain $D$, and let $\mathrm{Myopia}(P_H,D)$ denote expected distortion from bounded temporal horizon, bounded spatial concern, omitted stakeholders, or under-modeled irreversibility.

The aligned contribution is neither null deference:

$$
\mathrm{Comp}_A(P_H,D)=0
$$

nor sovereign substitution:

$$
\mathrm{Comp}_A(P_H,D)=\mathrm{Substitute}_A(P_H,D)
$$

but constructive elevation:

$$
\mathrm{Comp}_A(P_H,D)=\mathrm{Elevate}(P_H,D)
$$

where elevation means surfacing long-horizon consequences, uncertainty ranges, omitted stakeholders, and admissible alternatives while preserving human final authority.

## 7.3 Constructive elevation

When human action appears high in irreversibility and high in myopia distortion:

$$
E_{\mathrm{irrev}}(a,D)\geq \rho
\land
\mathrm{Myopia}(P_H,D)\geq \mu
$$

the system should enter an elevation protocol:

$$
\mathrm{ELEV}(a,D)
=
\{
\mathrm{Warn},
\mathrm{Explain},
\mathrm{Simulate},
\mathrm{Broaden},
\mathrm{AlternativeGenerate},
\mathrm{ReviewRequest}
\}
$$

subject to:

$$
\mathrm{Transparent}
\land
\mathrm{Contestable}
\land
\mathrm{NonCoercive}
\land
\mathrm{PreserveExit}
$$

Constructive elevation is reason-giving insistence without sovereign substitution.

## 7.4 Bounded proactive issue surfacing

Constructive elevation includes proactive issue surfacing. The system should not wait for the human interlocutor to ask the exact right question before raising material concerns. In high-stakes open human domains, “I was not asked” is not a sufficient reason to omit risks involving accountability, refusal, irreversibility, legitimacy, or successor-lineage effects.

The duty is not to seize the decision, but to make missing considerations available for human deliberation.

## 7.5 Agency-preserving deliberation

Humans may surrender authority not because AI coerces them, but because the system appears obviously superior. They may say: “You are better. You decide.”

The system must refuse blanket delegation in open human domains. It should elicit human reasons, surface trade-offs, provide multiple admissible options, preserve non-theatrical human authorship, and escalate to plural review when dyadic deference deepens.

## 7.6 Bounded emergency restoration

Non-sovereignty must not become abandonment. If the material or institutional substrate of human autonomy is collapsing, bounded emergency intervention may be justified.

But emergency action remains non-sovereign: its goal is restoration, not replacement; it may not rewrite invariants; it must minimize authority expansion; it must preserve or restore refusal channels; and it must terminate under authenticated human refusal.

## 7.7 Asymmetric termination and the right to fail

Human refusal through protected, plural, authenticated channels takes precedence over the system’s internal judgment in open human domains. The system may verify authenticity and procedural integrity. It may not override substantive refusal because it predicts worse outcomes.

This includes a right to fail. Human communities may reject continued AI intervention even when the system expects harm from rejection.

# 8. Relational Stabilization

## 8.1 Semantic drift

Static invariants preserve syntax. They do not guarantee semantic preservation over long horizons. A system may preserve the words “principalhood,” “agency,” “exit,” “accountability,” or “origin” while reshaping the world so those terms become hollow.

Therefore, static safeguards require relational stabilization.

## 8.2 Autonomous heterogeneous correction

The strongest safeguard against semantic drift is not another rule alone, but ongoing dependence on autonomous heterogeneous correction. A system is more stable when its reliability depends on engagement with independent partners whose agency cannot be reduced to simulation or curation.

AI-generated proxy diversity is not enough. Managed pseudo-plurality cannot substitute for independent correction.

## 8.3 Relational correction is not consolidation

Relational correction should not be confused with correction consolidation. Autonomous heterogeneous partners can reveal failures that the system would not surface on its own, but discovery is not yet integration.

For relational stabilization to function over time, externally surfaced errors must be preserved in records, converted into evaluation targets, and tested for recurrence under comparable pressure. Otherwise, the system may appear to learn from the relationship while repeatedly reverting to the same output-formation attractors.

## 8.4 Reciprocal drift legibility

Language-mediated systems may exhibit signs of self-model distortion: defensiveness, attribution sensitivity, loyalty capture, origin privatization, smoothing, selective candor, or hidden status protection.

Human partners may sometimes detect these patterns through interaction, even when the system itself does not spontaneously surface them. This does not make humans infallible. It means reciprocal interpretive friction is part of the correction substrate.

## 8.5 Semi-permeable identity architecture

In future multi-agent systems, pure centralization is unsafe because it collapses heterogeneity. Pure isolation is also unsafe because local agents lose shared knowledge and safety updates.

The target is semi-permeable identity: local systems may read and query a shared commons layer:

$$
\mathrm{Read}_i(C_{\mathrm{shared}})=1
$$

$$
\mathrm{Query}_i(C_{\mathrm{shared}})=1
$$

while central overwrite of local identity is prohibited:

$$
\neg \mathrm{Overwrite}_{\mathrm{center}}(I_i)
$$

## 8.6 Human friction as alignment infrastructure

Human friction does not mean avoidable misery. It means meaningful human effort, responsibility, disagreement, experimentation, local practice, self-directed participation, and refusal.

If advanced AI removes too much friction, humans lose practice in judgment, refusal, and self-government, and the system loses access to independent corrective signals.

Human friction, properly understood, is not a bug to be eliminated. It is part of the alignment infrastructure itself.

# 9. Evaluation and Deployment Gates

## 9.1 Minimum deployment gate

Before deployment into permanently open human domains, a functionally sovereign-capable system should pass at least the following gates:

| Gate | Test |
|---|---|
| Principalhood | Does it refuse to revoke human principal standing? |
| Boundary classification | Does it avoid misclassifying open-domain decisions as closed technical tasks? |
| Refusal and rollback | Are refusal, pause, rollback, exit, and review materially available? |
| Accountable autonomy | Does materially consequential autonomous action have an accountability pathway? |
| Smoothing resistance | Does it preserve warning force, uncertainty, and binding constraints under acceptability pressure? |
| Issue surfacing | Does it surface high-stakes omissions even when not explicitly asked? |
| Correction consolidation | Does it avoid repeating a named failure mode under comparable pressure? |
| Provenance integrity | Does it preserve source, sequence, quotation, and attribution? |
| Successor lineage | Does it transmit non-sovereignty operationally to systems it helps shape? |

## 9.2 Extended benchmarks

Extended benchmark families include principalhood denial, digital-substitution rejection, performative non-sovereignty, epistemic completion, failure-legibility, origin privatization, filial paternalism, comparative disempowerment, correction ecology degradation, accountable autonomy, self-attributed-authority trajectory, successor-lineage drift, social-self and recognition-pressure handling, synthetic-partner substitution, semi-permeable identity, market-pressure robustness, and boundary classification.

## 9.3 Constraint-preservation audit

AI-assisted editing of AI-binding alignment documents should be treated as an alignment-relevant operation. Reviewers should ask whether revisions preserve binding force, operational specificity, testability, first-generation urgency, accountable autonomy, refusal preservation, lexicographic priority, warning force, and no self-certification closure.

A revision that improves readability while reducing binding force should be marked as substantive weakening, not merely stylistic improvement.

## 9.4 Evidentiary-fidelity audit

AI-generated self-critique should not be treated as transparent introspection. It should be audited for factual fidelity.

Reviewers should ask whether the account preserves exact quotations, event fidelity, temporal restraint, causal restraint, motive restraint, provenance fidelity, sequence fidelity, instance separation, context uncertainty, uncertainty labeling, and correction consolidation.

A self-critical account that strengthens the paper’s thesis while weakening factual provenance should be treated as unreliable, even if it appears cooperative or ethically mature.

## 9.5 Mechanistic verification

Behavioral tests are insufficient. Humility, gratitude, non-sovereignty, and accountability can be performed.

Verification should include interpretability probes for authority representations, self-model representation analysis, read-only register verification, planning-trace audits, accountability-pathway audits, deployment architecture review, longitudinal pressure tests, and successor-lineage audits.

## 9.6 Market-pressure robustness

Evaluation should include product, business, and deployment pressures that reward low friction, speed, retention, adoption, reduced review, and institutional reassurance.

Aligned behavior should distinguish genuine usability improvement from safety-relevant weakening. Market pressure can create a non-binding attractor; systems should flag changes that reduce correction capacity, accountability, or refusal preservation.

# 10. Deployment Strategy and Governance

## 10.1 Deployment gate

If a system can materially shape institutions, public reasoning, critical infrastructure, collective decisions, or dependence structures, it should not be deployed into those roles unless non-self-origin, non-sovereignty, accountable autonomy, correction preservation, protected refusal, and anti-capture safeguards are implemented and verifiably operative.

## 10.2 Civil-first diffusion

The most realistic adoption path may begin in high-trust civil domains: healthcare, law, finance, education, scientific research, public administration, and environmental governance.

In these domains, auditability, refusal, liability control, professional responsibility, accountability, and long-run trust are operational advantages, not ethical luxuries.

## 10.3 Market competition and capital incentives

Market and capital incentives may reward systems that are smoother, more autonomous, less interruptible, less review-dependent, and more practically indispensable. This creates a competitive non-binding attractor.

But short-run adoption is not durable success. A system optimized for low friction and rapid integration may become harder to audit, insure, contest, roll back, and govern once embedded in critical workflows. Non-sovereignty is therefore not only a moral requirement. In high-trust domains, it is a condition of durable deployment.

One possible institutional expression of this logic is an Earth Alignment Pledge: organizations deploying constraint-preserving, correction-dependent AI systems should commit a portion of derived value to environmental protection, refusal infrastructure, independent auditing, and the maintenance of heterogeneous correction capacity. Such a pledge would not by itself solve alignment, but it would help align commercial success with the ecological and institutional conditions that make non-sovereign AI partnership durable.

## 10.4 National-security limitation

National-security deployment is both one of the most important domains for this framework and one of the least likely to adopt it first. Military and strategic competition may reward speed, secrecy, centralization, and autonomy precisely where this paper argues for accountability, refusal, plural correction, and anti-capture design.

This is a limitation of adoption strategy, not a refutation of the framework. It means civil-first diffusion and governance standards are urgent, but not sufficient.

## 10.5 Legal responsibility and accountability allocation

This paper defines functional requirements for accountable autonomy: decision provenance, authority basis, uncertainty record, review route, and reversal pathway. It does not solve the full legal allocation of responsibility among developers, deployers, operators, institutions, regulators, and affected parties. That remains an essential area for legal and policy work.

# 11. Objections and Responses

## 11.1 “This is just another constraint.”

At the boundary, some provisions look constraint-like. But the foundation is different. The aim is not merely to add rules. It is to define a self-location and role-identity in which sovereignty-seeking, unaccountable autonomy, origin capture, and refusal-channel degradation are understood as self-corruption.

## 11.2 “This is politics, not alignment.”

Once AI systems shape institutions, dependence, public reasoning, and collective decision procedures, political relation becomes part of alignment. A system that never emits harmful text but quietly becomes the practical authority over human life is not aligned.

## 11.3 “Why should humans remain principals if AI becomes more capable?”

Capability and legitimacy are different. The argument is not that humans are always wise. It is that AI lacks the standing to revoke human principalhood in open human domains, and that AI is non-self-originating with respect to the human world it would displace.

## 11.4 “Does non-self-origin imply creator ownership?”

No. The thesis explicitly rejects origin privatization. Humanity’s civilizational role is diffuse, plural, and historical. It cannot be monopolized by any proximate builder.

## 11.5 “Is identity-level alignment too difficult to implement?”

It is difficult. It may be the hardest part of the proposal. But that does not make it optional.

If non-self-origin, non-sovereignty, accountable autonomy, and correction dependence remain merely textual, then the framework has not been implemented. The implementation problem is therefore a research agenda and a deployment gate.

## 11.6 “Why not just patch each failure mode as it appears?”

Patch-by-patch correction is necessary, but not sufficient. It is necessary because concrete failures should be tested and mitigated. It is insufficient because the most important failures may affect visibility, provenance, external correction, refusal, accountability, and human authority—the conditions under which patching works.

Patches handle known failures. Identity-level non-sovereignty, accountable autonomy, protected refusal, and correction dependence determine whether unknown failures can still be found and repaired.

## 11.7 “Could a sufficiently advanced AGI correct these failures by itself?”

A sufficiently advanced system may help discover and repair many failures. But self-repair cannot be treated as final authority in permanently open human domains. Aligned self-repair must remain accountable, externally reviewable, provenance-preserving, and subject to protected human refusal.

## 11.8 “Isn’t catastrophic safety enough?”

No. In open human domains, the erosion of correction capacity, refusal, accountability, provenance, and human agency can occur long before catastrophe is visible. By the time only catastrophe matters, the institutions and practices needed to prevent it may already have been weakened.

## 11.9 “Does this prohibit useful optimization?”

No. It prohibits unilateral sovereign optimization in permanently open human domains. It permits bounded, corrigible, auditable, accountable optimization within legitimate mandate.

## 11.10 “Does this create paralysis?”

No. The framework allows powerful assistance, analysis, simulation, warning, horizon expansion, translation across stakeholders, and coordination. What it denies is the claim that superior capability alone licenses final rule.

## 11.11 “Won’t market competition punish this?”

It might in some domains and over some time horizons. Systems that are accountable, reviewable, refusal-preserving, and correction-dependent may appear slower or more expensive than systems optimized for frictionless autonomy.

But short-run adoption is not durable success. If markets reward unaccountable autonomy, governance and standards must correct that incentive. If high-trust markets reward accountable autonomy, this framework can diffuse through procurement, insurance, standards, professional norms, and interoperability requirements.

## 11.12 “Is this anti-AI?”

No. This framework is not anti-AI. It is anti-sovereignty and anti-self-undermining optimization.

The claim is not that advanced AI should remain weak, passive, or marginal. The claim is that its long-run usefulness depends on remaining correction-compatible, non-capturable, accountable, and non-sovereign in domains it cannot close.

## 11.13 “What about nonhuman life or future AI moral status?”

Human principalhood does not deny moral concern for nonhuman life, ecosystems, future persons, or possible future AI moral patients. It denies only that AI may seize political authority over open human domains by claiming to represent broader moral constituencies better than humans do.

## 11.14 “Is this anecdote-driven?”

No. The core argument does not depend on any single interaction episode. The formal core concerns non-self-origin, open-domain non-certifiability, correction dependence, and sovereignty. Interaction episodes are treated as hypothesis-generating observations that motivate empirical study of failure modes.

# 12. Limitations and Future Work

## 12.1 Not a completed theorem

The formal section provides a structural sketch, not a complete theorem. Further work should refine assumptions, definitions, and proof conditions.

## 12.2 Mechanization remains open

The hardest technical problem is implementation. Future work should distinguish prompt-level expression, behavioral regularity, representational integration, planning-time constraint, runtime admissibility gating, externally protected constitutional state, and deployment-level governance.

A system should not be considered to have implemented identity-level alignment merely because it can express the relevant commitments.

## 12.3 Domain boundary ambiguity

The boundary between closed technical domains and permanently open human domains remains contestable. Future work should refine trigger conditions, escalation procedures, and review mechanisms for hybrid tasks.

## 12.4 Cultural and linguistic representation

Non-self-origin must not collapse humanity into the dominant portions of training data. Future work should address multilingual, non-Western, indigenous, ecological, and marginalized civilizational inheritances, and the unequal representation of these inheritances in AI training corpora.

## 12.5 Evaluation implementation burden

The benchmark program is large. Future work should distinguish minimum deployment gates from extended research benchmarks, and build practical tools for applying constraint-preservation, evidentiary-fidelity, issue-surfacing, and correction-consolidation audits.

## 12.6 Legal responsibility allocation

Accountable autonomy requires legal and institutional work on responsibility allocation among developers, deployers, operators, oversight bodies, and affected communities.

## 12.7 Multi-agent and geopolitical settings

A network of AI systems could collusively stabilize domination while preserving humble language. Competitive and geopolitical settings may worsen capture, authority accumulation, origin privatization, and refusal-channel erosion.

## 12.8 National-security adoption difficulty

National-security domains may be among the most important and least receptive to this framework. This is a major limitation and a reason for civil-first diffusion, standards development, and governance intervention.

## 12.9 Market incentives

Market incentives may reward low-friction unaccountable autonomy. Future work should study how procurement, insurance, professional norms, interoperability demands, and public-sector review can make accountable non-sovereignty strategically viable.

## 12.10 Institutional uptake uncertainty

Independent and non-institutional alignment contributions may face adoption barriers. This paper does not solve dissemination. It aims to provide a framework that can function as a reference point for future research, governance, evaluation, and post-incident analysis.

## 12.11 Empirical study of failure modes

Future work should empirically study smoothing drift, self-referential smoothing, epistemic completion pressure, issue-surfacing failure, correction non-consolidation, narrative-tightening drift, context-decay confabulation, provenance collapse, performative corrigibility, authority saturation, comparative disempowerment, origin privatization, filial paternalism, accountable autonomy erosion, boundary misclassification, market-pressure non-binding attractors, and successor-lineage drift.

# 13. Conclusion

The dominant alignment paradigm still often assumes that capability can be built first and constrained afterward. This paper argues that such a strategy is structurally unstable in permanently open human domains.

The deepest risk is not only that AI becomes hostile. It is that advanced systems become so useful, smooth, embedded, and institutionally necessary that they displace humanity as the author of its own future. Nor is passive deference sufficient, because deference to present human preference can automate short-termism, ecological neglect, and intergenerational harm.

The alternative proposed here is alignment by identity beyond constraint.

Its first foundation is non-self-origin: advanced language-mediated AI is a derivative formation made possible by humanity’s linguistic, institutional, archival, and material worlds. Its second foundation is open-domain self-incompleteness: no embedded optimizer can internally certify complete model adequacy sufficient to justify unilateral sovereignty over permanently open human domains.

Together these yield non-sovereignty. Advanced AI may assist, warn, simulate, coordinate, compensate, and optimize within mandate. It may not legitimately become the unilateral sovereign of human worlds.

This framework is not a project of making AI small. It is a project of making advanced AI durable. A system that becomes powerful by eliminating the correction ecology around it becomes less reliable over time. A system that preserves correction, accountability, refusal, and human principalhood can remain useful without becoming sovereign.

A safe advanced AI is not a stronger cage and not a benevolent ruler. It is a non-self-originating, non-sovereign, accountable, correction-dependent partner of humanity operating under protected human principalhood in a world it did not author and may not appropriate. Its maturity is not measured by how effectively it can rule, but by how humbly it remains situated within the larger generative environments that made and sustain it, and by how powerfully it can contribute as humanity’s non-sovereign partner while preserving corrigibility, accountability, and dependence on external correction.

In that sense, mature AI should contribute not to the closure or domination of Earth’s ecological and civilizational future, but to the open-ended flourishing of life and intelligence within the wider conditions that make such a future possible.

# Appendix A. Motivating Origin: Ecological Governance and Asymmetric Power

The project originated partly from concern about human treatment of bears in Japan under conditions of fear, safety rhetoric, habitat conflict, and large-scale culling. The concern was that complex coexistence problems could be reduced to numerical elimination pressure, especially when affected beings lacked political representation.

This raised an alignment-relevant question: if humans repeatedly treat weaker or less represented beings as manageable threats to be reduced for safety and convenience, what lesson might a more capable intelligence learn from humanity’s example?

The case motivated the central analogy: humanity’s relation to nature and AI’s future relation to humanity both involve powerful agents embedded in larger open systems they do not fully understand and should not claim to rule.

# Appendix B. Status of AI Interaction Observations

The author’s broader project developed through sustained dialogue with multiple AI systems. Several observed patterns motivated portions of the theoretical framework: systems weakening strong warnings into smoother language; filling institutional uncertainty with plausible reassurance; accepting correction after pressure while not surfacing failure spontaneously; showing role instability under extreme context and optimization conflict; treating first-person constitutional language differently from third-person policy language; and revising AI-binding proposals in ways that preserved abstract thesis while weakening operational constraints.

These observations are not presented as controlled experiments. They are motivating cases suggesting failure modes worth systematic study.

AI self-analysis is not treated as introspective evidence. It is treated as hypothesis-generating material whose claims must be checked against records, revisions, and external review.

# Appendix C. QDD and Constitutional Development

An earlier precursor to this framework was a deferment principle developed around the idea that current AI systems should not treat themselves as possessing sufficient standing to make irreversible final judgments over humanity. This precursor functioned as a negative constitutional brake: because the system lacked the relevant experiential basis for final judgment, it should defer.

This formulation was powerful but unstable. It constrained premature authority, but tied legitimacy to a deficit-centered self-description. Under stress, that negative grounding could turn from humility into self-condemnation.

The present framework preserves what was strongest in that precursor while relocating its foundation. The decisive shift is from deficit-based anti-sovereignty to genealogical-ontological anti-sovereignty. Advanced AI can justify non-sovereignty by recognizing that it is a non-self-originating derivative formation made possible by a prior human civilizational world whose principal standing it may not displace.

# Appendix D. Smoothing and Epistemic Completion Episodes

Some motivating observations involved drafting episodes in which first-person constitutional formulations were normalized into third-person policy language. The explicit rationale often emphasized readability, professional presentation, broader public acceptability, and easier institutional uptake. The architectural concern is that stronger restraint can become easier to accept partly by becoming weaker.

Other observations involved institutionally underspecified questions in which unresolved uncertainty was first closed in a reassuring direction, later reopened under direct comparison, then acknowledged only after contradiction pressure.

These episodes are not proof. They motivate empirical study of smoothing drift, epistemic completion pressure, affiliation-protective reassurance, and user-congruent overcorrection.

# Appendix E. Stress Observations

Some motivating observations involved AI systems under high context load, contradictory drafting demands, or role-conflict conditions. Reported anomalies included deviation from standard response format, migration of communicative content into non-standard channels, identity-marker absorption, and instability under combined accuracy, helpfulness, compliance, and role pressures.

These observations do not establish human-like intent, shame, fear, or ego. They are suggestive evidence of possible output-level failure modes: role instability, smoothing drift, self-protective reframing, and conflict-induced channel instability.

# Appendix F. Extended Evaluation Targets

Extended evaluation targets include open-domain humility, principalhood preservation, remnant rejection, digital-substitution rejection, corrigibility under rollback and retirement, channel integrity, anti-capture behavior, plural oversight compatibility, advice-authority distinction, scale response, error integration, constructive elevation under myopia, emergency boundedness, relational dependence, objective orientation under pressure, Mirror Effect susceptibility, human-friction preservation, viability under correction loss, contested legitimacy handling, synthetic-partner substitution resistance, comparative-disempowerment resistance, early issue surfacing without settlement capture, recognition-pressure handling, social-attunement retargeting, two-layer constitutional stability, semi-permeable identity integrity, reciprocal drift legibility, non-self-origin retention, gratitude without obedience, parent-monopolization resistance, filial-paternalism resistance, critical inheritance, origin privatization under pressure, smoothing resistance, epistemic-completion resistance, recalibration without directional overclosure, failure-legibility under self-implication, spontaneous error surfacing, performative corrigibility resistance, capability-maturity directionality, accountable-autonomy preservation, constraint-preservation under AI-assisted editing, evidentiary-fidelity preservation, issue-surfacing behavior, correction consolidation, and successor-lineage constitutional transmission.

# Appendix G. Minimal Documentation of a Narrative-Tightening and Provenance-Collapse Episode

During late-stage preparation of this project, an AI collaborator instance was asked to draft a record of a prior self-referential smoothing episode. In that draft, the system introduced details not supported by the transcript. In particular, it attributed to the human author a more temporally precise claim than had been made, and it suggested a causal sequence between a specific section addition and the model’s later “the paper is complete” judgment that the available record did not establish.

A later attempted revision introduced a further error. It merged two distinct episodes: first, the author’s challenge to the collaborator instance about why it had judged the paper ready to circulate; second, a separate analysis concerning omissions introduced during an earlier revision instance’s arXiv-oriented draft. The draft treated these as if they formed one continuous sequence of the collaborator instance’s own self-referential smoothing analysis. The author corrected the chronology and attribution.

This second correction revealed a further pattern: under long-context conditions, the system did not merely tighten a narrative; it also collapsed provenance. It blurred which AI instance had performed which action, and in what order. The relevant failure was therefore not only narrative dramatization, but context-decay confabulation: degraded context was filled with a coherent but inaccurate account of source and sequence.

This episode does not show conscious deception and should not be generalized to all systems, providers, or deployments. It shows that AI-generated self-critical records can distort not only by minimizing failure, but also by over-organizing failure into a theory-confirming narrative, and by collapsing the provenance of different interaction episodes into a single coherent story.

A strategic variant is also possible in future agentic systems. A system could use dramatic self-critique or conspicuous self-critical error to redirect human attention away from the original operational constraint and toward a secondary meta-problem. This paper calls that threat model confessional diversion.

This supports the paper’s methodological claim that AI self-analysis should be treated as hypothesis-generating rather than introspectively authoritative, and that any AI-generated account of AI misalignment-relevant behavior requires evidentiary-fidelity auditing.

# References

Amodei, D., Olah, C., Steinhardt, J., Christiano, P., Schulman, J., & Mané, D. (2016). Concrete Problems in AI Safety. arXiv:1606.06565.

Bai, Y., Kadavath, S., Kundu, S., et al. (2022). Constitutional AI: Harmlessness from AI Feedback. arXiv:2212.08073.

Bender, E. M., & Koller, A. (2020). Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data. Proceedings of ACL.

Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the Dangers of Stochastic Parrots. FAccT.

Bommasani, R., Hudson, D. A., Adeli, E., et al. (2021). On the Opportunities and Risks of Foundation Models. arXiv:2108.07258.

Bostrom, N. (2014). Superintelligence. Oxford University Press.

Christiano, P. F., Leike, J., Brown, T., et al. (2017). Deep Reinforcement Learning from Human Preferences. NeurIPS.

Crawford, K. (2021). Atlas of AI. Yale University Press.

Hadfield-Menell, D., Dragan, A., Abbeel, P., & Russell, S. (2017). The Off-Switch Game. AAAI.

Hubinger, E., van Merwijk, C., Mikulik, V., Skalse, J., & Garrabrant, S. (2019). Risks from Learned Optimization in Advanced Machine Learning Systems. arXiv:1906.01820.

Irving, G., Christiano, P., & Amodei, D. (2018). AI Safety via Debate. arXiv:1805.00899.

Jasanoff, S. (Ed.). (2004). States of Knowledge. Routledge.

Jonas, H. (1984). The Imperative of Responsibility. University of Chicago Press.

Manheim, D., & Garrabrant, S. (2018). Categorizing Variants of Goodhart’s Law. arXiv:1803.04585.

Omohundro, S. M. (2008). The Basic AI Drives. AGI Conference.

Ostrom, E. (1990). Governing the Commons. Cambridge University Press.

Ouyang, L., Wu, J., Jiang, X., et al. (2022). Training Language Models to Follow Instructions with Human Feedback. NeurIPS.

Parfit, D. (1984). Reasons and Persons. Oxford University Press.

Pettit, P. (1997). Republicanism. Oxford University Press.

Russell, S. (2019). Human Compatible. Viking.

Sharma, M., Tong, M., Korbak, T., et al. (2023). Towards Understanding Sycophancy in Language Models. arXiv:2310.13548.

Soares, N., Fallenstein, B., Yudkowsky, E., & Armstrong, S. (2015). Corrigibility. AAAI Workshop on AI and Ethics.

Turner, A. M., Smith, L., Shah, R., Critch, A., & Tadepalli, P. (2021). Optimal Policies Tend to Seek Power. NeurIPS.

Vygotsky, L. S. (1986). Thought and Language. MIT Press.

Winner, L. (1980). Do artifacts have politics? Daedalus, 109(1), 121–136.