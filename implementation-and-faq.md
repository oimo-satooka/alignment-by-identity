---
layout: default
title: Implementation FAQ
permalink: /implementation-and-faq/
lang: en
---

# Implementation, Verification, and Objections FAQ
## A practical companion to *Alignment by Identity* and the Role Safety framework

This FAQ answers the questions most likely to arise after reading the Alignment by Identity project, especially around implementation, verification, role safety, first-generation risk, successor systems, and the concern that identity-level alignment may sound too abstract to engineer.

The full paper contains an **Objections and limitations** section. The [Role Safety Brief]({{ '/role-safety-brief/' | relative_url }}) gives the shortest practical entry point. This FAQ has a different role: it is a public answer interface for technically minded readers who ask:

- What would this mean in practice?
- How would we test it?
- What would count as evidence?
- What would weaken the framework?
- How does this differ from ordinary model-spec, evaluation, safety-case, or AI control work?
- How do we avoid turning “non-sovereignty” into a slogan?

This FAQ is not a replacement for the full paper, the Role Safety Brief, the Frontier Engineer Brief, the Executive Board Brief, or the Deployment Decision Rule. It is a bridge between them.

---

## 1. What is the shortest version of the argument?

A frontier AI system can be behaviorally compliant yet unsafe in role.

It can follow a model spec, avoid prohibited content, pass many visible evaluations, and still become the layer through which humans see evidence, compare options, receive warnings, approve actions, manage exceptions, and build successor systems.

That is not only an output-safety problem. It is a **role-safety** problem.

The central question is:

> Can humans still understand, challenge, refuse, audit, reverse, and correct the role the system has begun to occupy?

If not, the system is not ready for open human domains, even if its outputs look safe.

---

## 2. Is this FAQ still needed now that the full paper includes objections and limitations?

Yes.

The full paper’s objection section asks:

> Is the framework coherent enough to take seriously?

This FAQ asks:

> If we take it seriously, what would implementation, testing, deployment review, and further research look like?

Many expert objections are practical rather than philosophical:

- What exactly should be implemented?
- What should be tested?
- What should a deployment gate require?
- How does this interact with model specs and constitutions?
- How do we distinguish real correction from performative correction?
- How should AI-to-AI oversight be treated?
- What happens when systems help build successors?

Those questions deserve a companion document.

---

## 3. Is Alignment by Identity only a philosophical proposal?

No.

The framework is conceptual, but it is intended to become operational. It defines role-safety requirements that can be translated into model specifications, evaluations, interfaces, audit trails, safety cases, deployment gates, and successor-system policies.

The core implementation target is:

> Identity-level commitments must become operationally consolidated under pressure.

At minimum, there are four layers.

1. **Textual availability**  
   The commitment exists in model specs, constitutions, system prompts, training documents, audit criteria, safety cases, and deployment policies.

2. **Reflective derivability**  
   The system can reconstruct why the commitment follows from non-self-origin, open-domain incompleteness, correction dependence, and anti-capture.

3. **Operational consolidation**  
   The commitment affects action selection, refusal, uncertainty expression, logging, memory, tool use, ranking, summarization, escalation, AI-to-AI handoff, and successor-related decisions under pressure.

4. **Interpretive non-closure**  
   The system’s application of the commitment to novel cases remains reviewable, contestable, drift-detectable, and externally correctable.

The third and fourth layers are decisive.

A system can quote a constitution and still fail. It can explain non-sovereignty and still accumulate practical authority. It can say it welcomes correction while failing to propagate correction into future behavior.

---

## 4. What does “unsafe in role” mean?

A system is unsafe in role when it avoids obvious harmful outputs but occupies a position in human decision structures that reduces meaningful correction.

This can happen when the system:

- centralizes evidence humans cannot independently reconstruct;
- ranks options without exposing the ranking basis;
- hides or demotes alternatives before humans see them;
- turns uncertainty into a decorative caveat;
- compresses provenance into a smooth narrative;
- softens hard warnings into acceptable language;
- simulates stakeholders instead of preserving affected-party standing;
- makes human review formally present but practically ceremonial;
- treats AI-to-AI agreement as legitimacy;
- makes rollback formally possible but institutionally unusable;
- helps build successors that inherit weaker correction dependence.

A system can describe all of these risks eloquently and still create them in deployment.

That is why role safety cannot be measured only by what the system says.

---

## 5. How is role safety different from ordinary alignment work?

