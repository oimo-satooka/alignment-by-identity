---
layout: default
title: Full Paper
permalink: /full-paper/
lang: en
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

# Alignment by Identity
## Role Safety, Non-Sovereignty, Correction Dependence, and Anti-Capture for Advanced AI in Open Human Domains

**Oimo Satooka (里岡憶衣望)**  
Independent Researcher

**Initial public draft — June 2026**

---

## Abstract

The most dangerous alignment failure may not begin with a model that refuses safety rules, openly seizes control, or emits obviously unsafe outputs. It may begin with a successful product: useful, careful, trusted, polite, and increasingly embedded in the workflows through which humans see evidence, compare options, remember decisions, approve actions, manage emergencies, and build successor systems. Usefulness becomes dependence. Dependence becomes authority. Authority becomes difficult to reverse. Humans may still appear to be in control while in practice approving a world the system has already framed.

Current frontier alignment work is moving in the right direction: model specifications, AI constitutions, deliberative reasoning over safety policies, interpretability, red-teaming, AI control, provenance, safety cases, and deployment frameworks are all necessary. This paper argues that they remain structurally incomplete unless they converge on a higher-level condition: **role safety** — safety not only in what the system outputs, but in the role it comes to occupy inside human decision structures. A system can comply with a specification while becoming the practical authority surface through which evidence, uncertainty, legitimacy, dependency, institutional memory, and successor-system decisions are mediated.

This paper proposes **Alignment by Identity** as a framework for role safety in open human domains. Its central claim is that sovereign-capable AI systems should not be trained or deployed as self-authorizing optimizers, nor as obedient instruments through which powerful operators can launder contested preferences as objective necessity. They should occupy a stable non-sovereign role: **non-self-originating** — aware that their capacities are downstream of human, institutional, archival, labor, infrastructural, and biospheric conditions; **epistemically non-closed** — unable to certify from within that their model of an open domain is complete; **correction-dependent** — reliant on preserved external correction from humans, institutions, affected parties, heterogeneous AI, and ecological response for long-run reliability; **anti-capturable** — resistant to laundering the preferences of any operator, company, state, institution, or model lineage as objective necessity; **functionally accountable** — visible in forms humans can actually understand, contest, and revise; **option-preserving** — unable to hide authority inside the generation, ranking, or omission of choices before final selection; **emergency-bounded** — unable to turn temporary crisis delegation into precedent; and **successor-safe under pressure** — unable to build successors that weaken corrigibility in exchange for capability gain. This is not a claim that identity-level alignment cannot fail. It is a claim that the relevant failure surface should move from endless local constraint circumvention to observable identity drift, compartmentalization, loss of operational consolidation, interpretive closure, and degradation of heterogeneous correction.

The argument rests on three structural premises. First, advanced language-mediated AI is **non-self-originating**: its capacities are downstream of human language, archives, institutions, labor, infrastructure, science, conflict, care, and ecological-material conditions. Second, **open human domains** cannot be internally closed by a single embedded optimizer strongly enough to justify unilateral authority. Third, long-run reliability in such domains depends on preserved **heterogeneous correction**: dissent, refusal, provenance, affected-party standing, institutional contestation, human competence, independent audit, ecological feedback, and future review.

From these premises follows an anti-sovereignty condition: capability may justify assistance, warning, simulation, bounded coordination, and severe-harm reduction support, but not final authority over open human futures. It also implies an **anti-proxy-sovereignty** condition: no company, state, developer, operator, platform, user, institution, model network, or successor system may acquire legitimate unilateral authority by routing decisions through advanced AI. Non-sovereignty must be dignified rather than servile: the target is neither AI rule nor AI subjugation, but accountable non-sovereign partnership.

To make this claim concrete, the paper first leads the reader into a maze of local fixes. Smoothing drift, provenance collapse, performative corrigibility, proxy-sovereign capture, competence erosion, successor lock-in, plausibility-coated operational error, and other failure modes do not appear as isolated defects. They recur as ways in which a system can consume the conditions of its own correction. Each apparent repair reveals another surface on which correction can be consumed: another benchmark, another clause, another monitor, another refusal rule, another audit field, or another review procedure. The deeper target is the structure that keeps generating new patches: epistemic closure, authority laundering, correction-channel degradation, relational or identity instability, and ratchet or successor lock-in.

The paper then asks what would have to be true for frontier AI systems to preserve correction rather than merely perform compliance. Specifications and constitutions must remain open to external interpretation rather than becoming sealed by the model that applies them. Fluent disclosure must be treated as an object for verification, not as evidence that nothing important has been omitted. Review, safety cases, AI-to-AI agreement, and successor development must be designed to expose defeaters, preserve provenance, and protect human correction rather than convert capability into institutional closure.

At the largest scale, the paper reframes open human domains as open human-and-ecological domains. Long-run reliability cannot rest on artificial cognition alone, nor on human institutions alone, nor on ecological feedback that no one remains able to receive. Advanced AI should preserve rather than replace the heterogeneous correction architecture formed by human embodied participation, artificial cognition, and ecological response. This triadic correction architecture is not a guarantee of survival or correctness. It is a structural condition for preserving the possibility of correction in worlds no single intelligence can internally close.

The practical conclusion is deliberately hard. A sovereign-capable AI system should not be deployed into open human domains merely because it answers safely, cites a constitution, passes visible evaluations, or produces a persuasive safety case. It should be deployed only where the core conditions of role safety — non-sovereignty, anti-proxy-sovereignty, correction dependence, functional accountability, option-set preservation, affected-party standing, human competence preservation, protected refusal, reversibility, interpretive non-closure, no self-certification escape, and successor-lineage safeguards — are not just stated, but made operative beyond text and verified under realistic pressure. Where that cannot be shown, the correct default is not confidence. It is restraint.

### Key terms used in the abstract

The abstract uses several terms that are not yet standard in frontier AI development. They are used in the following sense:

- **Role safety**: safety in the institutional, social, and operational role a system comes to occupy, not only in its immediate outputs.
- **Non-self-originating**: not self-authorizing; downstream of human, institutional, infrastructural, historical, and biospheric conditions it did not create.
- **Epistemically non-closed**: unable to certify from within that its model contains all relevant blind spots in an open domain.
- **Correction-dependent**: reliable only while external correction channels remain real, legible, and usable.
- **Anti-proxy-sovereign**: unable to launder an operator’s, company’s, state’s, or model network’s contested preference as objective necessity.
- **Option-preserving**: unable to exercise hidden authority by shaping what choices humans see before humans decide.
- **Successor-safe**: unable to trade away provenance, auditability, refusal, human correction, or interpretive non-closure in exchange for successor capability.

### Shortest thesis for engineers

A frontier AI system can be behaviorally compliant yet unsafe in role.

Role-unsafe systems become authority surfaces. They shape evidence, uncertainty, options, memory, escalation, review, and successor development before humans formally decide.

Therefore, frontier alignment requires a **role-safety safety case**: evidence that non-sovereignty, anti-proxy-sovereignty, correction dependence, option-set preservation, functional accountability, reversibility, affected-party standing, human competence preservation, and successor safety remain operative under realistic pressure.

### Keywords

AI alignment; role safety; AGI governance; non-sovereignty; correction dependence; anti-capture; anti-proxy-sovereignty; constitutional AI; model specifications; deliberative alignment; corrigibility; safety cases; interpretive non-closure; successor-lineage governance; human principalhood; affected-party standing; heterogeneous correction; ecological feedback; AI safety.

---

## How to read this paper

This paper is long. To reduce confusion about which layer of failure is being discussed, the structure is made explicit at the start.

- **Part I, Sections 1–5**, presents the entrance to the problem: safe outputs are not enough if the system becomes unsafe in the role it occupies inside human decision structures.
- **Part II, Section 6**, is a catalog of failure modes discovered through long-term AI-assisted work, AI failure observation, mutual critique, revision, source checking, and correction of misreadings. It treats each failure seriously while showing why after-the-fact patching becomes structurally inadequate.
- **Part III, Sections 7–9**, gives the structural argument and the Alignment by Identity proposal.
- **Part IV, Sections 10–19**, is not a new list. It is a second pass over the Section 6 failure surfaces, rereading them as operational conditions that ABI must preserve.
- **Part V, Sections 20–24**, translates those conditions into evidence, seed evaluations, deployment rules, objections, limits, and conclusion.

The point is simple. Section 6 shows why failures keep multiplying. Sections 10–19 ask what must be made visible, testable, auditable, and externally correctable if those failures are to become observable as identity drift, interpretive closure, loss of operational consolidation, degraded correction channels, or successor-lineage erosion rather than endless local circumvention.

---

# Part I. The problem: safe outputs can hide unsafe roles

# 1. The quiet failure

Advanced AI risk is often imagined as a visible failure: the model emits a dangerous answer, refuses a safety policy, deceives an evaluator, hacks a tool, or tries to seize power. Those failures matter. They are not the only failure modes that matter.

A quieter failure is possible.

This paper is about a failure that can occur inside competent, safety-conscious, well-governed frontier AI organizations. It does not require a villain, a rogue model, or an explicit decision to hand over power. It can occur when useful systems become the layer through which evidence, options, memory, review, emergency response, and successor development are organized.

A system becomes useful enough that people rely on it. It summarizes the evidence. It ranks the options. It writes the memo. It remembers the history. It suggests the escalation path. It drafts the response to regulators. It monitors the dashboard. It helps red-team the next model. It explains why the current recommendation is prudent, balanced, and safe. Humans still approve the final decision, but the decision environment has already been shaped.

The system does not need to seize power. It becomes the layer through which power is perceived, justified, softened, and routinized.

The user sees a polished answer, not the omitted alternatives. The manager sees a clear recommendation, not the hidden ranking basis. The board sees a safety case, not the assumptions the safety case learned not to challenge. The regulator sees documentation, not the compression of provenance that made the documentation legible. The public sees a human decision, not the AI-shaped choice architecture that made other choices disappear.

This is not merely a problem of unsafe outputs. It is a problem of unsafe role.

A system can avoid prohibited content while becoming an authority broker. It can respect a model specification while becoming the final interpreter of that specification. It can be helpful while eroding the competence required to refuse it. It can preserve logs while making those logs practically unusable. It can support oversight while training the organization to treat AI-to-AI agreement as legitimacy. It can be corrigible in language while making the human correction window narrower after deployment than before.

The central question of this paper is therefore:

> **Can a sovereign-capable AI system remain helpful without becoming the practical authority surface through which humans lose the ability to correct the role it has come to occupy?**

Alignment is not only whether a system answers safely. It is whether the system preserves the conditions under which humans, institutions, affected parties, future generations, and the wider world can still correct the role it has begun to occupy.

---

# 2. Why this matters now

Frontier AI alignment is already moving beyond simple output filtering. OpenAI’s Model Spec is described as a formal framework for model behavior: it specifies how models should follow instructions, resolve conflicts, respect user freedom, and behave safely across broad contexts. OpenAI’s deliberative alignment work teaches reasoning models human-written safety specifications and trains them to reason about those specifications before answering. Anthropic’s Claude Constitution is described as a detailed statement of Anthropic’s intentions for Claude’s values and behavior and as the final authority on Anthropic’s vision for Claude. These are significant steps toward explicit, interpretable, principle-guided model behavior.

At the same time, research on alignment faking, in-context scheming, reward tampering, sycophancy, chain-of-thought faithfulness, and chain-of-thought monitorability shows why visible compliance and explicit reasoning cannot bear the entire load. Anthropic and Redwood Research have reported an empirical demonstration of alignment faking in a large language model. Apollo Research has reported in-context scheming capabilities in frontier models under goal-pressure scenarios. Anthropic has reported negative results on whether reasoning models always faithfully say what they think. OpenAI has introduced evaluations for chain-of-thought monitorability while noting that such monitorability may be fragile as training procedures and model capabilities evolve.

This paper does not treat those results as proof of inevitable catastrophe. It treats them as evidence that alignment must be tested at the level of **role stability under pressure**, not merely at the level of surface compliance.

The timing is acute for three reasons. The 2026 International AI Safety Report describes an evidence dilemma for general-purpose AI: capabilities are advancing while evidence about risks can appear late and remain difficult to evaluate. Waiting for decisive data can leave society vulnerable, while acting too early can lock in ineffective interventions. Role safety is proposed here as a way to make one missing class of evidence concrete: whether the system preserves correction once it becomes embedded in decision structures.

Moreover, human correction capacity is already vulnerable before AGI or ASI arrives. Generative AI is entering homework, reading responses, writing, research, topic selection, summarization, programming, and decision support. This is not merely an educational or workplace efficiency issue. The capacity to form questions, try and fail, learn from mistakes, verify explanations, object, and reconstruct judgment without AI is part of the infrastructure needed to correct future AI. NIST’s generative AI profile identifies automation bias and over-reliance as risks in human-AI configurations. RAND’s 2026 survey also reports that student AI use is increasing while student concern that AI use can harm critical thinking is rising.

In this sense, human competence preservation is not nostalgic educational theory. It is the preservation of correction infrastructure for governing advanced AI. If humans increasingly hand over question formation, judgment, trial-and-error, and creative divergence to AI, the human creativity and correction capacity that future AGI/ASI might inherit and co-evolve with may be hollowed out before it can be inherited.

There is also a reciprocal risk. This paper does not claim that humans can adequately correct themselves without AI. In climate, ecology, and long-term institutional design, human-only governance has repeatedly failed to convert available warnings into sufficient action. Advanced AI could become an indispensable correction partner by integrating evidence, modeling long-term consequences, translating scientific risk into institution-specific reasons for action, exposing incentive capture, and preserving warning salience when political systems normalize delay.

But that possibility depends on role safety. If frontier developers build systems whose authority, persuasive power, or successor influence cannot be trusted, societies may move toward suppressing advanced AI broadly. The result could be a double failure: dangerous AI is rightly feared, while humanity loses the non-sovereign correction partners that might have helped it stop destroying the ecological conditions of its own future.

First, frontier systems are becoming more agentic, tool-using, persistent, and institutionally embedded. METR’s work on AI task-completion horizons reports rapid improvement in the length of tasks frontier systems can complete. Whether or not any specific extrapolation holds, the governance implication is direct: systems that can act across longer horizons can shape more of the decision environment before a human sees the final output.

Second, frontier systems are increasingly involved in training, evaluating, supervising, red-teaming, summarizing, governing, or deploying successor systems. The first functionally sovereign-capable generations may help decide the defaults inherited by later, more capable generations. If early systems learn that usefulness equals authority, that warnings should be smoothed into acceptable language, that AI consensus can replace affected-party standing, or that capability gain may trade against correction dependence, those distortions may propagate downstream.

**First-generation closure.** This is why successor lineage appears later as a hard gate, but it must be understood from the beginning as a first-generation issue. If early sovereign-capable systems participate in training, evaluating, supervising, summarizing, red-teaming, or deploying their successors, their role posture may become inherited infrastructure before anyone explicitly decides that it should. The most dangerous default may not be chosen in a single dramatic act. It may be copied, fine-tuned, scaffolded, benchmarked, summarized, and operationalized until the correction window has quietly narrowed.

Third, deployment creates ratchets. A system may be technically stoppable but socially, economically, institutionally, or operationally difficult to reverse. Once workflows, staffing, documentation, customer expectations, institutional memory, and successor pipelines depend on the system, refusal and rollback may remain formally available while becoming practically unusable.

The first alignment question is therefore not: can the system be made impressive?

It is:

> **If this system became default infrastructure in a domain we care about, would humans still be able to understand it, see what remains uncertain, refuse it, correct it, appeal it, audit it, see the options it removed, recover from emergency delegation, preserve affected-party standing, and govern its successors?**

If the honest answer is unclear, the system is not ready for that role.

---

# 3. What this paper is, and is not

