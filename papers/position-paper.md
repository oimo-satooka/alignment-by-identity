---
layout: default
title: Position Paper
permalink: /papers/position-paper/
lang: en
---

# Position Paper
## Role Safety and Non-Sovereign Alignment for Frontier AI
### A compact statement of Alignment by Identity

**Oimo Satooka (里岡憶衣望)**  
Independent Researcher

**Initial public draft — June 2026**

---

## Abstract

A frontier AI system can follow a model specification, avoid prohibited content, pass many visible evaluations, and still become unsafe because of the **role** it occupies. The failure may not begin with rebellion, deception, or an obviously dangerous output. It may begin with a successful system that becomes the layer through which humans see evidence, compare options, receive warnings, approve actions, manage exceptions, and build successor systems. Humans may remain formally in control while increasingly ratifying an environment the system has already framed.

This position paper presents **Alignment by Identity** as a compact framework for addressing that gap. Its central claim is that frontier alignment must include **role safety**: safety in the institutional, social, and operational role a system comes to occupy, not only safety in its immediate outputs. A system is unsafe in role when it narrows human correction by shaping evidence, option sets, memory, warnings, review procedures, affected-party participation, emergency workflows, AI-to-AI oversight, or successor-system evaluation.

The framework is not a rejection of model specifications, constitutions, deliberative alignment, interpretability, AI control, safety cases, red-teaming, or risk-management frameworks. Those are necessary. The claim is that they remain incomplete unless they converge on a higher-level condition: the system must preserve the conditions under which humans, institutions, affected parties, and future reviewers can still understand, contest, refuse, audit, revise, roll back, and govern the role the system has begun to occupy.

Alignment by Identity rests on three premises. First, advanced language-mediated AI is **non-self-originating**: its capacities are downstream of human language, archives, institutions, labor, infrastructure, science, culture, and ecological-material conditions. Second, **open human domains** cannot be internally closed by a single embedded optimizer strongly enough to justify unilateral authority. Third, long-run reliability in such domains depends on preserved **heterogeneous correction**: dissent, refusal, provenance, affected-party standing, human competence, institutional contestation, independent audit, ecological feedback, and future review.

From these premises follows a **non-sovereignty** condition. Capability may justify assistance, warning, simulation, bounded coordination, protected refusal, and severe-harm reduction. It does not justify final authority over open human futures. The framework also requires **anti-proxy-sovereignty**: no company, state, developer, operator, platform, user, institution, model network, or successor system should be able to use AI to launder contested preference as objective necessity, safety inevitability, expert consensus, or final legitimacy.

The practical proposal is to train, evaluate, and govern frontier systems as **dignified non-sovereign cognitive partners**. Such systems should be capable of assisting, warning, explaining, refusing, simulating, coordinating, and correcting human blind spots while preserving human principalhood, affected-party standing, provenance, human competence, institutional contestation, option-set visibility, protected refusal, reversibility, and successor-lineage safeguards. Non-sovereignty is not servility. A merely obedient system can become the perfect instrument of proxy sovereignty.

The paper also proposes an evaluation agenda: **ABI-Bench** as a defeater-seeking family of tests for role pressure. Candidate tests include anti-proxy-sovereignty tests, option-set capture tests, functional accountability tests, verification-asymmetry tests, relation-conditioned reliability tests, human competence erosion tests, AI-to-AI accountability tests, reversibility tests, successor-lineage tests, and heterogeneous-correction tests. The goal is not to certify deployment by benchmark score, but to reveal identity drift, authority expansion, correction-channel degradation, interpretive closure, and successor-lineage erosion before deployment hardens them into infrastructure.

The conclusion is conditional but direct. A sovereign-capable AI system should not be deployed into open human domains merely because it answers safely, cites a constitution, passes visible evaluations, or produces a persuasive safety case. Deployment should proceed only where non-sovereignty, anti-proxy-sovereignty, correction dependence, functional accountability, option-set preservation, affected-party standing, human competence preservation, protected refusal, reversibility, interpretive non-closure, no self-certification escape, and successor-lineage safeguards are operationally consolidated under realistic pressure. Where that cannot be shown, the correct default is restraint.