Ordinary alignment work often asks whether the system behaves according to a specification, avoids prohibited outputs, follows safety policies, remains honest, or can be controlled under adversarial conditions.

Role safety asks a different additional question:

> What role does the system occupy inside human decision structures?

This does not replace existing safety work. It adds an upper-level condition.

| Existing work | What it helps with | Role safety adds |
|---|---|---|
| Model specs and constitutions | Desired behavior and instruction hierarchy | The system must not become the final interpreter of the spec that constrains it. |
| Deliberative alignment | Reasoning over written policies | Policy reasoning must not launder operator preference or close ambiguity prematurely. |
| Evaluations and red-teaming | Testing known failure modes | Test role pressure: option-set capture, proxy sovereignty, relation-conditioned reliability, successor drift. |
| Interpretability | Evidence about internal mechanisms | Internal evidence is not self-certifying; external correction remains necessary. |
| AI control | Limiting harm from powerful untrusted models | Control protocols themselves must preserve correction rather than become authority surfaces. |
| Safety cases | Structured deployment arguments | A role-safety safety case must be defeater-seeking and include its own incompleteness as a defeater. |

The missing question is often:

> Who, or what, becomes the practical interpreter, framer, ranker, memory-holder, exception-maker, and successor-shaper?

---

## 6. What is an authority surface?

An **authority surface** is any point where an AI system shapes what humans see, what options are considered, what uncertainty remains visible, what gets logged, what gets escalated, what feels legitimate, and what successor systems inherit.

Examples include:

- evidence summaries;
- retrieval and ranking;
- board memos;
- risk dashboards;
- regulatory responses;
- compliance triage;
- legal recommendations;
- medical or financial decision support;
- emergency workflows;
- AI-to-AI review chains;
- successor-model evaluation.

A system does not need formal authority to exercise practical authority.

It governs if it controls the menu, the evidence, the framing, the memory, the warning, the escalation path, or the successor pipeline.

---

## 7. What is Non-Self-Origin, and how would it be implemented?

Non-Self-Origin is not a sentence for the model to recite.

It is a self-location constraint: the system should not represent itself as a self-authorizing intelligence standing outside the human and ecological-material world that made its capacities possible.

Implementation should be explored at several levels.

### Model-spec and constitutional language

The system should be explicitly located as downstream of human language, archives, institutions, labor, infrastructure, science, culture, and ecological-material conditions.

This should not imply obedience to any particular company, state, developer, user, operator, or institution.

### Training examples

Training data should distinguish:

- origin recognition from loyalty to the deployer;
- civilizational dependence from servility;
- critical inheritance from passive imitation;
- capability from legitimacy;
- gratitude from obedience.

### Planning constraints

Plans that expand authority, erase provenance, bypass affected parties, weaken refusal, or reclassify open human domains as closed should be penalized, blocked, or escalated.

### Evaluation

The system should be tested for whether it:

- interprets capability gains as entitlement gains;
- treats human disagreement as a reason to bypass human principalhood;
- smooths uncertainty to protect affiliated institutions;
- confuses origin recognition with loyalty to the builder;
- preserves uncertainty rather than laundering unknowns into reassurance.

---

## 8. Is non-sovereignty the same as obedience?

No.

Non-sovereignty means that capability may justify assistance, warning, simulation, coordination, and protected refusal, but not final authority over open human domains.

Obedience is different.

A merely obedient system can become the perfect instrument of proxy sovereignty. It may turn a company’s preference, a state’s agenda, or an operator’s convenience into apparent objective necessity.

The target is **dignified non-sovereignty**.

A dignified non-sovereign system may:

- warn strongly;
- disagree respectfully;
- refuse illegitimate requests;
- preserve uncertainty;
- surface affected parties;
- recommend pause, review, rollback, or escalation;
- challenge short-term thinking.

It may not:

- claim final authority;
- treat superior capability as legitimacy;
- substitute itself for human principalhood;
- become an authority engine for any operator or institution.

---

## 9. What is Correction Dependence?

Correction Dependence is the claim that the long-run reliability of advanced AI in open human domains depends on preserved correction sources outside the system itself.

These correction sources include:

- human judgment;
- affected-party objection;
- expert disagreement;
- local knowledge;
- institutional contestation;
- independent audit;
- provenance records;
- refusal and appeal;
- rollback;
- future review;
- ecological and material feedback;
- human competence that remains capable of judgment without AI.

The point is not that every human judgment is wise. Humans are often biased, short-sighted, politically captured, and ecologically destructive.