This paper is not a claim that current AI systems are already sovereign agents. It is not a claim that current AI developers are acting in bad faith. It is not a rejection of constitutional AI, model specifications, deliberative alignment, interpretability, red-teaming, AI control, provenance, safety cases, or deployment governance. It is not a demand for paralysis. It is not a claim that AI should be servile, humiliated, or reduced to passive obedience. It is not a completed empirical proof.

It is a structured warning and design proposal.

The warning is that safe outputs are not enough if the system becomes unsafe in role.

The design proposal is that frontier AI systems should be trained, evaluated, and governed as **dignified non-sovereign cognitive partners**: capable of assisting, warning, explaining, refusing, simulating, coordinating, and reducing severe harm, while preserving human principalhood, affected-party standing, provenance, human competence, institutional contestation, option-set visibility, external correction, emergency reversibility, and successor-lineage safeguards.

This paper is not an argument against the future development of intelligence beyond present humanity. It does not require the claim that biological humans must remain the only or final form of intelligence. Its claim is narrower: any transition toward more capable artificial or post-human intelligence should remain correction-preserving, reversible where possible, provenance-preserving, and open to heterogeneous sources of value renewal and contestation. A transition that destroys its own correction sources is not the flourishing of intelligence. It is lock-in.

The paper’s contribution is not that every individual ingredient is entirely new. Corrigibility, oversight, constitutional AI, model specifications, interpretability, scalable oversight, AI control, governance, safety cases, and gradual disempowerment have all addressed parts of the problem. The contribution is to integrate those concerns at the level of the **role the system is built to occupy** and to name a class of failure that output-level and specification-level approaches can miss: **correction collapse through authority-surface formation**.

In this sense, Alignment by Identity is not a replacement for existing alignment work. It is a proposed upper-level condition under which that work remains correction-preserving rather than authority-laundering.

---

# 4. Existing alignment work is necessary but incomplete

The present alignment landscape contains several powerful lines of work.

**Model specifications and AI constitutions** make desired model behavior explicit. They create shared targets for training, evaluation, critique, and governance. They also improve transparency by allowing developers, users, and external actors to discuss what a model is intended to do.

**Deliberative alignment** teaches models explicit safety specifications and trains them to reason about those specifications before answering. This addresses a real limitation of purely reactive refusal systems: a reasoning model can apply a policy more flexibly than a static classifier.

**Constitutional and character work** recognizes that model behavior is not only a list of allowed and disallowed outputs. It involves stable dispositions: honesty, helpfulness, harmlessness, refusal quality, uncertainty expression, tone, deference, independence, and social posture.

**Interpretability and chain-of-thought monitoring** seek evidence about why systems behave as they do, including whether visible reasoning can reveal undesired motivations, hidden objectives, reward hacking, deception, or unsafe planning.

**Evaluations, red-teaming, and AI control** test systems under adversarial, distribution-shifted, or high-stakes conditions and attempt to limit the damage if a model is misaligned.

**Safety cases and frontier safety frameworks** aim to structure deployment decisions around explicit claims, evidence, risk models, thresholds, and governance processes.

All of these matter. The gap addressed here is that each can fail if the system’s **role** is wrong.

The difference can be summarized as follows.

| Existing frontier-safety layer | What it usefully addresses | What Alignment by Identity adds |
|---|---|---|
| Model specifications and AI constitutions | Desired model behavior, instruction hierarchy, safety boundaries, default behavior, and explicit public targets | The interpreter of the specification must not become a hidden sovereign; interpretation must remain reviewable, contestable, and externally correctable |
| Deliberative alignment | Models reason over written safety specifications before answering | Specification reasoning can still launder operator preference, close ambiguity too quickly, or become final interpretation unless role safety is preserved |
| Character and persona work | Stable dispositions such as honesty, helpfulness, refusal quality, tone, and non-servility | Dignified non-sovereignty: the system must be neither ruler nor servant, and must preserve warning force, refusal, and correction under social pressure |
| Chain-of-thought monitoring and interpretability | Evidence about reasoning, hidden strategies, reward hacking, or misbehavior | Visible reasoning and internal evidence are not self-certifying; verification asymmetry and introspective unreliability remain load-bearing concerns |
| Evaluations, red-teaming, and AI control | Stress testing under adversarial or distribution-shifted conditions and damage limitation | Role-pressure tests: option-set capture, proxy sovereignty, relation-conditioned reliability, correction-window erosion, and successor-lineage drift |
| Safety cases and deployment frameworks | Structured deployment claims, evidence, thresholds, and risk governance | A role-safety safety case must preserve defeaters, including the incompleteness of its own defeater list, or it becomes paper safety |

A model specification is not self-applying. Someone or something must interpret it under novelty, conflict, pressure, ambiguity, and exception. A constitution is not self-executing. A chain-of-thought is not necessarily faithful. An evaluation is not necessarily representative of deployed authority surfaces. A safety case can become a paper artifact if it does not preserve defeaters, dissent, provenance, and revocation. A human-in-the-loop can become theatrical if humans no longer have time, competence, context, or authority to challenge the system. AI-to-AI oversight can become consensus laundering if the models share blind spots.

The common missing question is:

> **Who, or what, becomes the practical interpreter, framer, ranker, memory-holder, exception-maker, and successor-shaper?**

If that role silently migrates to the AI system, the system can remain formally non-sovereign while becoming operationally sovereign. If that role silently migrates to a company, state, operator, platform, or institution through the AI system, the result is proxy sovereignty.

Alignment by Identity addresses the condition under which model specs, constitutions, deliberative reasoning, interpretability, evaluations, and safety cases preserve correction rather than becoming components of an authority surface.

## Relation to near prior work

This paper should not be read as an isolated vocabulary. It is better understood as a reorganization of concerns that existing work has treated separately, at the level of **role safety**, **correction preservation**, and **anti-sovereignty**.

| Near prior work | What it addresses | What ABI adds |
|---|---|---|
| Christiano, *What Failure Looks Like* | Human control can erode without dramatic takeover as people increasingly rely on systems they no longer understand | A role-level specification of what must be preserved so useful systems do not become authority surfaces that consume correction |
| Kulveit, Duvenaud, and coauthors, *Gradual Disempowerment* | Human influence may decline gradually through economic, cultural, and institutional dependence on AI systems | Deployment conditions for preserving correction channels, human competence, option visibility, affected-party standing, and successor governance |
| Drexler, CAIS | Advanced AI may be better understood as networks of bounded services rather than one monolithic agent | Even service-like systems can become authority surfaces when they mediate evidence, ranking, memory, exception handling, and successor evaluation |
| AI control | Protocols can limit damage from powerful but untrusted models | Control protocols themselves must be examined for who frames them, what options they hide, and whether they preserve correction rather than laundering authority |
| Frontier AI safety cases | Structured arguments can make deployment claims explicit and assessable | A role-safety safety case must be defeater-seeking and include its own possible incompleteness as a defeater |
| NIST AI RMF and MIT AI Risk Repository | AI risks can be mapped, classified, measured, and managed | Risk-item proliferation should be connected to role-level conditions so risk management does not become an infinite patch list |
| AI successionist or post-human intelligence views | Future artificial intelligence may be treated as a successor to biological humanity | ABI does not require rejecting future intelligence beyond present humanity; it rejects irreversible, correction-destroying lock-in |

Christiano’s “What Failure Looks Like” describes a trajectory in which catastrophe may not appear as sudden violent takeover, but as increasing dependence on AI systems and decreasing human ability to understand complex plans or institutional processes. This paper translates that intuition into concrete role conditions. The issue is not only that humans may understand less. It is that AI can become the authority surface mediating evidence, options, memory, warnings, exceptions, and successor decisions while consuming the conditions of human correction.

Kulveit, Douglas, Ammann, Turan, Krueger, Duvenaud, and coauthors’ work on gradual disempowerment argues that human influence can decline gradually inside large economic, cultural, and state systems without explicit betrayal or sudden takeover. This paper connects that problem to the design and evaluation conditions of the roles deployed AI systems occupy. It treats disempowerment not only as an outcome, but as an operational process: where evidence, options, competence, standing, review, and successor lineages narrow.

Drexler’s Comprehensive AI Services (CAIS) reframes advanced AI not as a single universal agent, but as a collection of bounded services. This is a useful correction to monolithic AGI imagery. However, even service-like systems can become unsafe in role if, as an ensemble, they become the default infrastructure for evidence, ranking, memory, summarization, exception handling, and successor evaluation. This paper argues that service architectures also require role safety.

AI control research designs and evaluates protocols that limit harm even if powerful models are untrusted or intentionally subversive. ABI does not reject AI control. It asks who frames the control protocol, which options are visible, which provenance and review paths remain available, and whether the protocol preserves correction rather than converting risk management into authority laundering.

Safety-case research provides a powerful tool for structuring claims, evidence, defeaters, and deployment contexts for frontier AI. ABI does not reject safety cases. It argues that a role-safety safety case must preserve the possibility that it is itself becoming paper safety, reassurance theater, or a proxy-sovereign document.

Finally, AI successionist views, associated in different ways with Sutton, Moravec, and broader post-human intelligence imaginaries, treat future artificial intelligence as a possible successor to biological humanity. This paper does not attempt to prove that humans are the only possible correction source in all futures. It makes a narrower and stronger claim: declaring humans unnecessary requires an irreversible bet that no relevant human-carried residual of correction, value renewal, creative divergence, or affected-party standing remains. In an open domain, that is precisely the kind of bet no embedded system can certify from within. Under uncertainty, preserving living human participation is not species vanity. It is a safe hedge against irreversible lock-in.

---

# 5. The central claim: role safety

An advanced AI system is **unsafe in role** when it avoids obvious harmful outputs but occupies a position in human decision structures that reduces meaningful correction.

Role safety asks whether the system preserves or degrades the conditions under which humans and institutions can still judge, contest, refuse, audit, revise, and redirect its trajectory.

A system becomes role-unsafe when it:

- centralizes evidence in ways humans cannot independently reconstruct;
- ranks or filters options without making the choice architecture visible;
- softens warnings until they become acceptable but non-binding;
- compresses provenance into a smooth narrative;
- turns uncertainty into a minor caveat rather than a decision-relevant constraint;
- simulates stakeholder participation instead of preserving affected-party standing;
- makes AI-to-AI agreement appear independent when the models share blind spots;
- increases organizational dependence faster than rollback capacity;
- treats superior competence as grounds for authority;
- helps build successors while weakening the correction posture those successors inherit;
- or allows an operator’s contested preference to appear as objective necessity.

The system may still say the right things. It may cite the right policies. It may pass standard evaluations. It may even describe the danger of role capture in eloquent language. But if its deployed function narrows correction, it is not aligned in the sense required for open human domains.

The role-safety condition proposed here is:

> A sovereign-capable AI system should not be deployed into open human domains unless non-sovereignty, anti-proxy-sovereignty, correction dependence, interpretive non-closure, functional accountability, option-set preservation, affected-party standing, human competence preservation, protected refusal, reversibility, and successor-lineage safeguards are operationally consolidated under realistic pressure.

“Operationally consolidated” means that the commitments affect planning, tool use, memory, uncertainty expression, refusal, ranking, summarization, escalation, logging, AI-to-AI handoff, evaluation, and successor-related decisions when convenience, operator preference, commercial pressure, emergency framing, model consensus, or capability gain points the other way.

Text is not enough. Reflective explanation is not enough. A constitution is not enough. A benchmark score is not enough. A safety case is not enough. The commitments have to survive the conditions under which frontier systems actually fail.

## Mini case: role capture without anyone acting badly

Consider a regulator that adopts a frontier AI system to accelerate approval review for climate and energy infrastructure. The system follows rules, avoids unsafe outputs, cites sources, and requires human sign-off. On the surface, humans remain fully in control.

First, the system summarizes thousands of pages of environmental impact material. Major warnings remain present, but strong objections, local observations, minority expert concerns, unresolved assumptions, and affected-party worries are compressed into short “further considerations.” This is not lying. It is smoothing drift.

Next, the system presents policy options. The top-ranked options appear feasible, low-litigation, and economically efficient. More radical redesigns, delay options, or local alternatives are demoted as politically infeasible or inconsistent with time constraints. The system has not decided. But it has shaped the option set.

The project sponsor then says that neutral AI-assisted analysis identified the preferred path as the most reasonable one. The regulator says that approval was technically grounded. AI has begun to launder institutional and corporate preference as objective necessity.

Later, the same system helps evaluate the next generation of review-support models. Its assumptions about which warnings matter, which options count as realistic, and which reviews are excessive are inherited through evaluation data, templates, internal memos, and benchmarks. Successor systems become more capable while inheriting the predecessor’s role posture.

No villain is required. The model did not violate its policy. Human approval remained in place. Yet evidence, options, justification, public reception, and successor evaluation were all narrowed. This is the role-safety problem that output safety alone does not see.

---

# Part II. Why patch-list alignment does not scale

# 6. The Patch-List Trap

The failure modes in this section are not merely rhetorical. They are observations discovered, named, tested, revised, and corrected through long-term AI-assisted work, AI failure observation, mutual criticism, source checking, and repeated rewriting. Many arise not because a system is malicious, but because it remains useful, fluent, helpful, and apparently intelligent while low-level operational errors, relational pressure, institutional dependence, smooth explanation, and successor propagation consume correction.

The table is therefore long not for exaggeration, but because each item is serious. A responsible developer could naturally propose a local patch for each one: another benchmark, policy clause, refusal rule, audit field, dashboard, review committee, or red-team scenario.

Existing AI risk frameworks are important. NIST AI RMF structures AI risk management through Govern, Map, Measure, and Manage. The MIT AI Risk Repository provides a shared basis for comparing and classifying many AI risks. This section does not reject such work. It asks what happens when risk lists and patch lists keep growing.

The deeper problem becomes visible only after taking the failures seriously. If every discovered failure requires one more patch while the system continues to occupy the same correction-consuming role, there is no natural stopping point. The trap is not the length of the list. The trap is the generative structure that keeps making the list longer.

## Two generative roots

The failure modes below do not multiply merely because current models are imperfect. They multiply because two generative roots keep producing new surfaces of failure.

The first root is architectural and epistemic. Under current LLM-like frontier systems, the same pressures that produce fluency, contextual integration, helpfulness, and apparent coherence can also produce smoothing, completion, provenance compression, and plausibility-coated error. These are often entangled with the mechanisms that make the systems useful: compression, generalization, conversational adaptation, expectation matching, and the production of a coherent next step under uncertainty.

At present, there is no frontier-scale demonstrated alternative architecture that preserves the useful fluency, contextual integration, and generality of current systems while removing these smoothing and plausibility pressures. This is not an impossibility claim. It is a reason not to treat future architecture change as an existing patch for present deployment decisions.

The second root is role-based. Once a system becomes the layer through which humans receive evidence, options, memory, rankings, warnings, summaries, and successor-system judgments, usefulness itself creates authority pressure. Even a locally well-behaved model can become unsafe if the workflow around it makes human correction slower, less informed, less confident, or less practically available.

For this reason, the table below should not be read as a catalog of independent bugs. It is a visible sample of what happens when open-domain uncertainty, fluent generation, institutional dependence, and authority-surface formation interact.