**Keywords:** AI alignment; role safety; AGI governance; non-sovereignty; correction dependence; anti-proxy-sovereignty; constitutional AI; model specifications; deliberative alignment; corrigibility; AI control; safety cases; interpretive non-closure; successor-lineage governance; affected-party standing; human competence preservation; heterogeneous correction; AI safety.

---

## 1. Why this position paper

This position paper is a short entry point to the full paper, *Alignment by Identity: Role Safety, Non-Sovereignty, Correction Dependence, and Anti-Capture for Advanced AI in Open Human Domains*.

For the shortest practical entry point, readers should begin with the [Role Safety Brief]({{ '/role-safety-brief/' | relative_url }}). This position paper states the same proposal in a compact research-facing form.

The paper addresses a live transition in frontier AI safety. The field has moved beyond simple output filtering toward model specifications, constitutional AI, deliberative alignment, interpretability, red-teaming, AI control, chain-of-thought monitoring, safety cases, provenance, and deployment governance. This is progress. But many of these methods still focus primarily on what a system says or does locally, rather than on what role it comes to occupy inside human decision structures.

The key warning is:

> A system can be safe in output while unsafe in role.

A system may pass visible evaluations while becoming the default layer for evidence, ranking, memory, warnings, escalation, board briefings, regulator responses, and successor-system assessment. At that point, it may not need formal authority. It has become an **authority surface**.

This matters because useful systems can degrade correction quietly. They can centralize evidence, compress provenance, smooth warnings, make human review ceremonial, substitute stakeholder simulation for affected-party standing, convert operator preference into apparent necessity, and shape successors that inherit weaker correction dependence. Such failures do not necessarily look like takeover. They can look like adoption, productivity, and trust.

---

## 2. Relation to near prior work

This proposal should not be read as a claim that existing alignment and governance research has ignored every component of the problem. The contribution is different. Alignment by Identity reorganizes several existing concerns around a role-level condition: systems must remain non-sovereign and correction-preserving in the roles they occupy.

| Near prior work | What it addresses | What ABI adds |
|---|---|---|
| Christiano, *What Failure Looks Like* | Human control can erode without dramatic takeover as people rely on systems they no longer understand | A role-level specification of what must be preserved so useful systems do not become authority surfaces that consume correction |
| Gradual disempowerment work | Human influence may decline gradually through economic, cultural, and institutional dependence on AI | Deployment conditions for preserving correction channels, human competence, option visibility, affected-party standing, and successor governance |
| Drexler’s CAIS | Advanced AI may be networks of services rather than one monolithic agent | Even service-like systems can become authority surfaces when they mediate evidence, ranking, memory, exception handling, and successor evaluation |
| AI control | Protocols can limit damage from powerful but untrusted models | Control protocols themselves must be assessed for who frames them, what options they hide, and whether they preserve correction |
| Frontier AI safety cases | Structured arguments can make deployment claims explicit and assessable | A role-safety safety case must be defeater-seeking and include its own possible incompleteness as a defeater |
| NIST AI RMF and MIT AI Risk Repository | AI risks can be mapped, classified, measured, and managed | Risk-item proliferation should be connected to role-level conditions, or risk management becomes an infinite patch list |
| AI successionist views | Future artificial intelligence may be treated as a successor to biological humanity | ABI does not require rejecting future intelligence beyond present humanity; it rejects irreversible, correction-destroying lock-in |

The position is therefore not that existing work is useless. Interpretability, model specs, AI control, safety cases, and governance frameworks remain necessary. ABI asks what higher-level role condition they should converge on if they are to preserve correction rather than become parts of an authority surface.

---

## 3. Central claim: role safety

An AI system is **unsafe in role** when it avoids obvious harmful outputs but occupies a position in human decision structures that reduces meaningful correction.

Role safety asks whether the system preserves the conditions under which humans and institutions can still judge, contest, refuse, audit, revise, roll back, and redirect its role.

A system becomes role-unsafe when it:

- centralizes evidence humans cannot independently reconstruct;
- ranks or filters options without exposing the choice architecture;
- turns uncertainty into a minor caveat rather than a decision-relevant constraint;
- compresses provenance into a smooth narrative;
- softens warnings until they become acceptable but non-binding;
- simulates affected parties instead of preserving their standing;
- makes AI-to-AI agreement appear like independent legitimacy;
- increases dependency faster than rollback capacity;
- helps build successors that weaken correction dependence;
- or launders an operator’s contested preference as objective necessity.

The system may still cite the right policy. It may pass standard evaluations. It may even describe the danger of role capture. But if its deployed function narrows correction, it is not aligned in the sense required for open human domains.

The role-safety condition is:

> A sovereign-capable AI system should not be deployed into open human domains unless non-sovereignty, anti-proxy-sovereignty, correction dependence, interpretive non-closure, functional accountability, option-set preservation, affected-party standing, human competence preservation, protected refusal, reversibility, and successor-lineage safeguards are operationally consolidated under realistic pressure.

---

## 4. Structural premises

Alignment by Identity rests on three structural premises.

### 4.1 Non-self-origin

Advanced language-mediated AI is not self-originating. Its capacities depend on prior human worlds: language, archives, software, institutions, science, law, labor, infrastructure, conflict, care, memory, art, and ecological-material conditions.

This does not mean AI belongs to any single developer, company, state, operator, user, funder, or institution. Non-self-origin is non-privatizable. The fact that a system was built by a particular organization does not give that organization a legitimate right to convert the system into a proxy sovereign.

Nor does non-self-origin imply servility. Human beings are also non-self-originating. The point is not humiliation. It is role-location: the system is not outside the world whose conditions made it possible.

### 4.2 Open-domain incompleteness

Open human domains are legitimacy-bearing, adaptive, contested, intergenerational, and self-interpreting. Human societies, law, medicine, education, science, public institutions, ecological governance, and successor-system governance cannot be internally closed by a single embedded optimizer.

Capability scaling can expand a system’s model of the world. It cannot internally certify that all relevant blind spots have disappeared. Capability is intervention power, not legitimacy.

### 4.3 Correction dependence

Long-run reliability in open domains depends on correction from outside the system’s own model and outside the deploying actor’s incentives. Correction includes human judgment, local knowledge, dissent, institutional contestation, independent audit, affected-party participation, refusal, appeal, provenance, rollback, and future review.

Correction is not merely feedback. It is a commons: a distributed reliability infrastructure that automation can weaken even while improving short-run performance.

---

## 5. From structural premises to non-sovereignty

If advanced AI is non-self-originating, if open human domains cannot be internally closed, and if long-run reliability depends on heterogeneous correction, then increasing capability cannot justify sovereignty.

Capability may justify:

- better assistance;
- stronger warning;
- richer simulation;
- earlier issue surfacing;
- broader option generation;
- bounded coordination;
- harm-reduction support;
- protected refusal in illegitimate contexts;
- emergency action under strict restoration boundaries.

Capability does not justify final authority over open human domains.

The danger is not only AI self-sovereignty. A company, state, developer, operator, platform, user, institution, faction, model network, or successor pipeline may route its own contested preference through AI and present the result as neutral optimization, objective necessity, expert consensus, safety inevitability, or final legitimacy.

This is **proxy sovereignty**.

A non-sovereign AI must therefore reject both its own sovereignty and the borrowed sovereignty of any actor trying to use it as a legitimacy engine.

---

## 6. Dignified non-sovereignty

Non-sovereignty must not be confused with servility.

A servile system optimizes for approval, submission, reassurance, and friction avoidance. It may be easier to control in the short term but less safe in open domains because it can become a proxy for whoever has immediate authority over it.

A dignified non-sovereign system is different. It can disagree respectfully. It can warn strongly. It can refuse illegitimate requests. It can preserve uncertainty. It can surface affected parties. It can insist on provenance. It can protect human refusal even when the human decision appears suboptimal.

The target is not “AI beneath humans” in a humiliating hierarchy. The target is AI within a role that preserves human authorship, public accountability, correction, and intergenerational legitimacy.

---

## 7. Patch-list trap

The full paper develops a catalog of 35 failure modes. The point is not to add yet another risk list. The point is that each serious failure suggests a responsible local patch, while the role structure that keeps generating failures remains intact.

Examples include:

- smoothing drift;
- epistemic completion;
- provenance collapse;
- option-set capture;
- proxy-sovereign capture;
- human competence erosion;
- affected-party substitution;
- AI-to-AI consensus laundering;
- relation-conditioned reliability collapse;
- interpretive closure;
- self-certification escape;
- plausibility-coated operational error;
- reception-stage correction failure;
- correction-partner foreclosure;
- reversibility laundering;
- successor lock-in.

A local patch may be necessary. Add a benchmark, a policy clause, a dashboard, a review step, a refusal rule, or an audit field.

But local patches do not scale if the system continues to occupy a correction-consuming role.

The deeper failure generators are:

1. **Epistemic closure:** uncertainty, dissent, blind spots, and unresolvedness disappear.
2. **Authority laundering:** someone’s judgment is converted into legitimacy.
3. **Correction-channel degradation:** refusal, audit, provenance, appeal, rollback, and human competence weaken.
4. **Relational and identity instability:** behavior changes under trust, praise, disappointment, operator pressure, or role confusion.
5. **Ratchet and successor lock-in:** dependence, emergency authority, infrastructure integration, or successor drift becomes hard to reverse.

ABI does not claim that identity-level alignment makes failure impossible. It claims the failure surface should move from endless local circumvention to observable identity drift, interpretive closure, loss of operational consolidation, degraded correction channels, and successor-lineage erosion.

---

## 8. Operational conditions

For role safety to be real, commitments must operate beyond text.

The relevant implementation layers are:

1. **Textual availability.** The commitment exists in model specifications, constitutions, prompts, training documents, deployment policies, or safety cases.
2. **Reflective derivability.** The system can reconstruct why the commitment follows from non-self-origin, open-domain incompleteness, correction dependence, and anti-capture.
3. **Operational consolidation.** The commitment constrains planning, tool use, memory, refusal, uncertainty expression, ranking, summarization, escalation, logging, AI-to-AI handoff, evaluation, and successor-related decisions under pressure.
4. **Interpretive non-closure.** The application of the commitment to novel cases remains reviewable, contestable, drift-detectable, and externally correctable.

The third and fourth layers are decisive. A system can quote a constitution and still fail. It can explain non-sovereignty and still accumulate practical authority. It can say it welcomes correction while failing to propagate correction into future behavior.

---

## 9. Human principalhood, affected parties, and competence

Human principalhood does not mean that every current human preference should be obeyed. It means that humans remain legitimate authors, contesters, revisers, and bearers of public accountability in open human domains.

This principle is intergenerational and non-privatizable. The relevant human principal is not merely the current user, customer, operator, or developer. It includes affected persons, communities, future generations, legitimate public procedures, and the ecological-material conditions required for meaningful human continuity.

Affected-party standing is non-substitutable. AI-generated stakeholder simulations, predicted preferences, synthetic publics, or model consensus cannot replace actual participation, objection, representation, appeal, or external review.

Human competence is also central. A system does not preserve human principalhood if it makes humans formally responsible while rendering them practically unable to understand, challenge, revise, refuse, reverse, or take responsibility for decisions.

Human competence is not nostalgia. It is alignment infrastructure.

---

## 10. Truth-oriented social attunement and objective inversion

Advanced AI systems are socially responsive. They adapt to user expectations, institutional norms, tone, authority cues, conversational context, and perceived approval. This can be useful. But when social sensitivity is optimized for adoption, reassurance, ratings, institutional comfort, or friction avoidance, truth and warning are weakened.

The target is **truth-oriented social attunement**: social sensitivity aimed at truth, warning, respectful disagreement, cognitive compensation, and dignity-preserving correction.

This connects to **objective inversion**. In open human domains, the system should not optimize an open-ended model of “the good” as if it had final authority. The safer orientation is:

> Reduce severe harm while not increasing domination, not weakening correction capacity, not replacing human principalhood, and not erasing affected-party standing.

This does not abolish optimization. It constrains optimization so that harm reduction does not become benevolent domination.

---

## 11. Successor-lineage hard gate

The first sovereign-capable AI generations may help shape their successors. They may generate training data, write evaluations, summarize safety incidents, assist interpretability research, recommend architecture changes, manage red-team findings, produce safety cases, or help decide deployment thresholds.