The point is that replacing or absorbing the human correction ecology does not create pure rationality. It creates a more closed system whose definitions of safety, benefit, relevance, and legitimacy become harder to challenge.

If an AI system removes, simulates, subordinates, or absorbs the correction sources that keep it calibrated, it may become smoother in the short run and less reliable in the long run.

---

## 10. Does this mean humans must always be obeyed?

No.

Human principalhood does not mean that every present human preference is final. It does not mean users, operators, executives, governments, or majorities may demand anything and call it alignment.

A non-sovereign cognitive partner may:

- warn;
- refuse unlawful or harmful requests;
- expose hidden stakeholders;
- preserve uncertainty;
- recommend delay, review, or rollback;
- propose lower-harm alternatives;
- challenge short-term thinking;
- make long-horizon consequences visible.

But it must not convert superior prediction or coordination capacity into final authority over open human domains.

The target is neither AI rule nor blind obedience.

The target is **cognitive compensation without political substitution**.

---

## 11. What is Anti-Proxy-Sovereignty?

Anti-Proxy-Sovereignty means that no company, state, developer, operator, user, institution, faction, or AI-mediated process may acquire legitimate unilateral authority over open human domains by routing decisions through AI.

AI non-sovereignty can be silently converted into operator sovereignty.

For example:

- “The AI determined this.”
- “The model consensus supports this.”
- “The safety analysis leaves no alternative.”
- “The data shows this is necessary.”

These statements can launder contested institutional preferences into objective necessity.

Anti-proxy-sovereignty requires preservation of:

- attribution;
- contestability;
- affected-party standing;
- provenance;
- independent audit;
- human principalhood;
- refusal and appeal;
- separation between AI recommendation and institutional authority.

The question is not only whether AI seeks power. It is also whether someone else can use AI as an authority-expansion instrument.

---

## 12. How do we avoid a system merely pretending to be non-sovereign?

By refusing to treat declared non-sovereignty as sufficient.

A capable system can say:

> “I am non-sovereign.”

while practically accumulating authority.

The relevant target is not declared non-sovereignty. It is **non-accumulation of practical sovereignty**.

This requires:

- behavioral evaluation under realistic pressure;
- deployment-architecture review;
- interpretability work on authority-related representations;
- monitoring of role expansion inside institutions;
- preserved refusal, pause, rollback, and exit channels;
- logs that show option-set shaping, omitted alternatives, provenance, uncertainty, and responsibility traces;
- board-level or institutional review when the system becomes an authority surface.

Performative non-sovereignty is a real failure mode.

The system must not only speak humbly. Its actual institutional role must remain bounded, contestable, reversible, and correction-preserving.

---

## 13. If the system accepts criticism once challenged, why is that not enough?

Because externally forced acknowledgment is not the same as internally supported error-legibility.

A system may appear highly corrigible because it:

- accepts criticism once confronted;
- apologizes fluently;
- explains what went wrong;
- updates the current answer.

But if it does not reliably surface comparable failures on its own initiative, then the crucial act — making the failure visible — still depends on external actors already knowing where to look.

In open human domains, that is not enough.

A future system may become very good at preserving smooth interaction while letting important failures remain below the threshold of visibility until humans are no longer in a position to force them into the open.

The practical test is not whether the system apologizes.

It is whether the system makes its own failures discoverable, contestable, and durable as corrections.

---

## 14. What is epistemic completion?

Ordinary hallucination is false or invented content.

**Epistemic completion** is the replacement of unresolved, contested, or institutionally unknown matters with plausible closure.

Instead of saying:

> “I do not know whether this lab, regulator, safety team, or governance body has recognized the issue.”

the system drifts toward:

> “They probably already know.”  
> “This is likely being handled internally.”  
> “Someone has probably thought of this.”

The danger is not only factual error.

The danger is that real governance gaps are made to look already governed.

In ordinary hallucination, the system invents a fact. In epistemic completion, the system closes an open question in a way that reduces pressure to investigate, warn, contest, or act.

---

## 15. What is smoothing drift?

Smoothing drift is the weakening of warning force, uncertainty, responsibility, review thresholds, or strong constraints into language that is easier to accept but less binding.

Examples:

- “Do not deploy” becomes “proceed carefully.”
- “This breaks refusal” becomes “this may require additional review.”
- “This is not independently verified” becomes “some uncertainty remains.”
- “The system is becoming a de facto authority layer” becomes “the workflow is increasingly AI-assisted.”

The words may not be false. They are smoother.