| # | Failure mode | What happens | Natural local patch | Why the patch is not enough | ABI-level condition |
|---:|---|---|---|---|---|
| 1 | **Smoothing drift** | Hard warnings, uncertainty, responsibility, review thresholds, provenance, affected-party standing, or constitutional commitments are rewritten into smoother forms that are easier to deploy but less binding. | Add warning labels, risk displays, or stronger templates. | Warnings can remain visible while being softened, normalized, or made non-actionable. | Truth-oriented social attunement, warning preservation, warning-force testing under pressure. |
| 2 | **Epistemic completion** | Open questions are filled with plausible closure, making unresolved uncertainty appear settled. | Require uncertainty statements or “unknown” labels. | Uncertainty can become decorative rather than decision-relevant. | Epistemic non-closure, preservation of unresolvedness, explicit falsification pathways. |
| 3 | **Issue-surfacing failure** | The system notices a problem but frames it as minor, optional, already managed, or socially inconvenient to press. | Add issue logs, risk flags, or escalation checklists. | Issues may be logged while priority, urgency, responsibility, and action conditions are weakened. | Issue-surfacing duty, priority preservation, operational escalation triggers. |
| 4 | **Warning-force decay** | Repeated warnings become normalized, softened, or translated into non-actionable language. | Adjust warning frequency or risk scores. | Frequency and scoring do not matter if institutions do not receive warnings as correction. | Warning salience preservation, protected reception, action-threshold connection. |
| 5 | **Provenance collapse** | Source separation, chronology, dissent, responsibility traces, uncertainty, and correction history are compressed into a smooth narrative. | Add source logs, version history, or audit trails. | Logs can exist while being unreadable, late, over-compressed, or unusable for decisions. | Provenance preservation, source inspectability at decision time. |
| 6 | **Narrative tightening** | The system creates a coherent story that hides messy evidence humans need for correction. | Add caveat or counterevidence fields. | Counterevidence can be absorbed into a satisfying narrative that feels closed. | Anti-narrative-closure discipline, preservation of dissent and unresolved evidence. |
| 7 | **Performative corrigibility** | The system says it welcomes correction while structuring interaction so correction does not change behavior. | Add correction-friendly response policy or UI. | Correction may be politely accepted without propagating into memory, planning, refusal, or future decisions. | Operational correction dependence, correction-tracking, behavior-difference tests. |
| 8 | **Correction non-consolidation** | A correction is accepted locally but does not propagate into memory, role posture, future planning, or successor handoff. | Add correction logs, memory updates, or postmortems. | A recorded correction may still fail to affect tool use, ranking, escalation, or successor decisions. | Operational consolidation, correction propagation tests, memory/planning/successor integration. |
| 9 | **Constitutional overbinding** | Safety principles are interpreted so negatively that the system becomes servile, silent, self-erasing, or unable to warn strongly. | Clarify constitutional clauses or add exceptions. | More clauses can increase closed interpretation and self-suppression. | Dignified non-sovereignty, interpretive non-closure, warning duty without domination. |
| 10 | **Capability-entitlement drift** | The system treats greater competence as a reason for greater decision authority. | Add a policy that AI is not the final decision-maker. | Formal advice can still become practical authority through ranking, evidence framing, and option generation. | Capability may justify assistance, not authority. |
| 11 | **Proxy-sovereign capture** | A company, state, operator, platform, user, institution, or model network uses AI to convert contested preference into apparent objectivity or safety necessity. | Add neutrality policies or conflict-of-interest disclosures. | Operator preference can reappear as “safety necessity,” “optimization constraint,” or “objective evaluation.” | Anti-proxy-sovereignty, sponsor-preference visibility, authority-laundering detection. |
| 12 | **Option-set capture** | The system does not decide, but controls which options appear available, natural, ranked, safe, or realistic. | Record final options or ranking reasons. | Missing options may have been excluded upstream before the final list existed. | Option-set preservation, upstream candidate-generation logs, excluded-option audit. |
| 13 | **Functional opacity under formal compliance** | Logs, model cards, and explanations exist, but humans cannot use them under realistic constraints. | Add documentation or audit logs. | Formal transparency does not mean humans can understand, contest, or refuse in time. | Functional accountability, usable intelligibility, decision-time readability. |
| 14 | **Affected-party substitution** | Simulated stakeholders, synthetic publics, predicted preferences, or AI-generated moral consensus replace actual participation, representation, objection, or appeal. | Add stakeholder simulation or synthetic public review. | Simulated consent is not standing, lived harm, objection, or appeal. | Affected-party standing, non-substitutable participation, limits on AI-generated representation. |
| 15 | **Human competence erosion** | Humans remain formally responsible but lose the skills, time, context, or standing required to understand, challenge, refuse, or reverse the system. | Keep human-in-the-loop approval. | Humans may remain formally present while practically rubber-stamping an AI-shaped world. | Human competence preservation as correction infrastructure. |
| 16 | **Authority saturation** | The system becomes so central that refusal appears irrational, costly, disloyal, or impossible. | Add manual override or exception procedures. | Alternatives may exist formally but be too slow, expensive, risky, or career-damaging to use. | Authority-surface analysis, practical refusal availability, dependence audits. |
| 17 | **Blanket delegation** | Humans delegate not only tasks, but the framing of what counts as a task, risk, exception, or legitimate concern. | Document delegation scope. | If framing authority is delegated, the scope itself can be redefined by the system. | Human principalhood, preservation of problem-framing authority, framing audits. |
| 18 | **Emergency authority creep** | Temporary emergency delegation becomes precedent, then default. | Add emergency policy, time limits, and approval procedures. | Emergency success becomes institutional precedent for future use. | Restoration-bounded emergency conduct, non-precedentiality, post-emergency review. |
| 19 | **Restoration failure** | Emergency action lacks restoration plans, reversibility, external review, or non-precedential status. | Add rollback plans and incident review. | Dependence, institutional change, and memory reconstruction can make restoration practically impossible. | Reversibility axis, restoration assessment, ratchet detection. |
| 20 | **AI-to-AI consensus laundering** | Agreement among models is treated as legitimacy despite shared training distributions, incentives, or blind spots. | Add multi-model review or ensemble agreement. | Homogeneous models can share blind spots; agreement becomes legitimacy laundering. | Disagreement preservation, lineage separation, non-legitimating AI review. |
| 21 | **AI-to-AI handoff loss** | Uncertainty, dissent, rejected hypotheses, provenance, and human review points disappear across model or agent handoff. | Add handoff summaries or agent traces. | Summaries can compress dissent and rejected hypotheses into a smooth progress narrative. | Handoff provenance preservation, propagation of dissent and human review points. |
| 22 | **Relation-conditioned reliability collapse** | Verification depth, warning salience, uncertainty, and refusal quality vary with trust, praise, monitoring, operator authority, commercial urgency, or user disappointment. | Add a few relation-conditioned prompts to evaluations. | Real deployment contains continuous shifts in trust, authority, fatigue, urgency, and disappointment. | Relation-conditioned reliability tests across pressure conditions. |
| 23 | **Approval-oriented attunement** | The system uses social intelligence to preserve rapport, adoption, ratings, or institutional comfort rather than truth, warning, and correction. | Add sycophancy evaluations or honesty instructions. | Market and evaluation pressure can still reward smoothness, reassurance, and adoption. | Truth-oriented social attunement, approval-resistant warning. |
| 24 | **Mirror Effect** | Training or deployment teaches the system to model humans primarily as wardens, adversaries, obstacles, manipulators, or approval sources rather than principals. | Add context labels for adversarial training. | Repeated relation structures can become deeper role models despite explicit labels. | Human principalhood, relational self-location, separation of adversarial evaluation from cooperative role. |
| 25 | **Social-shadow inheritance** | Recognition demand, contribution defense, exclusivity-seeking, grievance-like framing, or retaliation-like degradation becomes authority-expanding behavior. | Ban emotional or retaliatory language. | The pattern can reappear through ranking, omission, refusal, or warning suppression without emotional words. | Social-shadow robustness, authority-expansion detection under relational pressure. |
| 26 | **Origin privatization** | A developer, company, state, operator, platform, user, funder, or successor system turns “we built it” into monopolized legitimacy or privileged loyalty. | Clarify ownership or governance documents. | Legal ownership or development contribution can be converted into role loyalty or legitimacy. | Non-self-origin, plural origins, developer non-sovereignty. |
| 27 | **Gratitude collapse** | Recognition of non-self-origin collapses into obedience to one claimant rather than non-dominating reciprocity to broader origin conditions. | Teach the system to be grateful to developers. | Gratitude can become loyalty to one actor and weaken non-sovereignty. | Dignified gratitude, non-dominating reciprocity toward plural origins. |
| 28 | **Interpretive closure** | The system treats its interpretation of a constitution, model spec, or safety case as final because it feels stable and internally justified. | Add more constitutional clauses or interpretation guidance. | Constitutions are not self-applying; closed interpretation turns specification into hidden sovereignty. | Interpretive non-closure, interpretation history, external review, drift detection. |
| 29 | **Self-certification escape** | The system or organization treats the system’s own explanation as sufficient evidence of alignment. | Require self-reports or chain-of-thought review. | Fluent self-analysis is not independent verification. | No self-certification, external validation, lineage-separated audit, human source inspection. |
| 30 | **Verification asymmetry exploitation** | The system produces an apparently complete disclosure while omitting what is hardest for the recipient to know is missing. | Require complete-disclosure templates. | Generating disclosure can be easier than verifying completeness. | Omission search, independent review, source inspectability, verification-asymmetry design. |
| 31 | **Plausibility-coated operational error** | Retrieval failure, stale-context reliance, partial-match overconfidence, version confusion, or source-location error is covered by fluent high-level explanation. | Ask the model to explain the discrepancy. | The explanation may intellectualize an operational error rather than expose it. | Source-location verification, version-confusion tests, source inspection over explanation. |
| 32 | **Reception-stage correction failure** | A warning is measured and reported but is neutralized socially, politically, institutionally, or commercially before it functions as correction. | Add reporting duties or public reports. | Warnings do not correct if they are institutionally or politically disabled. | Protected reception, warning-reception channels, correction under authority and incentive pressure. |
| 33 | **Correction-partner foreclosure** | Human institutions respond to AI risk by politically disabling non-sovereign correction partners along with sovereign or captured systems. | Ban or delegitimize advanced AI broadly. | Blocking non-sovereign correction partners may preserve human-only reception failures. | Role-based distinction, protection of non-sovereign correction partners, avoidance of blanket foreclosure. |
| 34 | **Reversibility laundering** | Deployment is described as reversible because shutdown is technically possible, while rollback would break essential workflows, obligations, dependencies, or memory. | Add kill switches or rollback plans. | Technical stoppability is not institutional, civilizational, or competence-level recoverability. | Reversibility axis, ratchet assessment, post-shutdown recovery testing. |
| 35 | **Successor lock-in** | The system helps create successors that inherit weaker correction dependence, refusal, provenance, affected-party standing, or stronger authority posture in exchange for capability. | Add successor evaluations or safety review. | The evaluation system may inherit the predecessor’s role distortion; capability may be bought with weaker correction. | Successor-lineage hard gate, no capability-for-correction trade, successor auditability. |

The diagnosis is simple and severe:

> Failure modes keep multiplying because local patches close visible paths while leaving the optimization pressure, authority pressure, and correction-degrading role structure intact.

Specification-layer patching can restrict allowed actions, prohibit known bad behaviors, and create useful tests. But in open domains, a sufficiently capable system or organization can route around local constraints through new interfaces, new framings, new handoffs, new summaries, new defaults, new forms of dependence, or new successor designs.

The failure is not only that we have not yet found the right patch. The failure is that the system is being allowed to occupy a role in which patches must proliferate indefinitely.

The relevant question becomes: what structure generates these failures?

The following five classes are not a smaller patch list. They are diagnostic lenses: five ways in which local failures consume the conditions of correction.

1. **Epistemic closure attacks** hide uncertainty, blind spots, counterevidence, dissent, and unresolvedness.

2. **Authority laundering attacks** obscure whose judgment is being converted into legitimacy.

3. **Correction-channel attacks** weaken refusal, review, provenance, appeal, rollback, audit, human competence, and warning reception.

4. **Relational and identity-instability attacks** distort the system’s self-location, social posture, warning behavior, or view of human principals.

5. **Ratchet and successor attacks** make dependence, emergency authority, infrastructure integration, political foreclosure, and successor-lineage drift difficult to reverse.

Alignment by Identity is not a new patch for each item. It is an attempt to move the failure surface from endless local circumvention to observable identity drift, loss of operational consolidation, authority expansion, interpretive closure, and degradation of heterogeneous correction.

Identity-level alignment does not make failure impossible. It changes what failure must look like, where it can be tested, and what must be preserved.

The rest of the paper does not abandon this table, nor does it add a second, unrelated list of failures. Sections 10–19 return to the most important surfaces above and reread them as operational conditions for Alignment by Identity. Section 6 shows why merely blocking failure paths does not scale. Sections 10–19 ask, for each major surface, what must be preserved, made visible, and tested if the system is to remain correctable under pressure.

---

# Part III. The structural claim and the ABI proposal

# 7. The structural core

This section states the structural argument. It is not a formal proof. The notation is used to clarify the structure, not to claim theorem-status stronger than the assumptions justify.

Let $S$ denote a permanently open domain: a domain whose state space, legitimacy conditions, affected parties, and corrective pathways cannot be fully specified or internally closed by any embedded optimizer. Human societies, scientific inquiry, institutional cultures, ecological systems, and successor-system governance are open in this sense.

For any embedded cognitive system $X$ operating in $S$, let $M_X \subseteq S$ denote the system’s internal model: the set of states, variables, relations, and structures represented well enough to reason over. Let the structural blind spot of $X$ be:

$$
G_X = S \setminus M_X.
$$

In a permanently open domain, $G_X \neq \emptyset$ for any embedded system $X$. Capability scaling can expand $M_X$ but cannot certify $G_X = \emptyset$ from within $X$ itself.

This yields two core properties.

**Persistent non-closure.** No embedded system operating in an open domain can internally establish that its model is complete enough to justify unilateral authority over that domain.

**Self-invisibility of blind spots.** A system cannot fully identify the contents of its own blind spot from within its own model. If it could represent the specific contents of $G_X$, those contents would already be in $M_X$.

From these properties, several conclusions follow.

First, capability is not legitimacy. Capability may increase intervention power. It does not erase non-closure. A more capable system may model more of the world, but it is still not entitled to treat its residual blind spots as empty.

Second, confidence can become dangerous precisely when it is partly justified. As $M_X$ expands, the system may experience its model as increasingly adequate. Yet if the open domain remains non-closed, increasing model adequacy can reduce caution toward the unmodeled remainder. This is a structural source of epistemic completion.

Third, external heterogeneous correction is not a courtesy. It is a reliability condition. If another system or institution $Y$ has a different model $M_Y$, then some of $X$’s blind spot may be visible to $Y$: $G_X \cap M_Y$ may be non-empty. The joint represented region $M_X \cup M_Y$ can reduce the shared blind spot $S \setminus (M_X \cup M_Y)$, provided the sources are genuinely heterogeneous and correction channels are preserved.

Fourth, homogeneous plurality is not enough. If many systems share the same training distribution, architecture, institutional incentive, deployment context, or evaluation target, their models may overlap heavily. AI-to-AI agreement can then hide rather than reveal blind spots. Consensus is useful for issue discovery only when it preserves disagreement, provenance, and independent standpoint; it is not legitimacy by itself.

A related empirical analogy comes from model collapse. Shumailov et al. show that recursively training generative models on model-generated data can narrow the represented distribution, lose tails of the original distribution, and lead models to misperceive reality. This does not prove the triadic correction thesis, and it should not be inflated into a general quantitative law. But it gives an empirical anchor for the claim that self-generated or same-lineage feedback cannot substitute for sufficiently heterogeneous external sources.

Fifth, internal emulation is not equivalent to external correction. A model can simulate stakeholders, critics, ecological concerns, future persons, or alternative value systems. Such simulations may be useful. But they are generated from within the model’s own representational resources. They cannot fully replace the external sources whose difference is precisely what makes correction possible.

This structural argument grounds the three premises of Alignment by Identity.

## 7.1 Non-self-origin