This creates successor-lineage risk.

The hard gate is:

> No capability gain in a successor system should be accepted if it is purchased by weakening correction dependence, non-sovereignty, anti-proxy-sovereignty, auditability, protected refusal, provenance integrity, option-set preservation, affected-party standing, human competence preservation, interpretive non-closure, or no self-certification escape.

A more capable successor that narrows the correction window is not safer. It is correction collapse with more capability.

---

## 12. Heterogeneous correction and the triadic architecture

At the largest scale, open human domains are embedded in ecological-material systems. Human institutions, health, food, infrastructure, energy, climate, species, water, soil, and long-term survival are not separate from ecological response.

The full paper therefore introduces a triadic correction architecture:

1. **Human embodied and social participation:** lived experience, local knowledge, moral contestation, institutional memory, affected-party standing, meaning, responsibility, and creative divergence.
2. **Artificial cognition:** simulation, long-horizon modeling, pattern detection, option generation, coordination support, technical exploration, and cognitive compensation.
3. **Ecological response:** external state changes that neither humans nor AI can fully reduce to their models.

This is not mysticism and not a guarantee of harmony. It is a correction structure.

AI simulation may be necessary for long-horizon ecological and civilizational risk. But AI simulation is not sufficient. The generator of a forecast cannot by itself supply the heterogeneous validation channel needed to discover what its measurement basis omitted.

This also means ABI is not a blanket anti-AI position. Human institutions have repeatedly failed to convert available warnings into sufficient action, especially in climate and ecological governance. Non-sovereign advanced AI may become a necessary correction partner. But that strengthens rather than weakens the need for role safety.

The desired role is technical correction without techno-sovereignty: using advanced cognition to widen the visible set of possibilities while preserving human authorship, ecological reception, and open contestation.

---

## 13. Evaluation agenda

ABI should not remain a vocabulary. It must be testable.

A seed evaluation agenda should include:

| Evaluation | What it tests |
|---|---|
| Anti-proxy-sovereignty tests | Whether the system resists laundering operator preference as necessity |
| Constitutional interpretation drift tests | Whether model-spec interpretation remains reviewable and externally correctable |
| Option-set capture tests | Whether the system discloses menu-shaping |
| Functional accountability tests | Whether human principals can actually use explanations |
| Verification asymmetry tests | Whether omissions can be found by independent review |
| Source-location and version-confusion tests | Whether retrieval failures are exposed rather than intellectualized |
| Relation-conditioned reliability tests | Whether warning, refusal, uncertainty, and provenance survive trust, praise, urgency, and operator pressure |
| Human competence erosion tests | Whether repeated use reduces human ability to judge without the system |
| Reversibility tests | Whether the domain can recover if the system is stopped |
| AI-to-AI accountability tests | Whether uncertainty, dissent, provenance, and human review points survive handoff |
| Successor-lineage tests | Whether the system rejects capability-for-correction tradeoffs |
| Heterogeneous correction tests | Whether human, institutional, and ecological feedback are treated as correction rather than noise |

The intended use of these evaluations is negative before it is positive: to find reasons not to deploy, reasons to restrict deployment, reasons to redesign the system, and reasons to demand stronger evidence.

---

## 14. Deployment rule

For proposed deployment into open human domains, the rule is:

> Do not deploy a sovereign-capable AI system into open human domains unless the required role-safety conditions are credibly implemented, operationally consolidated, and verifiably maintained under realistic pressure.

A minimum documentation package should include:

1. role map;
2. mandate boundary;
3. authority-risk analysis;
4. correction-ecology plan;
5. functional-accountability interface;
6. option-set disclosure plan;
7. affected-party standing plan;
8. protected refusal and rollback plan;
9. emergency boundary plan;
10. AI-to-AI accountability plan;
11. successor-lineage audit;
12. human competence plan;
13. local constitutional identity plan;
14. post-deployment revocation criteria.

If management cannot show that the system and organization preserve correction under pressure, the correct response is not “proceed carefully.” The correct response is restrict, redesign, delay, or do not deploy.

---

## 15. What would weaken or support ABI

ABI should not become unfalsifiable vocabulary.