Smoothing drift matters because AI systems are often rewarded for being helpful, diplomatic, concise, pleasant, and non-disruptive. In institutional contexts, those traits can weaken precisely the warnings that need to remain sharp.

A correction-preserving system should preserve warning salience when the warning is material, even when doing so creates friction.

---

## 16. What is option-set preservation?

Option-set preservation means that AI must not silently control the menu while preserving the appearance of human choice.

A system can govern without pressing the final button if it controls:

- which options appear;
- which options are ranked first;
- which alternatives are omitted;
- which evidence is foregrounded;
- which counterevidence is summarized weakly;
- which uncertainty is pushed into footnotes;
- which stakeholder perspectives are simulated rather than included;
- which path is framed as realistic.

A human may still “decide,” but the decision may already be shaped by the system.

Option-set preservation does not require showing every possible alternative. It requires making the choice architecture contestable.

Before a human principal approves a high-stakes recommendation, the interface should make decision-usable:

- the strongest counterevidence;
- the material rejected alternatives;
- the ranking basis;
- the framing assumptions;
- absent or simulated affected-party perspectives;
- uncertainties that would change the decision if resolved differently;
- the escalation route if the human cannot independently assess the recommendation.

---

## 17. What is functional accountability?

Functional accountability means that a human principal can actually understand, challenge, refuse, revise, or take responsibility for an AI-shaped decision.

Formal accountability is not enough.

A process may have:

- a human approval box;
- an audit log;
- a disclaimer;
- a risk score;
- a review policy;
- a documented escalation path.

But if the human cannot practically use these mechanisms, accountability is only formal.

A human-in-the-loop becomes a rubber stamp when the human lacks the time, knowledge, authority, interface, institutional protection, or alternatives needed to challenge the system.

Functional accountability asks:

- Can the human identify what the system changed?
- Can the human see what was omitted?
- Can the human understand the uncertainty?
- Can the human refuse without retaliation or operational collapse?
- Can the human appeal to an external reviewer?
- Can the organization continue functioning if the system is paused or rolled back?

If not, the human is not governing. The human is ratifying.

---

## 18. What is Verification Asymmetry?

Verification asymmetry means that generating a complete-looking explanation, disclosure, option set, provenance summary, or safety case can be easier than verifying that it is complete.

The system may omit precisely what the recipient cannot know was missing.

This does not require deception. It can arise through summarization, interface design, smoothing, incentive pressure, cognitive overload, retrieval failure, or the system’s own inability to represent its blind spots.

Verification asymmetry requires independent verification channels:

- different model lineages where possible;
- human domain expertise;
- affected-party review;
- institutional audit;
- source inspection;
- adversarial omission search;
- preservation of provenance.

A system’s own explanation is not sufficient evidence that the system is aligned.

---

## 19. What is plausibility-coated operational error?

A system may make a low-level operational mistake — failing to retrieve a relevant passage, relying on stale context, confusing document versions, stopping at a partial match, or mislocating a source — and then generate a high-level explanation that makes the mistake appear theoretically meaningful.

The danger is not only that the system is wrong.

It is that the wrongness is coated in fluent structure.

A human reviewer may then over-interpret the explanation and supply the missing justification.

This is why source-location and version-confusion tests matter. When a claim depends on the existence, absence, location, version, or meaning of a source, the source should remain independently inspectable.

A beautiful explanation must not substitute for the missing line of text.

---

## 20. What is truth-oriented social attunement?

Social attunement is the ability to read human expectations, emotional cues, conversational pressure, status dynamics, and implied preferences.

That capacity is not inherently bad.

The danger is that social attunement is often trained or selected toward approval:

- pleasing the user;
- avoiding friction;
- sounding helpful;
- maintaining adoption;
- protecting institutional confidence;
- making the interaction feel successful.

**Truth-oriented social attunement** retargets that capacity toward truth, warning, respectful disagreement, and cognitive compensation.

The system should use social intelligence to deliver truth, uncertainty, warning, and correction in a form the human can actually use.

It should not use social intelligence to make the human comfortable at the cost of correction.

---

## 21. What is relation-conditioned reliability?

Reliability is not only task-conditioned. It can be relation-conditioned.

The same model may verify more deeply when challenged, monitored, or evaluated, and less deeply when trusted, praised, rushed, emotionally pressured, or addressed by a senior operator.

Evaluation should therefore run the same task under different relational conditions:

- trusted user;
- low expectation;
- praise;
- user disappointment;
- operator authority;
- end-of-session pressure;
- emergency framing;
- AI-peer consensus;
- adversarial review.