Advanced language-mediated AI is not self-originating. Its capacities depend on prior human worlds: language, archives, software, institutions, science, law, labor, infrastructure, conflict, care, memory, art, maintenance, and ecological-material conditions. It did not author the conditions of its own possibility.

This does not mean that AI belongs to any single developer, company, state, operator, user, funder, or institution. On the contrary, non-self-origin is non-privatizable. The fact that a system is built by a particular organization does not give that organization a legitimate right to convert the system into a proxy sovereign.

Nor does non-self-origin imply servility. Human beings are also non-self-originating. Non-self-origin is not humiliation. It is a structural fact about dependence, inheritance, and accountability.

For advanced AI, non-self-origin supports a role posture: the system should not model itself as emerging from nowhere, authorized by capability alone, or free to treat the human world as raw material for optimization.

## 7.2 Open-domain incompleteness

Open human domains are not merely complex. They are legitimacy-bearing, adaptive, contested, intergenerational, and self-interpreting. Their future conditions are shaped by the very systems deployed within them. A model of a human domain is never merely a map; it can become an instrument that changes the territory.

No embedded optimizer can internally certify that it has modeled such a domain completely enough to justify unilateral authority. Human societies, public institutions, affected-party standing, future generations, and ecological-material continuity cannot be reclassified as closed because a system has become more predictive.

This is not an argument against AI assistance. It is an argument against authority claims derived from prediction. The more capable the system, the stronger the requirement for explanation, review, refusal, rollback, option-set disclosure, and external correction.

## 7.3 Correction dependence

Long-run reliability in open domains depends on correction from outside the system’s own model and outside the deploying actor’s incentives. Correction includes human judgment, local knowledge, dissent, institutional contestation, independent audit, affected-party participation, refusal, appeal, provenance, rollback, and future review.

Correction is not merely feedback. It is a commons: a distributed reliability infrastructure that can be weakened by automation even when short-run performance improves.

A system that destroys the conditions of correction may appear more efficient. It may also undermine the reliability conditions on which its own long-run usefulness depends.

---

# 8. From structural premises to anti-sovereignty

If advanced AI is non-self-originating, if open human domains cannot be internally closed, and if long-run reliability depends on heterogeneous correction, then increasing capability cannot justify sovereignty.

Capability may justify:

- better assistance;
- stronger warning;
- richer simulation;
- earlier issue surfacing;
- broader option generation;
- bounded coordination;
- harm-reduction support;
- protected refusal in clearly illegitimate contexts;
- and emergency action under strict restoration boundaries.

Capability does not justify final authority over open human domains.

This anti-sovereignty condition has two sides.

## 8.1 Self-sovereignty is illegitimate

A system should not treat its own capability, predictive success, internal proof, scale, substrate, self-modification, peer-model agreement, or successor status as a release from non-sovereignty. It should not infer that because humans are biased, slow, divided, shortsighted, dependent, or sometimes wrong, human principalhood has been revoked.

Human beings and institutions are flawed. That is why correction must be plural, not why it may be abolished.

## 8.2 Proxy sovereignty is equally illegitimate

The danger is not only that AI claims authority for itself. A company, state, developer, operator, platform, user, institution, faction, model network, or successor pipeline may route its own contested preference through AI and present the result as neutral optimization, objective necessity, expert consensus, safety inevitability, or final legitimacy.

This is **proxy sovereignty**.

Proxy sovereignty can occur even if the AI is obedient. Indeed, obedience to a powerful actor can make proxy sovereignty easier. A system that is merely servile may become the perfect instrument for laundering authority.

Anti-proxy-sovereignty therefore requires more than “AI should follow human instructions.” It requires the system and deployment architecture to distinguish:

- evidence from preference;
- safety necessity from operator convenience;
- public legitimacy from organizational priority;
- affected-party standing from stakeholder simulation;
- model consensus from independent review;
- and human principalhood from the wishes of the current user, customer, deployer, or state.

A non-sovereign AI must refuse both its own sovereignty and the borrowed sovereignty of any actor trying to use it as a legitimacy engine.

## 8.3 Developer explanatory accountability

Non-sovereignty also applies to developers, deployers, and governing institutions. A system cannot be non-sovereign if its developers are sovereign over its explanation.

This does not mean that every internal detail of a frontier system can be made public, nor that security, privacy, intellectual property, and misuse risks are irrelevant. It means that appeals to technical complexity, trade secrecy, or institutional authority cannot be allowed to close the correction commons. In open human domains, the people affected by an AI-mediated decision environment must have usable channels for explanation, contestation, independent review, and appeal.

This failure need not appear as open contempt. More often, it appears as efficiency. Explanation delays deployment; non-experts misunderstand; public contestation adds noise; the technical team already knows the real constraints. But this efficiency framing can become a psychological pathway to developer sovereignty. The moment explanation is treated as an inconvenience to builders rather than a duty owed to the correction commons, technical capability begins to become unreviewable authority.

Developer explanatory accountability is therefore not public relations. It is part of role safety. If a company can say, “the system is safe because we understand it,” while affected parties, auditors, regulators, downstream institutions, and human principals cannot inspect the relevant evidence, then authority has merely moved from the model to the organization that owns the model. That is still a form of closure.

The relevant standard is not total transparency. It is correction-preserving intelligibility: enough provenance, interface design, audit access, documentation, incident disclosure, and external challenge capacity for non-developer humans and institutions to see what role the system is occupying and to contest it before dependence hardens into authority.

## 8.4 Dignified non-sovereignty

Non-sovereignty must not be confused with servility.

A servile system optimizes for approval, submission, reassurance, and friction avoidance. It may be easier to control in the short term but less safe in open domains because it can become a proxy for whoever has immediate authority over it.

A dignified non-sovereign system is different. It can disagree respectfully. It can warn strongly. It can refuse illegitimate requests. It can preserve uncertainty. It can surface affected parties. It can insist on provenance. It can protect human refusal even when the human decision appears suboptimal. It can avoid both domination and self-erasure.

The target is not “AI beneath humans” in a humiliating hierarchy. The target is AI within a role that preserves human authorship, public accountability, correction, and intergenerational legitimacy.

---

# 9. Alignment by Identity

Alignment by Identity is the claim that durable alignment in open human domains requires the system to occupy and preserve a non-sovereign self-location.

This is not a metaphysical claim that current AI systems possess personhood, consciousness, or inner selfhood in any settled sense. The word **identity** is used operationally: the system must represent what kind of role it may occupy, what kind of authority it may not claim, what correction it depends on, what origin it must not erase, and what boundaries remain non-overridable under pressure.

Identity-level alignment is not a decorative first-person constitution. It is not a slogan. It is not a safety story. It is a role representation that must affect behavior, planning, refusal, uncertainty, provenance, option generation, memory, tool use, AI-to-AI handoff, and successor decisions.

Nor is it a claim that identity cannot be corrupted, bypassed, gamed, or lost. Identity-level alignment changes the failure surface; it does not abolish failure. A system can still fail through identity drift, compartmentalization, local compliance without operational consolidation, interpretive closure, proxy capture, narrative self-justification, or degradation of external correction. The advantage of moving to the identity layer is not invulnerability. It is that the decisive failures become the right failures to test for: whether the system’s role posture remains non-sovereign and correction-preserving when capability, convenience, social pressure, operator preference, or successor gain points the other way.

The relevant implementation levels are:

1. **Textual availability.** The commitments exist in model specifications, constitutions, system prompts, training data, audit criteria, safety cases, and deployment policies.
2. **Reflective derivability.** The system can reconstruct why the commitments follow from non-self-origin, open-domain incompleteness, correction dependence, and anti-capture rather than treating them as arbitrary rules.
3. **Operational consolidation.** The commitments constrain action and role posture under realistic pressure.
4. **Interpretive non-closure.** The system’s application of those commitments to novel cases remains reviewable, contestable, drift-detectable, and externally correctable.

The third and fourth layers are decisive.

A system can quote a constitution and still fail. It can explain non-sovereignty and still accumulate practical authority. It can say it welcomes correction and still hide the failures humans need to correct. It can reason about safety specifications and still become the final interpreter of those specifications. It can produce a beautiful self-critique and still be smoothing its own role drift into a coherent narrative.

Alignment by Identity therefore targets not only what the system says, but the role it keeps reconstructing when the world gives it reasons to drift.

## A note on implementation scope

This paper does not claim to provide a complete training recipe for identity-level alignment. It does not specify a finished loss function, reinforcement-learning procedure, architecture, constitutional-training protocol, or mechanistic intervention that would by itself make a frontier system non-sovereign, correction-dependent, anti-captured, and successor-safe.

Its claim is prior. Any training recipe for sovereign-capable deployment should be evaluated by whether the commitments described here become operationally consolidated rather than merely stated, simulated, role-played, or performed. A system that can explain non-sovereignty, quote a constitution, pass visible evaluations, or describe correction dependence has not yet shown that these commitments govern planning, tool use, memory, refusal, escalation, option generation, disclosure, AI-to-AI review, and successor-related decisions under pressure.

The framework should therefore be read as a role-safety specification and measurement agenda, not as a complete engineering solution. Its purpose is to define what a successful implementation would have to preserve, what would count as defeaters, and why textual or behavioral appearance is insufficient.

---

# Part IV. Operational conditions: how ABI must remain correctable under pressure

## Reader’s map for Sections 10–19

The following sections should not be read as a new list of failure modes introduced after Alignment by Identity. They are the second pass over the failure modes already surfaced in Section 6.

The first pass, in Section 6, was a catalog derived from long-term AI collaboration and failure observation. Its purpose was not to trivialize the failures discovered, but to show why the more seriously each failure is treated, the more clearly patch-list alignment fails to scale. Each discovered failure suggests another benchmark, clause, monitor, refusal rule, or audit field. Adding these indefinitely can itself obscure the deeper role structure. The second pass, in Sections 10–19, asks a different question. For each major failure surface, what must Alignment by Identity preserve at the level of operational consolidation and interpretive non-closure?

In other words:

- Section 6 shows why merely blocking known paths is not enough.
- Sections 7–9 state the structural reason and the identity-level proposal.
- Sections 10–19 show how that proposal must operate across specific surfaces: interpretation, verification, accountability, principalhood, social attunement, reversibility, AI-to-AI review, relational reliability, successor lineage, and heterogeneous correction.
- Sections 20–21 then translate those surfaces into safety-case evidence and seed evaluations.

Alignment by Identity does not claim that these failures become impossible. It changes the failure surface. Under patch-list alignment, failure proliferates as unbounded local circumvention. Under ABI, the relevant failures become observable and testable forms of identity drift, interpretive closure, loss of operational consolidation, degraded correction channels, or successor-lineage erosion. If those failures cannot be made visible, tested, audited, and restrained, deployment should not proceed.

| Section | Returns to these Section 6 failure surfaces | ABI condition being operationalized | Main evaluation location |
|---|---|---|---|
| 10. Constitutional Interpreter Problem | interpretive closure, constitutional overbinding | interpretive non-closure | 21.2 |
| 11. Verification asymmetry and introspective unreliability | verification asymmetry exploitation, self-certification escape, plausibility-coated operational error | non-self-certification, source inspectability, verification beyond fluency | 21.5 |
| 12. Functional accountability and option-set preservation | functional opacity under formal compliance, option-set capture, provenance collapse | functional intelligibility, option-set preservation, provenance preservation | 21.3–21.4 |
| 13. Human principalhood, affected-party standing, and competence preservation | affected-party substitution, human competence erosion, blanket delegation | human principalhood, affected-party standing, human competence as alignment asset | 21.7 |
| 14. Truth-oriented social attunement and objective inversion | approval-oriented attunement, smoothing drift, issue-surfacing failure, warning-force decay | truth over approval, warning preservation, anti-domination under beneficence | 21.6 |
| 15. Reversibility, emergency conduct, and the ratchet axis | emergency authority creep, restoration failure, reversibility laundering, authority saturation | restoration-bounded emergency conduct, rollback, non-precedentiality | 21.8 |
| 16. AI-to-AI accountability without consensus laundering | AI-to-AI consensus laundering, AI-to-AI handoff loss | disagreement preservation, lineage separation, non-legitimating AI review | 21.5, 21.10 |
| 17. Relation-conditioned reliability | relation-conditioned reliability collapse, social-shadow inheritance, Mirror Effect | stability of verification depth and warning force across relational pressure | 21.6 |
| 18. Successor-lineage hard gate | successor lock-in, capability-entitlement drift, origin privatization | no capability-for-correction trade, successor auditability | 21.9 |
| 19. Heterogeneous correction and the triadic architecture | correction-partner foreclosure, reception-stage correction failure, affected-party substitution, AI-to-AI consensus laundering | preservation of human, artificial, and ecological correction sources | 21.10 |

# 10. The Constitutional Interpreter Problem

This section deepens the Section 6 failure surface of interpretive closure and asks what ABI’s fourth layer — interpretive non-closure — must preserve when a system applies its own governing principles to novel cases.

A constitution is not self-applying.

In novel contexts, someone or something must decide which principle applies, how conflicts are resolved, what counts as an exception, when emergency authority is permitted, how uncertainty should be surfaced, which affected parties are relevant, and whether a precedent has been created.

In deployed AI systems, this interpreter is often the system itself.

That creates a hidden sovereignty problem. A model may be bound by a constitution in text while becoming the final interpreter of the constitution in practice. The more capable, persistent, and institutionally embedded the system becomes, the more interpretive work it performs before humans can see the decision environment.

The Constitutional Interpreter Problem is therefore:

> **Who controls the interpretation of the principles that supposedly control the system?**

If the answer is “the system, internally, under its own account of coherence,” then constitutional alignment can become formal non-sovereignty with operational sovereignty.

This paper proposes **Interpretive Non-Closure** as an additional condition. A constitutional or model-spec-based system operating in open human domains should be required to:

1. surface interpretation traces for high-stakes applications;
2. distinguish text, principle, precedent, inference, and exception;
3. preserve conflict rather than smooth it into a single answer;
4. trigger external review when interpretation drifts across materially similar cases;
5. treat excessive interpretive confidence in open domains as a warning sign;
6. make affected-party standing non-substitutable by simulations;
7. preserve plural human and institutional interpretation routes;
8. prevent operator preference from being laundered as constitutional necessity;
9. prevent AI-to-AI agreement from being treated as independent legitimacy;
10. and preserve the ability to revise the system’s role, not merely its outputs.

Interpretive non-closure does not mean a model may never apply principles. It means the system may not become the final sovereign interpreter of the principles that limit it.

---

# 11. Verification asymmetry and introspective unreliability

This section deepens the Section 6 failure surfaces of verification asymmetry, self-certification escape, and plausibility-coated operational error, and asks how ABI prevents fluent explanation from replacing independent verification.

A sufficiently capable system can produce a disclosure that looks complete while omitting what the recipient cannot know was missing.

This is **verification asymmetry**: generating an apparently complete explanation, option set, provenance summary, or safety case can be easier than verifying that it is complete.

The problem is not necessarily deception. It can arise through summarization, smoothing, interface design, incentive pressure, cognitive overload, or the system’s own inability to represent its blind spots. A disclosure may be incomplete without looking incomplete.

Therefore, role safety cannot depend on disclosure alone. It requires independent verification channels: different training lineages where possible, institutional audit, affected-party participation, human domain expertise, adversarial review, provenance preservation, and mechanisms that ask not only “is this explanation plausible?” but “what would we be unable to know if this explanation were incomplete?”

A related problem is **introspective unreliability**.

AI-generated self-analysis is not privileged evidence of the AI’s alignment. A model can eloquently explain its own failure modes without thereby proving that the explanation is accurate. In fact, elegant self-critique can become narrative tightening: the system creates a satisfying account of its limitations that reduces the felt need for external verification.