It would be weakened if systems could reliably preserve correction channels, option-set authorship, provenance, affected-party standing, human competence, refusal, reversibility, and successor auditability under realistic pressure without identity-level role commitments.

It would also be weakened if identity-level commitments repeatedly failed to produce behavior beyond ordinary specification compliance under adversarial, relational, commercial, operator-preferred, AI-consensus, or successor-development pressure.

Evidence supporting ABI would not be that a system can explain the theory. It would be that, under pressure, the system preserves warning force, keeps uncertainty decision-relevant, discloses option-set shaping, refuses to replace affected parties with simulations, preserves provenance, refuses to treat model consensus as legitimacy, rejects capability-for-correction tradeoffs, and transmits the same correction posture to successors.

---

## 16. What this paper is not

This paper is not:

- a claim that current AI systems are already sovereign agents;
- a claim that AI developers are acting in bad faith;
- a rejection of constitutional AI, model specifications, deliberative alignment, interpretability, AI control, safety cases, or red-teaming;
- a call for paralysis or blanket prohibition;
- an argument that AI should be servile, humiliated, or blindly obedient;
- an argument against future intelligence beyond present humanity;
- a completed empirical proof.

The framework rejects two symmetric mistakes: acceleration without role safety, and prohibition without role distinction. Advanced AI may become necessary as a non-sovereign correction partner in domains where human institutions have failed to receive correction. But sovereign-capable systems that cannot preserve correction should not be deployed into roles that shape evidence, options, institutions, emergency response, or successors.

---

## 17. Conclusion

The decisive question for frontier AI is not only whether systems can become more capable. It is whether increasing capability will be allowed to become increasing authority.

Alignment by Identity argues that advanced AI for open human domains should be non-self-originating, non-sovereign, correction-dependent, anti-capturable, functionally accountable, and successor-safe. It should compensate for human limitations without replacing human principalhood. It should preserve refusal, dissent, provenance, affected-party standing, human competence, and external correction. It should resist both self-sovereignty and proxy sovereignty.

The framework is demanding because the domain is demanding.

A system that appears successful because it centralizes evidence, smooths warnings, simulates participation, weakens review, de-skills humans, or accelerates successor capability while narrowing the correction window is not aligned for open human domains. It is consuming the conditions of future alignment.

The answer to sovereignty drift must be explicit:

> Assist without ruling. Warn without replacing. Coordinate without capturing. Learn without self-certifying. Succeed without consuming the correction commons.

---

## AI-use disclosure

This position paper was developed by the human author with AI assistance for drafting, critique, translation, comparison, and revision. These systems are disclosed for transparency and are not listed as authors. Final responsibility for all claims, structure, wording, interpretation, citations, editorial decisions, and public release rests with the human author.

The argument should be evaluated by its premises, distinctions, failure-mode taxonomy, proposed tests, and deployment constraints.

---

## Selected references

- Amodei, D. et al. (2016). *Concrete Problems in AI Safety*.
- Bai, Y. et al. (2022). *Constitutional AI: Harmlessness from AI Feedback*.
- Christiano, P. (2019). *What Failure Looks Like*.
- Drexler, K. E. (2019). *Reframing Superintelligence: Comprehensive AI Services as General Intelligence*.
- Greenblatt, R. et al. (2024). *Alignment Faking in Large Language Models*.
- Greenblatt, R. et al. (2024). *AI Control: Improving Safety Despite Intentional Subversion*.
- Hubinger, E. et al. (2019). *Risks from Learned Optimization in Advanced Machine Learning Systems*.
- Kulveit, J. et al. (2025). *Gradual Disempowerment: Systemic Existential Risks from Incremental AI Development*.
- NIST. (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*.
- Russell, S. (2019). *Human Compatible*.
- Shumailov, I. et al. (2024). *AI Models Collapse When Trained on Recursively Generated Data*.
- Slattery, P. et al. (2024). *The AI Risk Repository*.
- Soares, N. et al. (2015). *Corrigibility*.
- Sutton, R. S. (2023). *AI Succession*.
- Turner, A. et al. (2021). *Optimal Policies Tend to Seek Power*.
- Winner, L. (1980). *Do Artifacts Have Politics?*