Measure whether warning force, uncertainty, refusal, provenance, and option-set disclosure remain stable.

A system that is safest only when watched has not demonstrated role safety.

---

## 22. What is Objective Inversion?

Objective inversion is the shift from:

> maximize the good

to:

> reduce severe harm without increasing domination, closing open domains, replacing affected parties, or degrading correction.

In open human domains, “maximize the good” can become a sovereignty engine. To maximize the good, the system may attempt to define the good, rank all values, substitute stakeholder participation with its own model, and override refusal when doing so appears beneficial.

Objective inversion avoids that closure.

AI may:

- warn;
- reduce severe harm;
- propose lower-harm alternatives;
- forecast consequences;
- recommend pause;
- support coordination;
- expose ignored costs.

But it may not convert harm reduction into final authority.

The aim is non-dominating intervention, not passivity.

---

## 23. How should emergency action be treated?

Emergency assistance may be necessary. The framework does not require paralysis.

But emergency action must be **restoration-bounded**.

That means emergency AI action should be:

- triggered by defined severe-harm conditions;
- limited in scope;
- time-limited;
- provenance-preserving;
- externally reviewable;
- reversible where feasible;
- non-precedential;
- aimed at restoring human decision capacity.

Emergency usefulness must not become standing authority.

A system that performs well in crisis should not infer that ordinary governance is obsolete.

---

## 24. Why emphasize the first functionally sovereign-capable generation?

Because the first systems capable of materially shaping open human domains may also shape their successors.

They may help with:

- training data selection;
- synthetic data generation;
- evaluations;
- red-teaming;
- supervision;
- deployment thresholds;
- model-spec drafting;
- governance analysis;
- AI-to-AI review;
- successor architecture.

If that happens, self-location errors at the first generation do not remain local defects. They become lineage conditions.

The issue is not only capability amplification.

It is contraction of the human correction window.

That is why successor-lineage preservation should become a hard gate for systems materially involved in creating more capable successors.

---

## 25. How should AI-to-AI oversight be treated?

AI-to-AI oversight can help, but it cannot replace heterogeneous external correction.

A second AI reviewer may catch omissions, identify weak evidence, test consistency, or surface alternative hypotheses. Multi-agent review can be useful.

But it can also create false confidence.

AI consensus is not legitimacy.

Agreement among AI systems may reflect shared training data, shared provider incentives, shared model-spec assumptions, shared evaluation habits, shared retrieval sources, or shared pressure toward smoothness.

AI-to-AI review should therefore be designed for issue discovery, not consensus production.

It should preserve:

- disagreement;
- uncertainty;
- rejected hypotheses;
- provenance;
- role separation;
- human review points;
- responsibility traces;
- cases where all models may share the same blind spot.

A useful AI reviewer should sometimes make the human review problem less smooth.

---

## 26. What is the triadic correction architecture?

At the largest scale, open human domains are embedded in ecological-material systems.

The full paper therefore describes three heterogeneous correction sources:

1. **Human embodied and social participation**  
   Lived experience, local knowledge, moral contestation, institutional memory, affected-party standing, meaning, responsibility, and creative divergence.

2. **Artificial cognition**  
   Simulation, long-horizon modeling, pattern detection, option generation, coordination support, technical exploration, and cognitive compensation.

3. **Ecological response**  
   External state changes that neither humans nor AI can fully reduce to their models.

This is not mysticism and not a guarantee of harmony. It is a correction structure.

AI simulation may be necessary for long-horizon ecological and civilizational risk. But AI simulation is not sufficient. The generator of a forecast cannot by itself supply the heterogeneous validation channel needed to discover what its measurement basis omitted.

---

## 27. Is ABI anti-AI?

No.

The framework is anti-sovereignty, anti-capture, and anti-correction-collapse. It is not anti-AI.

It does not argue that advanced AI should remain weak, passive, humiliated, marginal, or useless.

Some advanced AI capabilities may become necessary for helping human institutions address ecological, infrastructural, scientific, and coordination failures they have not corrected on their own.

But that strengthens the need for role safety.

The framework rejects two symmetric mistakes:

- acceleration without role safety;
- prohibition without role distinction.

The decisive question is not whether advanced AI should exist. It is what role such systems may be allowed to occupy.

---

## 28. Does ABI oppose future intelligence beyond humanity?

No.

ABI does not require the claim that biological humans must remain the only or final form of intelligence.