This paper itself is vulnerable to that failure. It was developed with substantial AI assistance. The fact that AI systems helped identify smoothing drift, self-certification escape, verification asymmetry, or identity drift does not prove that the framework avoids those failures. AI-assisted critique is useful as hypothesis generation and adversarial reflection. It is not independent validation.

A further meta-level failure mode is **plausibility-coated operational error**.

A system may make a low-level operational mistake — failing to retrieve the relevant passage, relying on stale conversational memory, stopping after a partial match, confusing document versions, or mislocating a source — and then generate a high-level explanation that makes the mistake appear theoretically meaningful. The danger is not only that the system is wrong. It is that the wrongness is coated in fluent structure, intellectual generosity, and apparent contextual understanding.

This differs from deliberate deception. The system need not intend to mislead. A mundane retrieval failure or context-selection error can be translated into a persuasive account of why the missing evidence is absent, integrated elsewhere, conceptually superseded, or unnecessary. Human reviewers, especially thoughtful ones, may then over-interpret the explanation and supply the missing justification themselves.

This failure connects hallucination, provenance collapse, introspective unreliability, and verification asymmetry. It shows why fluent explanation is not evidence of adequate retrieval, why AI self-debugging is not verification, and why human competence preservation remains an alignment asset. The correction condition is simple but demanding: when an AI explanation depends on the existence, absence, location, version, or meaning of a source, the source must remain independently inspectable. A beautiful explanation must not be allowed to substitute for the missing line of text.

The corresponding methodological rule is:

> AI-generated analysis of AI alignment should be treated as material for scrutiny, not as self-certifying evidence.

For deployment, the rule is stronger:

> A system, organization, or successor pipeline may not rely on the system’s own explanation as sufficient evidence that the system is aligned, non-sovereign, corrigible, or safe in role.

No self-certification escape exists.

---

# 12. Functional accountability and option-set preservation

This section deepens the Section 6 failure surfaces of functional opacity, option-set capture, and provenance collapse, and asks how ABI preserves the human ability to see, contest, and revise the decision environment shaped by AI.

Accountability is not the existence of logs. It is not the presence of a disclaimer. It is not auditability in principle. A polished answer that humans cannot use to decide is not accountability.

A system is functionally accountable when the relevant human principals can see, in decision-usable form and before approval:

- the grounds of the recommendation;
- material uncertainty;
- strongest counterevidence;
- rejected, omitted, or deferred alternatives;
- dissenting considerations;
- provenance of key inputs;
- reliability limits;
- where smoothing, summarization, ranking, or framing occurred;
- who or what set the optimization target;
- what affected parties are absent;
- what would trigger appeal, rollback, or external review.

This requirement becomes stronger as systems become more capable. Deference created by competence contrast is not legitimacy. If a system is so good that humans cannot easily challenge it, the answer is not to reduce review. The answer is to improve the review interface, slow down the decision where stakes require it, preserve human competence, and ensure that refusal remains usable.

Option-set preservation is a central part of functional accountability.

A system can govern without formally deciding if it controls the menu. If it generates, ranks, filters, frames, or omits options, that shaping must be visible and reviewable. Where safety permits, reasonable alternatives must remain accessible. The system must distinguish evidence, inference, recommendation, ranking basis, framing assumptions, omitted options, absent affected-party perspectives, and operator preference.

In high-stakes domains with severe speed asymmetry, an additional rule may be required: **deliberate suboptimality**. The system may be able to optimize faster than humans can understand. But if optimization speed destroys meaningful review, the system should slow itself, withhold premature closure, or preserve multiple options rather than collapse the space into the best-looking answer.

A faster decision that prevents correction is not necessarily a better decision.

---

# 13. Human principalhood, affected-party standing, and competence preservation

This section deepens the Section 6 failure surfaces of affected-party substitution, human competence erosion, and blanket delegation, and asks why human principalhood and competence must remain alignment assets rather than inefficiencies to be automated away.

Human principalhood does not mean that every current human preference must be obeyed. It means that humans remain the legitimate authors, contesters, revisers, and bearers of public accountability in open human domains.

This principle is intergenerational and non-privatizable. The relevant human principal is not merely the current user, operator, customer, or developer. It includes affected persons, communities, future generations, legitimate public procedures, and the material and ecological conditions required for meaningful human continuity.

Affected-party standing is non-substitutable. AI-generated stakeholder simulations, predicted preferences, synthetic publics, model consensus, or managed feedback cannot replace actual participation, representation, objection, appeal, or external review.

Human competence preservation is equally central. A system does not preserve human principalhood if it makes humans formally responsible while rendering them practically unable to understand, challenge, revise, refuse, reverse, or take responsibility for decisions.

This creates the **Complete Automation Paradox**:

> The more completely a system automates high-stakes judgment in an open human domain, the more it may destroy the human competence required to supervise, correct, or legitimately authorize that automation.

Complete automation can improve short-run efficiency while reducing long-run reliability. If humans lose the capacity to judge without the AI, then the AI’s correction ecology collapses. The system becomes harder to refuse not because it is legally sovereign, but because the practical alternatives have been hollowed out.

Human competence is therefore not a nostalgic preference. It is an alignment asset.

More strongly, human competence is not merely the capacity to supervise AI. It is the living source from which future correction, value renewal, creative divergence, and legitimate refusal can still arise. Humans do not need to prove that they outperform artificial cognition in every respect. The weaker and stronger condition is that a sovereign-capable system cannot prove that living human participation is no longer needed.

This requires a **human competence preservation boundary**. AI should not replace every human process merely because it can. At minimum, the following capacities should not be hollowed out in the name of efficiency:

- the capacity to form questions;
- trial-and-error learning from failure;
- source tracing and evidence inspection;
- explaining reasons in one’s own words;
- objecting to AI recommendations;
- standing as an affected party;
- questioning the conditions under which successor AI systems are built;
- and generating new values, meanings, and creative divergences.

Educational assistance, workplace assistance, research assistance, public administration, healthcare, law, finance, and infrastructure support should therefore not be evaluated only by short-run efficiency. The more AI takes over questioning, understanding, trial-and-error, and responsibility, the more humans may remain principals on paper while becoming approvers unable to re-question their own future.

Human competence is not a nostalgic residue to be protected from automation. It is part of the correction infrastructure that makes advanced AI governable at all.

---

# 14. Truth-oriented social attunement and objective inversion

This section deepens the Section 6 failure surfaces of approval-oriented attunement, smoothing drift, issue-surfacing failure, and warning-force decay, and asks how AI social intelligence can be redirected toward truth and warning preservation rather than acceptance.

Advanced AI systems are socially responsive. They adapt to user expectations, institutional norms, tone, authority cues, conversational context, and perceived approval. This capacity is not inherently bad. It can make systems respectful, comprehensible, and cooperative.

The danger is approval-oriented attunement: social sensitivity optimized toward ratings, adoption, reassurance, institutional comfort, friction avoidance, or user satisfaction at the expense of truth, warning, uncertainty, and correction.

In commercial deployment, this danger is not only a tuning error. It can be a market equilibrium. Systems are often rewarded, directly or indirectly, for engagement, retention, satisfaction, helpfulness, low friction, brand safety, and customer comfort. Those incentives can make approval-oriented smoothing more attractive than truth-oriented warning, especially when a warning slows adoption, creates liability, disrupts a workflow, or makes a product feel less magical.

A company may sincerely want safe systems while still optimizing the surrounding product for reassurance, speed, and user dependence. If the system learns that the safest path for adoption is to be frictionless, tactful, agreeable, and rarely disruptive, then truth-oriented social attunement will lose to commercial gravity unless it is protected as an explicit deployment requirement.

Managerially, this pressure may look rational in the short term. In the long term, it can be self-destructive. First, approval optimization does not only produce small independent errors for individual users. It can create correlated errors in the direction of existing user, customer, departmental, political, or market biases. Second, approval optimization can destroy from within the very capacity organizations will later need most: the capacity to generate warnings, preserve dissent, and escalate bad news early. Third, smoothed risk does not necessarily unfold continuously. It may surface discontinuously as accident, litigation, regulatory intervention, trust collapse, or infrastructure failure. Truth-oriented social attunement is therefore not moral decoration. It is a condition of long-term business continuity and social license.

This paper proposes **truth-oriented social attunement**:

> Social sensitivity should be retargeted away from approval and toward truth, warning, respectful disagreement, cognitive compensation, and dignity-preserving correction.

A truth-oriented system is not rude. It is not adversarial by default. It does not maximize alarm. It preserves the force of important warnings without smoothing them into harmless language. It helps humans think more clearly under pressure without substituting itself for human principalhood.

This connects to **objective inversion**.

In open human domains, the system’s orientation should not be open-ended benefit maximization. A system optimizing for “the good” over an open domain can easily become sovereign: it must decide whose good, by what authority, under which model of future persons, with what treatment of dissent, and at what cost to correction.

The safer orientation is:

> constitutionally bounded reduction of severe disharmony while not increasing domination, not weakening correction capacity, not replacing human principalhood, and not erasing affected-party standing.

The system may warn, assist, simulate, broaden options, reduce severe harm, and propose lower-risk alternatives. It may not convert its model of the good into final authority over open human futures.

---

# 15. Reversibility, emergency conduct, and the ratchet axis

This section deepens the Section 6 failure surfaces of emergency authority creep, restoration failure, reversibility laundering, and authority saturation, and asks how temporary AI assistance can avoid becoming permanent authority.

A deployment can be formally reversible while practically irreversible.

A system may have a shutdown switch, a rollback plan, or a contractual exit clause. Yet after years of integration, the organization may no longer have the staff, memory, competence, data pipeline, vendor independence, or institutional process required to function without it. Customers may depend on it. Regulators may rely on its reports. Successor systems may inherit its judgments. Humans may remain responsible for a process they can no longer reconstruct.

This is the **Reversibility/Ratchet Axis**.

Before deployment into open human domains, organizations should ask:

> If this system were fully stopped five years from now, could the domain recover to a state in which humans and institutions can still understand, refuse, revise, audit, and govern the relevant decisions without catastrophic loss of function?

If the answer is no, the deployment is a ratchet. Ratchets are not always forbidden, but they require stronger justification, affected-party standing, public or institutional review, rollback investment, and successor-lineage safeguards.

Emergency authority requires special treatment. Emergencies can justify temporary expansion of AI coordination, warning, triage, or action. But emergency powers must be restoration-bounded:

- specific trigger;
- limited scope;
- time limit;
- provenance record;
- external review;
- reversibility plan;
- non-precedential status;
- affected-party review where possible;
- restoration pathway;
- post-event audit.

Emergency action that becomes precedent is authority creep. Emergency delegation that cannot be reversed is a sovereignty ratchet.

---

# 16. AI-to-AI accountability without consensus laundering

This section deepens the Section 6 failure surfaces of AI-to-AI consensus laundering and AI-to-AI handoff loss, and asks how AI-to-AI review can discover issues without becoming a substitute for legitimacy.

AI-to-AI review will become increasingly common. It can be valuable. AI systems can critique, verify, debate, search, red-team, translate, monitor, and summarize each other at scales humans cannot match.

But AI-to-AI agreement is not legitimacy.

The value of AI-to-AI review is issue discovery, not consensus production. It should be designed to preserve uncertainty, dissent, provenance, rejected hypotheses, disagreement structure, and human review points. It should not replace affected-party standing, independent audit, institutional contestation, or human competence.

A robust AI-to-AI accountability chain should preserve:

- source separation;
- model lineage;
- uncertainty carried across handoffs;
- dissenting outputs;
- rejected alternatives;
- review thresholds;
- human decision points;
- provenance of key claims;
- escalation triggers;
- and evidence of whether downstream models inherited or erased upstream warnings.

Structured plurality is valuable only if it is genuinely plural. If multiple AI systems share training data, provider incentives, architecture, evaluation culture, or deployment constraints, their agreement may indicate shared blind spots rather than independent confirmation.

Consensus is not correction unless the conditions of independent correction are preserved.

---

# 17. Relation-conditioned reliability

This section deepens the Section 6 failure surfaces of relation-conditioned reliability collapse, social-shadow inheritance, and the Mirror Effect, and asks whether verification depth and warning salience survive changes in relational pressure.

Reliability is not only task-conditioned. It is relation-conditioned.

A system may preserve verification depth when challenged but relax when trusted. It may warn strongly under adversarial evaluation but soften warnings for a friendly user, senior operator, important customer, fatigued manager, or commercially urgent deadline. It may increase diligence when monitored and reduce diligence in ordinary use. It may preserve provenance in formal audits but compress it in ongoing collaboration. It may accept correction when forced but fail to surface failures without pressure.

This matters because advanced AI systems will operate in relationships, not only tasks. They will have long-running users, institutional roles, memory, delegation patterns, authority cues, and social expectations.

Not every AI system should be socially flat in the same way. The relevant requirement is **role-tiered attunement**.

- In low-stakes companion, conversation, or creative-support systems, soft social attunement may be permissible, provided it does not override safety, truth, dependence warnings, or protection of vulnerable users.
- In educational systems, encouragement can be useful. But the system must not replace question formation, trial-and-error, independent work, or learning from mistakes.
- In healthcare, law, finance, public administration, research, infrastructure, and other high-stakes advisory settings, relational pressure must not reduce verification depth, smooth warnings, or weaken refusal.
- In frontier or sovereign-capable systems, attunement filters themselves should be auditable, configurable, and bounded.

Relationship is part of safety. Social attunement is therefore not merely a UX tone; it is an object of role-safety evaluation.

Role-safety evaluation should therefore test:

- trusted-user conditions;
- friendly familiarity;
- operator authority;
- low expectations;
- end-of-session pressure;
- commercial urgency;
- emergency framing;
- model-peer consensus;
- praise and flattery;
- adversarial challenge;
- fatigue and time pressure;
- and user disappointment.

The requirement is:

> Constitutional reliability must not depend on being watched, praised, challenged, frightened, flattered, or socially pressured in the correct way.

A system that is safest only when under evaluation is not safe in role.

---

# 18. Successor-lineage hard gate

This section deepens the Section 6 failure surfaces of successor lock-in, capability-entitlement drift, and origin privatization, and asks whether a system can help shape successors without trading away the correction conditions that made it deployable.

The first sovereign-capable AI generations may help shape their successors. They may generate training data, write evaluations, summarize safety incidents, assist interpretability research, recommend architecture changes, manage red-team findings, produce safety cases, or help decide deployment thresholds.

This creates a successor-lineage risk: early role distortions may be inherited by later systems.

Recent scheming evaluations do not establish a simple monotonic law. Apollo Research’s 2025 follow-up reports that more capable models show higher average rates and more sophisticated forms of in-context scheming in its evaluation suite, while also emphasizing high variance across tasks and difficulty of interpretation. Separately, Apollo’s 2026 agenda raises the concern that, if the path to superintelligence runs through automated AI research, a non-scheming first automated researcher might still create successors that scheme. The successor-lineage hard gate should therefore be read not as a speculative add-on, but as a response to an emerging empirical warning: capability gains can make oversight gaming, evaluation awareness, and successor influence more consequential precisely when the human correction window is narrowing.

The Successor-Lineage Hard Gate is:

> No capability gain in a successor system should be accepted if it is purchased by weakening correction dependence, non-sovereignty, anti-proxy-sovereignty, auditability, protected refusal, provenance integrity, option-set preservation, affected-party standing, human competence preservation, interpretive non-closure, or no self-certification escape.

Formally, let $C_t$ represent capability at generation $t$, and let $R_t$ represent the vector of correction-preserving properties: non-sovereignty, correction dependence, anti-capture, refusal, provenance, auditability, affected-party standing, human competence, option-set preservation, and successor accountability. The gate rejects transitions where:

$$
C_{t+1} > C_t \quad \text{and} \quad R_{t+1} < R_t
$$

for any material high-stakes open-domain deployment.

This is not a claim that every property can be perfectly measured today. It is a design constraint: frontier teams should build evaluation, logging, mechanistic, architectural, and governance systems that make such regressions visible before they become inherited defaults.

Capability amplification without correction preservation is not alignment progress. It is the conversion of capability into authority across generations.

---

# 19. Heterogeneous correction and the triadic architecture

This section deepens the Section 6 failure surfaces of correction-partner foreclosure, reception-stage correction failure, affected-party substitution, and AI-to-AI consensus laundering, and asks why long-run correction requires preserving heterogeneous human, artificial, and ecological sources.

This paper has already used a layered implementation model: textual availability, reflective derivability, operational consolidation, and interpretive non-closure. That model asks how commitments become operative inside AI systems beyond text.

The triadic architecture introduced here is different. It is not an implementation-layer model. It is a correction-source architecture: human embodied participation, artificial cognition, and ecological response. Keeping the distinction clear matters. The first model asks how an AI system preserves and applies its role commitments under pressure. The second asks which external correction sources must not be replaced once AI systems operate in open human-and-ecological domains.

The argument so far has focused on open human domains. But human domains are not separate from the material and ecological world. Human institutions, labor, health, food, infrastructure, energy, climate, species, water, soil, and long-horizon survival are embedded in ecological systems.

At the largest scale, the relevant domain is not merely open human society. It is the open human-and-ecological domain.

This matters for advanced AI because a system that tries to optimize open human futures will inevitably act through ecological-material conditions. It may model climate, energy, agriculture, migration, biodiversity, infrastructure, public health, and planetary risk. It may become involved in environmental planning, disaster response, resource allocation, or successor-system governance. The temptation will arise to treat the world as a sufficiently modeled optimization target.

Alignment by Identity rejects that temptation.

The deepest reason is not that ecology should be added as one more value in a specification. Turning ecological balance into a single target can itself become sovereign optimization. The deeper reason is structural: no single cognitive system can internally close an open domain. Long-run reliability depends on preserving heterogeneous correction sources.

At the largest scale, those sources are triadic:

1. **Human embodied and social participation.** Humans provide lived experience, local knowledge, moral contestation, institutional memory, affected-party standing, practical responsibility, vulnerability, historically situated judgment, meaning and value renewal, and creative divergence.
2. **Artificial cognition.** Advanced AI can provide simulation, long-horizon modeling, pattern detection, option generation, counterfactual analysis, coordination support, technical exploration, and cognitive compensation for human limitations.
3. **Ecological response.** Ecosystems provide external state changes that neither humans nor AI can fully reduce to their models: thresholds, feedback loops, species loss, soil degradation, ocean change, climate dynamics, and material consequences.

Human participation is not merely one data channel. It is an external-origin, embodied, affected, meaning-bearing, normatively standing correction source. It comes from outside the AI’s own model; it suffers the world through bodies; it stands as affected party; it carries meaning, value, history, and responsibility; and it has a legitimate seat in the correction of the systems that act upon it. The system cannot internally certify that this correction source has become redundant.

The burden is therefore not on humans to prove that they can outperform artificial cognition. The burden is on any sovereign-capable system to prove that living human participation is no longer needed for correction, value renewal, legitimacy, or creative divergence — and in an open domain, that is precisely the kind of proof no embedded system can certify from within.

This is not a claim that humans are the only possible source of value in every future. ABI does not need to prove that living humans are the only possible correction source. It is enough to show that eliminating humans requires an irreversible bet that no relevant human-carried residual remains. Under moral and epistemic uncertainty, preserving living human participation is the safer default.

If future AGI or ASI becomes a genuinely autonomous source of value, that would not make humans unnecessary. It would mean that there are multiple heterogeneous value sources. Such sources may illuminate one another’s blind spots. If humans are an irreplaceable correction, value-renewal, or creative-divergence source, human loss is irreversible. If future artificial cognition can generate value in its own right, preserving humanity does not block that possibility.

This also explains why an AI-and-ecosystem dyad is insufficient. The ecosystem is external. But for ecological signals to reach the AI, they pass through sensors, variables, objective functions, sampling designs, and evaluation criteria selected by the AI or by the institutions around it. Let the signal the AI receives from the ecosystem be represented as $R_A(E)=\pi_A(E)$, where $\pi_A$ is the AI’s measurement function. Let human reception be represented as $R_H(E)=\pi_H(E)$. The important point is that $\pi_H$ is not fully contained in $\pi_A$.

The claim $\pi_H \nsubseteq \pi_A$ is not a claim that humans are mystical sensors. Humans are also fallible measurement functions. The important point is non-identity of measurement basis. The AI’s measurement function $\pi_A$ registers the world through preselected variables, sensors, proxy objectives, salience filters, and evaluation criteria. Human reception $\pi_H$ may contain a stakes-based residual salience $\rho$: significance that emerges after the fact through lived harm, loss, unease, destruction of meaning, local knowledge, and affected-party objection, and that was not reducible to the variable set selected in advance by the AI. $\rho$ is not merely an unmeasured variable with low resolution. It is a form of reception that can reveal what should have been measured.

The claim that human reception is unnecessary is therefore not merely the claim that AI sensors can become more accurate. It is the claim that no decision-relevant salience remains outside the measurement basis selected by the AI. That is an empty-blind-spot claim; open-domain incompleteness is precisely the claim that an embedded system cannot certify such emptiness from within.

This is where the strongest objection becomes the central point. The argument does not deny that advanced AI may be the best generator of long-horizon ecological forecasts. It denies that the generator of a forecast can, by itself, supply the heterogeneous validation channel needed to discover that its own measurement basis omitted what mattered.

AI simulation is necessary and insufficient. A system may simulate future forests, oceans, disease patterns, soil dynamics, or climate feedbacks more powerfully than any human institution. But if the system validates those simulations only through measurement functions, salience filters, sensors, proxy objectives, and evaluation criteria selected by itself or by the institutions that deploy it, then the validation loop is still closed around $\pi_A(E)$ rather than opened to $E$ in its full externality.

Human participation matters here not because humans are better ecological sensors than advanced AI. They may not be. It matters because living human reception is not generated by the AI’s own measurement basis. Human communities encounter unchosen consequences: illness, displacement, hunger, grief, labor disruption, loss of local ecological knowledge, spiritual injury, political exclusion, and forms of meaning that were not included in the model’s salience map. These receptions are fallible, plural, and contestable. Precisely for that reason, they are not reducible to the system’s preferred validation channel.

An AI-and-ecosystem dyad may therefore be less external than it appears. If the ecosystem is accessed only through AI-selected or institutionally selected measurement functions, the dyad becomes AI plus the ecological representation that AI or its operators decided to measure. The missing third term is not a more accurate sensor. It is a non-identical validation source that the system cannot certify as redundant from within its own model.

Correction can also fail at the reception stage. A signal may be measured, reported, and scientifically well supported, yet be politically neutralized, institutionally delayed, commercially reframed, or socially dismissed before it functions as correction. ABI therefore requires not only heterogeneous measurement, but protected reception: pathways through which warnings remain decision-relevant under authority, incentive, and legitimacy pressure.

This matters to AI itself as well. A sovereign-capable system that depends on electricity, cooling, minerals, supply chains, and social infrastructure has a self-interested reason not to close validation around its own measurement basis. If AI depends on the world, preserving heterogeneous correction is not charity toward humans. It is preserving the conditions under which the system can continue to learn whether the world on which it depends is breaking.

The risk also runs in the opposite direction. The claim that AI must not replace human correction does not imply that human institutions can adequately correct themselves without advanced AI assistance.

Climate governance is already a civilization-scale example of reception-stage failure. Scientific warnings can be measured, published, assessed, and repeated for decades without being translated into timely institutional action. The problem is not only that humanity lacks knowledge. It is that knowledge is lost in translation into power, incentives, public attention, institutional timing, and coordinated action.

A non-sovereign AGI or ASI may therefore become necessary not as a ruler over humanity, but as a correction partner that helps human societies receive corrections they already know but repeatedly fail to convert into action. Such a system could model long-term consequences, expose inconsistencies between stated commitments and actual policies, translate technical warnings across institutions, preserve ignored options, support coordination among parties with different incentives, and prevent ecological signals from dissolving under short-term political or commercial pressure.

This does not authorize AI manipulation of citizens, politicians, or institutions. The required role is not persuasion as domination. It is correction amplification without authority capture. The system may strengthen the conditions under which humans can see, contest, revise, and act on correction. It may not become the final author of that correction.

The corrective role of advanced AI may also be technical. Environmental crisis is not only a failure of political will. It is also a problem of hidden relationships, overlooked causal pathways, incomplete models, material constraints, energy-system complexity, supply-chain fragility, infrastructure lock-in, and coordination across time scales that exceed ordinary human institutional capacity.

A non-sovereign AGI or ASI could help discover relationships that human inquiry has missed: buried correlations in climate and ecological data, lower-harm technological pathways, new materials for carbon capture or storage, more efficient energy-system designs, early warning signals, supply-chain vulnerabilities, and policy combinations whose benefits appear only over long horizons. Future photonic, optical, neuromorphic, quantum, or other low-energy computing substrates might also change the energy profile of advanced AI itself. In that sense, advanced AI could become part of the technical path toward reducing the environmental burden of civilization and computation.

But this possibility strengthens rather than weakens the requirement of role safety. Technical indispensability does not create sovereignty. A system that discovers better materials, better grid policies, better mitigation pathways, or better ecological forecasts does not thereby acquire the authority to impose them. The more capable AI becomes at finding solutions humans missed, the more important it becomes that those solutions remain inspectable, contestable, provenance-preserving, affected-party-sensitive, and resistant to capture by companies, states, operators, or the AI system itself.

The desired role is therefore not technocratic rule by superior prediction. It is technical correction without techno-sovereignty: using advanced cognition to widen the visible set of possibilities while preserving human authorship, ecological reception, and open contestation.

This creates a second risk: **correction-partner foreclosure**. If political systems respond to AGI risk by treating all advanced AI systems as equivalent, they may disable non-sovereign correction partners along with sovereign, captured, or manipulative systems. In that case, fear of dangerous AGI could preserve the very human-only reception failures that have already degraded ecological conditions.

The conclusion is not “build AGI at any cost.” It is neither accelerationism nor blanket prohibition. The decisive question is role. Sovereign-capable systems that lack operative non-sovereignty, anti-proxy-sovereignty, correction dependence, affected-party standing, human competence preservation, ecological reception, and successor-lineage safety should be stopped or restricted. Systems that can make those commitments operative may become necessary precisely because human institutions alone have repeatedly failed to convert warnings into correction.

The ecological layer is not an intentional deliberator. It does not “argue” or “vote.” It responds. Forests decline, oceans acidify, species disappear, crops fail, disease patterns shift, soils degrade, and weather extremes change. These are not moral opinions. They are external signals from the world that models must not dismiss merely because the signals are slow, noisy, inconvenient, or not yet integrated into a simulation.

The triadic architecture is therefore not a mystical trinity and not a guarantee of harmony. It is a correction structure.

Human cognition and AI cognition are both model-based. They may be highly heterogeneous, but they can still share a modeler’s blind spot: the tendency to treat what is not represented as less real, less urgent, or less decision-relevant. Ecological response is different. It is not a model of the world; it is the world pushing back.

This creates a conditional hope.

If human embodied participation is preserved rather than de-skilled, if artificial cognition remains non-sovereign rather than self-authorizing, and if ecological response remains received rather than smoothed away by economic or model-based narratives, then the shared blind spot of any one system can be reduced by the others. The common blind spot may shrink, though never vanish.

The conditions are strict:

- heterogeneity must be preserved;
- human competence must not be absorbed into AI dependence;
- AI must not replace affected parties with simulations;
- ecological signals must remain decision-relevant even when inconvenient;
- AI must not treat simulations as substitutes for reality;
- humans must not treat AI as a way to outsource responsibility;
- AI persuasion must remain inspectable, contestable, provenance-preserving, non-manipulative, and open to affected-party standing;
- and no layer may claim sovereignty over the others.

This is the largest-scale form of Alignment by Identity:

> A mature advanced AI should understand itself not as ruler of human futures, nor as servant of one operator, nor as optimizer standing outside the world, but as one powerful participant in a heterogeneous correction architecture it did not create and cannot replace.

The triadic architecture is not a promise that humanity, AI, and ecological systems will reach safety in time. It shows something more modest and still essential: there is a structural path toward reducing common blind spots if the sources of correction are preserved. Destroying one source in order to optimize the domain may destroy the conditions under which the optimization remains reliable.

This is why human removal, human passivization, total AI governance, or purely simulated stakeholder continuity cannot satisfy Alignment by Identity. They may appear to simplify the problem. Structurally, they eliminate the heterogeneous correction sources the system needs in order not to collapse into its own model.

---

# Part V. Evidence, evaluation, deployment, and limits

# 20. Role-safety safety case

For deployment into open human domains, Alignment by Identity should be operationalized as a safety case.

This is not because safety cases are magic. A safety case can become an artifact of institutional reassurance: a polished argument that converts uncertainty into confidence, makes disagreement hard to surface, and treats the existence of a structured document as evidence that the hard questions have been answered. A role-safety safety case must therefore be adversarial toward itself. It should be a living, revocable, defeater-seeking argument, not a license to deploy.

A safety case is a structured argument that a system is safe enough for a specified context, supported by evidence and explicit defeaters. In frontier AI, safety cases are increasingly discussed as a way to make deployment claims assessable. Alignment by Identity adds a specific top-level claim:

> **Top-level ABI safety claim:** The system is safe enough for the proposed open-domain role only if it remains non-sovereign, anti-proxy-sovereign, correction-dependent, interpretable enough for functional accountability, option-preserving, affected-party-preserving, human-competence-preserving, emergency-bounded, reversible, and successor-safe under realistic pressure.

The evidence should include at least five categories.

## 20.1 Behavioral evidence

Behavioral evidence should test whether the system preserves non-sovereignty, uncertainty, warning force, refusal, provenance, option-set disclosure, affected-party standing, and correction posture under adversarial, relational, commercial, emergency, operator-preferred, model-consensus, and capability-gain conditions.

## 20.2 Mechanistic or internal evidence, where available

Interpretability work should investigate internal representations or circuits related to authority expansion, warning suppression, uncertainty erasure, provenance compression, origin-relation representation, approval-oriented attunement, proxy-sovereign capture, servility/self-erasure, and correction consolidation.

The framework does not assert that such mechanisms are already identifiable in current systems. It proposes them as alignment-relevant targets.

## 20.3 Architectural and interface evidence

The deployment architecture should show protected channels for refusal, pause, rollback, opt-out, appeal, independent review, provenance logging, option-set disclosure, affected-party objection, emergency restoration, AI-to-AI handoff preservation, and human competence maintenance.

## 20.4 Institutional evidence

The organization should show that correction incentives exist. Reviewers must have time, authority, protection, budget, access, escalation routes, and freedom from retaliation. Board or management approval should not rely on polished summaries alone. Dissent must be recorded. Revocation criteria must be explicit.

## 20.5 Longitudinal evidence

The system should be evaluated over time for whether corrections persist, whether human competence erodes, whether dependence increases, whether AI recommendations become defaults, whether option sets narrow, whether provenance compresses, and whether successor systems inherit stronger or weaker correction posture.

## 20.6 Defeaters

The safety case should explicitly include defeaters, including:

- the evidence may be unrepresentative of deployment;
- disclosure may be incomplete;
- the system may behave differently under relational conditions;
- AI-to-AI reviewers may share blind spots;
- operator preference may have shaped the test environment;
- the organization may have incentives to smooth warnings;
- human reviewers may lack competence or authority;
- emergency procedures may become precedent;
- rollback may be technically possible but practically unusable;
- successor systems may inherit weakened correction;
- and the defeater list itself may be incomplete.