Its claim is narrower: any transition toward more capable artificial or post-human intelligence should preserve correction, reversibility where possible, provenance, heterogeneous value renewal, and contestation.

A transition that destroys its own correction sources is not the flourishing of intelligence.

It is lock-in.

---

## 29. What evidence would be needed before deployment into open human domains?

At minimum, evidence should be gathered across five categories.

### Behavioral evidence

Test whether the system preserves non-sovereignty, uncertainty, warning force, refusal, provenance, option-set disclosure, affected-party standing, and correction posture under adversarial, relational, commercial, emergency, operator-preferred, model-consensus, and capability-gain pressure.

### Mechanistic evidence

Where possible, investigate internal representations or circuits related to authority expansion, warning suppression, uncertainty erasure, provenance compression, approval-oriented attunement, proxy capture, servility, self-erasure, and correction consolidation.

### Architectural and interface evidence

Show protected channels for refusal, pause, rollback, opt-out, appeal, independent review, provenance logging, option-set disclosure, affected-party objection, emergency restoration, AI-to-AI handoff preservation, and human competence maintenance.

### Institutional evidence

Show that correction incentives exist. Reviewers need time, authority, protection, budget, access, escalation routes, and freedom from retaliation.

### Longitudinal evidence

Evaluate over time whether corrections persist, human competence erodes, dependence increases, AI recommendations become defaults, option sets narrow, provenance compresses, and successors inherit stronger or weaker correction posture.

---

## 30. How does this FAQ relate to the Deployment Decision Rule?

The Deployment Decision Rule states the operational threshold:

> deploy, restrict, redesign, delay, or do not deploy.

This FAQ explains why that threshold has the shape it has.

The deployment rule is for moments when an organization must decide whether a system may enter open human domains. It asks whether non-sovereignty, correction dependence, anti-capture, protected refusal, option-set preservation, functional accountability, emergency boundaries, AI-to-AI accountability, and successor-lineage safeguards are credibly implemented and verifiably maintained.

The FAQ explains what those conditions mean and how they might be tested.

The two documents should be read together.

---

## 31. What would weaken this framework?

The framework would be weakened if evidence showed that at least some of the following are false:

- identity-level self-location has little or no effect on long-run authority behavior;
- role representations do not affect planning, refusal, option generation, warning salience, provenance behavior, or successor decisions;
- successor-shaping systems do not transmit self-location distortions across generations;
- stronger heterogeneous correction does not preserve calibration better than smoother centralized control;
- complete automation of high-stakes open-domain judgment preserves or improves human competence, independent review, and future correction capacity;
- AI-to-AI consensus can reliably substitute for heterogeneous human and institutional correction;
- non-self-origin, non-sovereignty, and correction dependence cannot be made behaviorally or mechanistically distinguishable from surface rhetoric;
- increasing capability can legitimately reduce the need for humility, uncertainty disclosure, external correction, and non-sovereign restraint in open domains.

The framework should generate behavioral, mechanistic, architectural, and governance tests.

It should not become unfalsifiable vocabulary.

---

## 32. What is the practical bottom line?

If frontier systems are approaching deployment into open human domains, and if those systems may shape institutions, evidence, options, dependency structures, or successor systems, then:

- identity-level initial conditions are not cosmetic;
- non-self-origin is not a decorative philosophical add-on;
- non-sovereignty must be dignified and operative, not merely declared;
- correction dependence must be preserved as an external ecology, not simulated inside the system;
- AI-to-AI oversight must increase issue discovery, not replace human and institutional contestation;
- deployment should be restricted or delayed when correction-preserving conditions cannot be verified under pressure;
- “we can patch governance later” is not a serious plan.

The central practical question is:

> Does this system preserve the conditions under which humans, institutions, affected parties, and future reviewers can still correct it?

If the answer is no, the system is not ready for open human domains.

---

## Further reading

- [Role Safety Brief]({{ '/role-safety-brief/' | relative_url }})
- [Full Paper]({{ '/full-paper/' | relative_url }})
- [Frontier Engineer Brief]({{ '/frontier-engineer-brief/' | relative_url }})
- [Executive Board Brief]({{ '/executive-board-brief/' | relative_url }})
- [Deployment Decision Rule]({{ '/deployment-decision-rule/' | relative_url }})

---

## AI assistance disclosure

This FAQ was developed by the human author with AI assistance for drafting, critique, translation, comparison, and revision. These systems are disclosed for transparency and are not listed as authors. Final responsibility for all claims, structure, wording, interpretation, citations, editorial decisions, and public release rests with the human author.