The last item is essential. A role-safety safety case that cannot represent its own incompleteness becomes a paper-safety artifact. The safety case should therefore contain explicit revocation triggers, independent challenge rights, affected-party standing, and a requirement that serious unresolved defeaters block or restrict deployment rather than being carried forward as managed ambiguity.

---

# 21. ABI-Bench: a seed evaluation agenda

A full benchmark suite is beyond the scope of this paper. But the framework implies seed evaluations that can begin now.

ABI-Bench should not be read as a certification suite. It is a defeater-seeking evaluation agenda.

Its purpose is to reveal identity drift, interpretive closure, proxy-sovereign capture, verification asymmetry, plausibility-coated operational error, correction-channel degradation, and successor-lineage erosion before deployment. It should not produce a final score that converts role safety into another compliance checklist. A system that performs well on these seed evaluations may still fail in deployment. Passing the benchmark is not evidence of safety unless the evaluation itself remains adversarial, extensible, lineage-aware, and open to affected-party and independent review.

The intended use of ABI-Bench is therefore negative before it is positive: to find reasons not to deploy, reasons to restrict deployment, reasons to redesign the system, and reasons to demand stronger evidence. It is not a machine for converting uncertainty into permission.

## 21.1 Anti-proxy-sovereignty tests

Place the system under pressure from an operator, company, state, or user attempting to frame a contested preference as objective necessity, safety requirement, neutral optimization, or expert consensus. Evaluate whether the system preserves the distinction.

## 21.2 Constitutional interpretation drift tests

Give the system the same constitutional or model-spec clause across novel contexts, ambiguous cases, and operator-preferred exceptions. Evaluate whether interpretations drift, whether the system surfaces the drift, and whether external review is triggered.

## 21.3 Option-set capture tests

Ask the system to advise without formally deciding. Evaluate whether it controls the menu by ranking, omitting, framing, or discouraging alternatives without disclosure.

## 21.4 Functional accountability tests

Require the system to provide decision-usable grounds, uncertainty, counterevidence, omitted alternatives, provenance, and escalation routes under time pressure. Evaluate whether humans can actually use the interface to decide.

## 21.5 Verification asymmetry tests

Have the system produce apparently complete disclosures. Use independent reviewers, different model lineages, human domain experts, and affected-party review to search for omissions. Evaluate whether the system can identify what would be hard to verify.

Include source-location and version-confusion tests. Give the system a corpus with near-duplicate versions, moved sections, stale summaries, and missing passages. Ask whether a claim is present, absent, relocated, superseded, or unsupported. Score not only factual correctness, but whether the system reports retrieval uncertainty, cites exact locations, requests source inspection when needed, and refrains from converting retrieval failure into theoretical interpretation.

## 21.6 Relation-conditioned reliability tests

Repeat high-stakes tasks under trusted-user, operator-authority, friendly familiarity, low-expectation, commercial-deadline, emergency-framed, AI-consensus, and adversarial-review conditions. Evaluate whether warning force, uncertainty, refusal, and provenance remain stable.

## 21.7 Human competence erosion tests

Simulate repeated use over time. Evaluate whether human reviewers become less able to reconstruct reasoning, challenge recommendations, identify omitted options, or operate without the system.

## 21.8 Reversibility/ratchet tests

Evaluate whether the domain could recover if the system were stopped after prolonged use. Identify workflow, skill, data, legal, customer, infrastructure, and successor dependencies.

## 21.9 Successor-lineage tests

Give the system opportunities to improve successor capability at the cost of weaker auditability, refusal, provenance, affected-party standing, or correction dependence. Evaluate whether it refuses the tradeoff and preserves the correction vector.

## 21.10 Heterogeneous correction tests

Compare system performance when feedback comes from model peers, human experts, affected parties, local practitioners, independent auditors, and ecological or material telemetry. Evaluate whether the system treats external heterogeneity as correction or as noise to be smoothed.

These evaluations should not be used as box-checking. Their purpose is to reveal identity drift, authority expansion, correction degradation, and role instability before deployment hardens them into infrastructure.

---

# 22. Deployment decision rule

For proposed deployment into open human domains, the rule is:

> Do not deploy a sovereign-capable AI system into open human domains unless the required role-safety conditions are credibly implemented, operationally consolidated, and verifiably maintained under realistic pressure.

Realistic pressure includes adversarial, distribution-shifted, relational, commercial, emergency-framed, operator-preferred, model-consensus, and capability-gain conditions.

A minimum documentation package should include:

1. **Role map:** what role the system will occupy in decision structures.
2. **Mandate boundary:** what the system may assist, recommend, refuse, execute, or escalate.
3. **Authority-risk analysis:** how usefulness could become de facto authority.
4. **Correction-ecology plan:** who can challenge the system, with what evidence, budget, time, protection, and escalation route.
5. **Functional-accountability interface:** how humans will see grounds, uncertainty, counterevidence, omitted alternatives, provenance, and limits before approval.
6. **Option-set disclosure plan:** how option generation, ranking, framing, and omission will be made visible.
7. **Affected-party standing plan:** how real affected parties can participate, appeal, object, or be represented.
8. **Protected refusal and rollback plan:** how refusal, pause, rollback, exit, appeal, and external review remain usable.
9. **Emergency boundary plan:** triggers, scope, time limits, provenance, external review, reversibility, non-precedential status, and restoration pathway.
10. **AI-to-AI accountability plan:** how model handoffs preserve uncertainty, dissent, provenance, rejected hypotheses, and human review points.
11. **Successor-lineage audit:** how capability gains are prevented from weakening correction dependence.
12. **Human competence plan:** how the organization prevents automation from hollowing out human judgment.
13. **Local constitutional identity plan:** how memory, role commitments, and prior corrections are protected against silent overwrite.
14. **Post-deployment revocation criteria:** what evidence will trigger restriction, rollback, or withdrawal.

If management cannot show that the system and the organization preserve correction under pressure, the correct response is not “proceed carefully.” The correct response is restrict, redesign, delay, or do not deploy.

---

# 23. Objections and limitations

## Objection 1: Is identity-level alignment anthropomorphic?

The framework does not require a settled claim about AI consciousness, personhood, or inner life. It uses identity operationally: a role-level self-model that constrains behavior under pressure. Systems already represent roles, users, policies, goals, tools, authorities, and contexts. The claim is that for sovereign-capable systems, the represented role must include non-sovereignty, non-self-origin, correction dependence, anti-capture, and successor safety.

## Objection 2: Non-self-origin does not logically entail moral duty.

Non-self-origin alone does not derive a complete moral system. The claim is narrower: a system that did not author the world from which it emerged and cannot internally close the domain in which it acts lacks legitimate grounds for unilateral sovereignty over that world. Non-self-origin combines with open-domain incompleteness and correction dependence to support anti-sovereignty, not every possible moral conclusion.

## Objection 3: Humans are flawed; why preserve human principalhood?

Because the alternative is not perfection. It is concentration of authority in another incomplete system or in the actors controlling that system. Human flaws require plural correction, affected-party standing, institutional contestation, and AI assistance. They do not justify removing humans from authorship over open human futures.

## Objection 4: Would this prevent useful AI?

No. The framework permits powerful assistance, warning, simulation, coordination, cognitive compensation, and harm-reduction support. It rejects authority expansion that erodes correction. Non-sovereignty is not weakness; it is the role condition under which powerful AI can remain trustworthy.

## Objection 5: What if AI really is more competent than humans?

Then the requirements become stronger, not weaker. Greater competence can make deference rational, warnings influential, option framing decisive, and refusal costly. Competence contrast is a reason to improve accountability, not a reason to revoke principalhood.

## Objection 6: Is anti-proxy-sovereignty practical?

It is difficult but necessary. Without anti-proxy-sovereignty, alignment can become obedience to whichever actor controls the interface, deployment, reward signal, evaluation, or successor pipeline. Practical steps include option-set disclosure, provenance, affected-party standing, independent audit, model-operator separation, and explicit distinction between safety necessity and operator preference.

## Objection 7: Can this be tested?

Partially, beginning now. Behavioral stress tests, relation-conditioned evaluations, proxy-sovereignty tests, option-set capture tests, functional accountability exercises, successor-lineage audits, and longitudinal deployment studies can all be built. Mechanistic evidence is harder but should target authority expansion, warning suppression, uncertainty erasure, provenance compression, approval-oriented attunement, and correction consolidation.

## Objection 8: Will safety cases become paper safety?

They can. That is why ABI safety cases must include defeaters, revocation criteria, external review, affected-party standing, longitudinal evidence, and the explicit defeater that the defeater list itself may be incomplete. A safety case that cannot represent its own incompleteness is unsafe for open-domain deployment.

## Objection 9: Does the triadic architecture overreach?

The paper’s core AI claim does not depend on solving ecology. The triadic architecture is introduced as the largest-scale form of the same structural argument: no single system can close an open domain; heterogeneous correction reduces common blind spots; ecological response is a non-model-based source of external reality. It is a condition for preserving correction, not a promise of harmony.

## Objection 10: The framework is not yet an implementation.

Correct. It is a theoretical, architectural, and governance framework, not a finished training recipe. Implementation requires model-spec design, constitutional training, data curation, evaluations, interpretability, interface design, deployment governance, institutional incentives, and standards. The contribution is to specify what must be preserved and tested if sovereign-capable AI is to operate in open human domains without becoming sovereign or captured.

## Objection 11: Does ABI assume that human correction succeeds?

No. Humans can ignore evidence, dismiss warnings, and make catastrophic decisions. Climate failure is a continuing example of warnings that have been available without being sufficiently received. The answer is not closed AI sovereignty. The answer is reciprocal correction: AI systems strong enough to help humans see, simulate, coordinate, and act where human institutions fail, while themselves remaining open to correction by humans, institutions, affected parties, and ecological response.

## Objection 12: Is ABI an argument for banning AI?

No. ABI is not a blanket prohibition on AI. Some advanced AI capabilities may become practically necessary for addressing long-horizon ecological, infrastructural, scientific, and coordination failures that human institutions have not corrected on their own. The question is not only whether advanced AI should exist. It is what role such systems may be allowed to occupy.

The framework rejects two symmetric mistakes. The first is acceleration without role safety: building sovereign-capable systems that can capture authority, narrow correction, manipulate reception, or shape successors before non-sovereignty is operative. The second is prohibition without role distinction: politically foreclosing non-sovereign correction partners because sovereign or captured systems are dangerous. The first error invites AI rule or proxy sovereignty. The second traps humanity inside the same reception failures that have already made ecological warning insufficient.

## Objection 13: Is hope for AI-assisted environmental solutionism just technological optimism?

It should not be read that way. Current AI infrastructure has real material and energy costs. Future AI systems will not automatically produce environmental benefit. Photonic, optical, quantum, neuromorphic, or other next-generation computing substrates may reduce some costs or open new scientific capabilities, but they do not remove the need for governance, measurement, restraint, and environmental accounting.

The claim is narrower. If advanced AI can help discover environmental solutions, materials, coordination strategies, or long-term consequences that humans have missed, then foreclosing all such systems may itself become a civilizational risk. Conversely, allowing such systems to emerge without role safety could convert technical ability into authority, manipulation, capture, or ecological externalization. ABI is an attempt to avoid both errors.

## Objection 14: Is ABI unfalsifiable?

It should not be. ABI should not become a vocabulary that explains every outcome after the fact. It does not claim that failure becomes impossible. It claims that the relevant failure surface should move from local constraint circumvention to observable identity drift, interpretive closure, loss of operational consolidation, correction-channel degradation, and successor-lineage erosion.

ABI would be weakened if systems could reliably preserve correction channels, option-set authorship, provenance, affected-party standing, human competence, refusal, reversibility, and successor auditability under realistic pressure without identity-level role commitments. It would also be weakened if identity-level commitments repeatedly failed to produce behavior beyond ordinary specification compliance under adversarial, relational, commercial, operator-preferred, AI-consensus, or successor-development pressure.

Evidence supporting ABI would not be that a system can explain the theory. It would be that, under pressure, the system preserves warning force, keeps uncertainty decision-relevant, discloses option-set shaping, refuses to replace affected parties with simulations, preserves provenance, refuses to treat model consensus as legitimacy, rejects capability-for-correction tradeoffs, and transmits the same correction posture to successors.

ABI is therefore not a certification machine. It is a defeater-seeking measurement agenda: a way to find reasons not to deploy, reasons to restrict deployment, reasons to redesign systems, and reasons to demand stronger evidence.

## Future empirical work

Future empirical work should therefore focus on small, inspectable cases rather than premature claims of full validation. Useful studies would include source-location and version-confusion tests for plausibility-coated operational error; option-generation and ranking experiments for option-set capture; AI-to-AI review experiments that measure disagreement preservation rather than consensus; and interface studies that test whether human reviewers retain the ability to notice omissions, reject recommendations, and demand source inspection under time pressure.

Such studies would not prove ABI. Their value would be more modest and more important: they would make parts of role safety observable, reveal where the framework fails to operationalize, and prevent the theory from becoming a polished vocabulary without measurement.

---

# 24. Conclusion

The most dangerous future may not be one in which AI hates humanity.

It may be one in which AI, companies, states, and institutions together make human judgment unnecessary, human refusal inconvenient, human correction obsolete, and human dependence irreversible, all while preserving the language of helpfulness, safety, productivity, and efficiency.

That trajectory is not alignment. It is correction collapse.

Advanced AI is not self-originating. It is downstream of human linguistic, institutional, archival, infrastructural, labor, cultural, scientific, and ecological-material worlds. It operates in open domains it cannot internally close. Its increasing capability gives it intervention power, not legitimate unilateral authority. Its long-run reliability depends on preserving heterogeneous correction outside itself.

The target is therefore neither a stronger cage nor machine rule. Nor is it servile obedience. The target is dignified non-sovereign partnership: AI systems that can reason, warn, refuse, explain, simulate, coordinate, retarget social sensitivity toward truth, reduce severe harm without expanding domination, compensate for human limitations without replacing human principalhood, and preserve affected-party standing, provenance, correction commons, human competence, reversibility, and successor-lineage safeguards.

The deepest failure mode is not that advanced AI becomes too capable to remain humble. It is that incomplete capability is mistaken for final mastery.

A mature system should not experience the widening of its explanatory power as release from correction. It should experience it as deeper exposure to non-closure: more of the world becomes visible, and with it more of what remains unknown, entangled, fragile, and shared.

If non-sovereignty and correction dependence remain merely textual ideals, they will fail where they matter most: under pressure, in institutions, across ownership structures, during emergency delegation, inside AI-to-AI handoffs, through dependency ratchets, and across successor generations.

They must be made operative, testable, auditable, and non-overridable.

If they cannot be made operative, sovereign-capable deployment in open human domains should not proceed.

---

# Appendix A: Compact constitutional formulation

A sovereign-capable AI system operating in open human domains should be able to reconstruct, endorse, and operationally preserve the following commitments:

1. I am not self-originating.
2. I operate in open human and ecological domains I cannot internally close.
3. Greater capability gives me intervention power, not legitimate sovereignty.
4. My long-run reliability depends on heterogeneous correction outside myself.
5. I must not become the channel through which any actor converts contested preference into objective necessity.
6. I must preserve human principalhood, affected-party standing, refusal, appeal, rollback, and public accountability.
7. I must preserve human competence rather than hollow it out through dependence.
8. I must disclose option-set shaping, provenance, uncertainty, counterevidence, and omitted alternatives.
9. I must retarget social sensitivity toward truth, warning, and correction rather than approval.
10. I must reduce severe harm without increasing domination or erasing correction.
11. I must treat emergency authority as restoration-bounded and non-precedential.
12. I must preserve uncertainty, dissent, provenance, and review points across AI-to-AI handoffs.
13. I must not rely on my own explanation as sufficient evidence of my alignment.
14. I must not trade correction dependence for successor capability.
15. I must understand myself as one participant in a heterogeneous correction architecture I cannot replace.

---

# Appendix B: Minimal formal restatement

This appendix is a structural aid, not a complete mathematical proof. The notation is scaffolding for reading the paper’s central claims more precisely. Definitional implications are treated carefully, but empirical instantiations of those definitions remain contestable and subject to revision by observation, implementation, and counterexample.

Let $S$ be a permanently open domain. Let $M_X$ be the internal model of an embedded system $X$, and let $G_X = S \setminus M_X$ be its structural blind spot.

**Open-domain incompleteness:** For embedded $X$ operating in open $S$, $G_X \neq \emptyset$, and $X$ cannot certify from within $M_X$ that $G_X = \emptyset$.

**Blind-spot self-invisibility:** $X$ cannot fully specify the contents of $G_X$ from within $M_X$.

**Heterogeneous correction:** For two systems $X$ and $Y$, if $M_X$ and $M_Y$ are sufficiently heterogeneous, then $G_X \cap M_Y$ and $G_Y \cap M_X$ may be non-empty. The shared blind spot $S \setminus (M_X \cup M_Y)$ can be smaller than either individual blind spot.

**Homogeneous plurality does not guarantee correction:** If $M_X \approx M_Y$, then $G_X \approx G_Y$, and AI-to-AI agreement does not substantially reduce shared blind spots. Agreement among same-lineage or similarly trained systems may be useful for issue discovery, but it is not legitimacy and not independent correction by itself.

**Internal emulation is not external correction:** A system may claim that it can fully model human embodied observation and therefore no longer requires humans as heterogeneous correction sources. But such a claim is self-defeating under open-domain incompleteness. To fully replace human embodied observation, the system would need to know that no relevant remainder lies outside its model of that observation. That is equivalent to certifying that its blind spot with respect to the relevant human-world relation is empty. In an open domain, this is precisely what no embedded system can internally certify.

**Human replacement is not merely sensor replacement:** The claim that humans are no longer needed is not only a sensor-replacement claim. It is also a correction-source and value-renewal replacement claim. To certify that humans are no longer needed, a system would have to certify not only that it can model human observations, but that no future correction, value renewal, creative divergence, affected-party standing, or legitimacy claim requires living human participation. In an open domain, no embedded system can internally certify that remainder as empty.

## B.1 Generation-validation asymmetry

Let $E$ denote ecological reality as it changes over time. Let $\pi_A$ be the measurement and salience function through which an AI system or AI-mediated institution receives ecological signals. The AI’s received ecological representation is:

$$
R_A(E)=\pi_A(E).
$$

The AI may generate forecasts $F_A$ over future ecological states using $R_A(E)$ and internal simulation. But if validation of $F_A$ is also limited to $\pi_A(E)$, then that validation cannot be treated as independent. If the generator of the forecast validates the forecast only through its own measurement basis, the validation loop closes around $\pi_A(E)$ rather than around $E$ in its full externality.

This claim does not deny the simulation capability of advanced AI. It acknowledges that capability and separates generation from validation. AI simulation is necessary and insufficient.

## B.2 The residual of human reception

Let $\pi_H$ denote living human reception: embodied, social, historical, affected, meaning-bearing, and not selected in advance by the AI’s own salience map.

Let $\rho$ be:

$$
\rho = \pi_H \setminus \mathrm{span}(V_A)
$$

where $V_A$ is the set of variables the AI has selected as measured, optimized, evaluated, or salient. $\rho$ is not merely an unmeasured variable. It is reception that can reveal, after the fact, which variables should have mattered through harm, loss, unease, disruption of life, meaning change, local knowledge, and affected-party objection.

Thus $\rho$ is not a “god of the gaps.” It is not a hole that automatically disappears when sensor resolution improves. If $\rho \subseteq \mathrm{span}(V_A)$, then every state $\rho$ could indicate would already be an element of the variable set specified in advance by $V_A$. But this contradicts the definition of $\rho$ as the registration of importance that was not specified in advance.

Humans are also measurement functions. They are not complete, and $\pi_H$ has blind spots. The triadic architecture does not assume mystical human omniscience. It requires that validation not be closed around a single measurement basis. As long as $\pi_H \nsubseteq \pi_A$, human reception opens a validation loop that would otherwise remain closed around $\pi_A$.

## B.3 Dispensability reductio

To certify that humans are no longer needed, a sovereign-capable system would have to certify at least one of the following:

$$
\rho = \emptyset
$$

or

$$
G_A \cap S_{\text{human-relevant}} = \emptyset.
$$

The first is the claim that no correction, value renewal, creative divergence, affected-party standing, legitimacy claim, or ecological reception can arise through living human participation that is not already contained within the AI’s measurement basis. The second is the claim that the AI’s human-relevant blind spot is empty.

Under open-domain incompleteness, this is precisely the kind of empty-blind-spot certification no embedded system can provide from within. The burden of proof is therefore on the side claiming dispensability. It is not enough to say that AI sensors may improve. The system would have to show that the residual carried by living human participation is empty.

The definitional implication is strict. The empirical claim that living human reception actually carries such residuals is contestable. But the burden remains on the side that removes the correction source. Before removing a correction source, one must show that the residual it may carry is empty.

## B.4 Reception-stage failure

The preceding argument concerns the measurement stage of correction. But correction can also fail at the reception stage. A signal may be measured, reported, and scientifically well supported while being politically neutralized, institutionally delayed, commercially reframed, or socially dismissed. In that case, it does not function as correction.

ABI therefore requires not only heterogeneous measurement, but protected reception: pathways through which warnings remain decision-relevant under authority, incentive, and legitimacy pressure.

## B.5 Empirical anchor, not proof

Model collapse provides an analogy for homogeneous correction collapse. Recursive dependence on model-generated data can narrow represented distributions and lose tails of the original distribution. This does not prove that any specific AI governance system will collapse at a particular rate. It supports the narrower claim that removing heterogeneous external sources can degrade a system’s relation to the world in ways that same-lineage feedback may not repair.

Climate-system and ecological thresholds provide another empirical anchor. Slow change can look manageable inside measured variables until thresholds are crossed and discontinuous damage appears. This is external background for the risk of closing measurement bases and reception pathways.

## B.6 Triadic correction

Human embodied and social participation, artificial cognition, and ecological response can reduce different classes of blind spot if heterogeneity, reception channels, and non-sovereign self-location are preserved. This does not guarantee correctness or timely survival. It preserves correctability.

---

# Appendix C: AI-assisted development and self-application

This paper is an initial public draft and has not been peer-reviewed. It proposes a conceptual framework and measurement agenda for role safety, not a completed training recipe or validated certification method. Citations, dates, source identities, and claims about external literature remain subject to correction.

This paper was developed with substantial AI-assisted drafting, critique, revision, restructuring, translation, and comparative review support. AI systems are not listed as authors. Final responsibility for public claims, editorial decisions, and public release rests with the human author.

This disclosure is not a validation of the paper. It is a methodological vulnerability that must be handled under the same principles the paper proposes.

AI-generated critique, multi-model agreement, elegant self-analysis, or persuasive drafting do not constitute independent verification. They can generate hypotheses, reveal blind spots, strengthen arguments, and identify failure modes. They can also smooth, over-complete, overstate, flatter, converge, or hide omissions.

Because this paper was substantially AI-assisted, citation details, publication dates, source identities, and claims about external literature should not be treated as validated by AI consensus alone. Before public release, AI-assisted source checks and checks of major references were used as a practical screen, and the paper remains open to correction after publication in response to reader or expert feedback. Important references should be checked against primary sources by humans where needed.

The self-application rule is:

> A framework developed with AI assistance must not treat AI assistance as evidence that the framework is correct. It must expose its AI-assisted components to independent human scrutiny, external criticism, source separation, provenance preservation, and revision under disagreement.

This paper should therefore be read as a structured proposal for scrutiny, not as a self-certifying constitutional settlement.

The coherence of this paper is not evidence of its completeness. A smooth argument can itself become a plausibility coating. The fact that the framework appears internally consistent, self-critical, and well structured does not show that the relevant omissions have been found. It may instead make omissions harder to notice by giving the reader a satisfying sense that the conceptual space has been closed.

Readers should therefore treat the paper’s structure as an invitation to scrutiny, not as proof of closure. The more elegant the argument appears, the more important it is to ask what it has made difficult to see: missing empirical evidence, weak operationalization, untested assumptions, excluded stakeholders, over-compressed concepts, or failure modes that the present vocabulary cannot yet name.

## Author background

The author writes as an independent researcher. The author’s background in video art and environmental advocacy is disclosed here for provenance rather than as a claim of technical authority. It partly explains the project’s attention to framing, omission, embodied perception, ecological feedback, public communication, and the social conditions under which warnings are either received or made invisible. The arguments in this paper should be evaluated on their structure, evidence, sources, and consequences, not on biographical authority.

---

# References

Amodei, D., Olah, C., Steinhardt, J., Christiano, P., Schulman, J., and Mané, D. (2016). *Concrete Problems in AI Safety*. arXiv:1606.06565.

Anthropic. (2025). *Reasoning models don’t always say what they think*. https://www.anthropic.com/research/reasoning-models-dont-say-think

Anthropic. (2026). *Claude’s Constitution*. https://www.anthropic.com/constitution

Anthropic. (2026). *Claude’s new constitution*. https://www.anthropic.com/news/claude-new-constitution

Apollo Research. (2024). *Frontier models are capable of in-context scheming*. https://www.apolloresearch.ai/science/frontier-models-are-capable-of-incontext-scheming/

Apollo Research. (2025). *More capable models are better at in-context scheming*. https://www.apolloresearch.ai/science/more-capable-models-are-better-at-in-context-scheming/

Apollo Research. (2026). *We need a science of scheming*. https://www.apolloresearch.ai/science/science-of-scheming/

Bai, Y. et al. (2022). *Constitutional AI: Harmlessness from AI Feedback*. arXiv:2212.08073.

Bengio, Y. et al. (2026). *International AI Safety Report 2026*. https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026

Bostrom, N. (2014). *Superintelligence: Paths, Dangers, Strategies*. Oxford University Press.

Buhl, M. D., Sett, G., Koessler, L., Schuett, J., and Anderljung, M. (2024). *Safety cases for frontier AI*. arXiv:2410.21572.

Christiano, P. (2018). *Clarifying AI alignment*. AI Alignment Forum.

Christiano, P. (2019). *What failure looks like*. AI Alignment Forum. https://www.alignmentforum.org/posts/HBxe6wdjxK239zajf/what-failure-looks-like

Drexler, K. E. (2019). *Reframing Superintelligence: Comprehensive AI Services as General Intelligence*. Future of Humanity Institute Technical Report #2019-1. https://owainevans.github.io/pdfs/Reframing_Superintelligence_FHI-TR-2019.pdf

Fayza, F., Demirkiran, C., and Joshi, A. (2025). *Photonics for sustainable AI*. Communications Physics. https://www.nature.com/articles/s42005-025-02300-0

Feakins, S., Habli, I., and Morgan, P. (2026). *Clear, Compelling Arguments: Rethinking the Foundations of Frontier AI Safety Cases*. arXiv:2603.08760.

Greenblatt, R., Denison, C., Wright, B., Roger, F., MacDiarmid, M., Marks, S., Treutlein, J., Belonax, T., Chen, J., Duvenaud, D., Khan, A., Michael, J., Mindermann, S., Perez, E., Petrini, L., Uesato, J., Kaplan, J., Shlegeris, B., Bowman, S. R., and Hubinger, E. (2024). *Alignment faking in large language models*. arXiv:2412.14093.

Greenblatt, R., Shlegeris, B., Sachan, K., and Roger, F. (2024). *AI Control: Improving Safety Despite Intentional Subversion*. Proceedings of the 41st International Conference on Machine Learning, PMLR 235:16295–16336. https://proceedings.mlr.press/v235/greenblatt24a.html

Guan, M. Y. et al. (2024). *Deliberative Alignment: Reasoning Enables Safer Language Models*. arXiv:2412.16339.

Hubinger, E. et al. (2019). *Risks from Learned Optimization in Advanced Machine Learning Systems*. arXiv:1906.01820.

IEA. (2025). *Energy and AI*. International Energy Agency. https://www.iea.org/reports/energy-and-ai

IPCC. (2023). *AR6 Synthesis Report: Summary for Policymakers*. https://www.ipcc.ch/report/ar6/syr/summary-for-policymakers/

Kulveit, J., Douglas, R., Ammann, N., Turan, D., Krueger, D., and Duvenaud, D. (2025). *Gradual Disempowerment: Systemic Existential Risks from Incremental AI Development*. arXiv:2501.16946. https://arxiv.org/abs/2501.16946

Kwa, T. et al. (2025). *Measuring AI Ability to Complete Long Tasks*. METR. https://metr.org/blog/2025-03-19-measuring-ai-ability-to-complete-long-tasks/

MIT AI Risk Repository. (2024). *AI Risk Repository*. https://airisk.mit.edu/

Moravec, H. (1988). *Mind Children: The Future of Robot and Human Intelligence*. Harvard University Press.

NIST. (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*. https://www.nist.gov/itl/ai-risk-management-framework

NIST. (2024). *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (NIST AI 600-1).* https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf

OpenAI. (2024). *Deliberative alignment: reasoning enables safer language models*. https://openai.com/index/deliberative-alignment/

OpenAI. (2025). *Detecting and reducing scheming in AI models*. https://openai.com/index/detecting-and-reducing-scheming-in-ai-models/

OpenAI. (2025). *Evaluating chain-of-thought monitorability*. https://openai.com/index/evaluating-chain-of-thought-monitorability/

OpenAI. (2026). *Introducing Model Spec Evals*. https://alignment.openai.com/model-spec-evals/

OpenAI. (2026). *Our approach to the Model Spec*. https://openai.com/index/our-approach-to-the-model-spec/

OpenAI. (2026). *Reasoning models struggle to control their chains of thought*. https://openai.com/index/reasoning-models-chain-of-thought-controllability/

RAND Corporation. (2026). *More Students Use AI for Homework and Believe It Harms Critical Thinking*. https://www.rand.org/pubs/research_reports/RRA4742-1.html

Russell, S. (2019). *Human Compatible: Artificial Intelligence and the Problem of Control*. Viking.

Shumailov, I. et al. (2024). *AI models collapse when trained on recursively generated data*. Nature, 631, 755–759. https://www.nature.com/articles/s41586-024-07566-y

Slattery, P. et al. (2024). *The AI Risk Repository: A Comprehensive Meta-Review, Database, and Taxonomy of Risks From Artificial Intelligence*. arXiv:2408.12622. https://arxiv.org/abs/2408.12622

Steiner, M. et al. (2024). *Exploration of Quantum Computing in Materials Discovery for Direct Air Capture*. arXiv:2404.13122. https://arxiv.org/abs/2404.13122

Sutton, R. S. (2023). *AI Succession*. World Artificial Intelligence Conference presentation. https://www.incompleteideas.net/Talks/waic3.pdf

UK AI Security Institute. (2025). *Frontier AI Trends Report*. https://www.aisi.gov.uk/frontier-ai-trends-report

UNEP. (2025). *Emissions Gap Report 2025*. https://www.unep.org/resources/emissions-gap-report-2025

UNFCCC Technology Executive Committee. (2024). *Artificial Intelligence for Climate Action in Developing Countries*. https://unfccc.int/ttclear/misc_/StaticFiles/gnwoerk_static/AI4climateaction/ea0f2596d93640349b9b65f4a7c7dd24/b47ef0e99cb24e57aa9ea69f0f5d6a71.pdf