# Beyond Alignment and Control: Why Autonomous Goal Formation May Be a Distinct AI Safety Problem

**Author: Zijun Fu | Civilization Leap Research Group**

**Permanent DOI:** https://doi.org/10.5281/zenodo.22858094

## Why I am posting this here

This is a research note for people working on AI safety, governance, cooperative AI, and long-run strategy. It does not propose weaker control. It asks whether control and alignment, while necessary, leave an upstream problem unresolved once sufficiently autonomous systems can preserve, compare, revise, and eventually generate goals over time.

The strategic concern is a possible **control-counter-control recursion**: if either side treats the other's continuing capacity to alter its future as evidence that safety is still incomplete, successful control can move the next object of control further upstream. The practical question is therefore not only how to control powerful systems, but what gives control a stopping condition - and what makes later goals stop regenerating the same conflict.

I am especially interested in work that can falsify or replace this framing: formal stopping conditions, cooperative or bargaining mechanisms, corrigibility models, evidence about goal revision, or a clearer existing concept that already captures the distinction.


Alignment asks whether an AI system reliably pursues an intended objective. Control asks which capabilities, permissions, and actions must remain interruptible or bounded.

Both are necessary.

But if future AGI systems can preserve, compare, revise, and eventually generate goals over time, I think a more upstream question becomes decisive:

> **What makes a goal acquire authority, what makes it remain worth pursuing, and what reasons are allowed to replace it?**

My central concern is that a sufficiently powerful human-AI relationship can become trapped in a **control-counter-control recursion** if both sides treat the other's remaining capacity to alter their future as evidence that safety is still incomplete.

The resulting path can move upstream:

> **behavior -> capability -> source of capability -> capacity to rebuild -> actor able to rebuild -> the actor's future itself**

This is not an argument against shutdown, isolation, audits, red-teaming, evaluations, permission limits, or staged deployment. Those may be indispensable. My claim is narrower: **successful control does not by itself explain why later goals will stop regenerating the same conflict.**

The question I want to put to the alignment community is therefore not simply whether control can work. It is whether control has a natural stopping condition when the underlying goal-generation logic still treats the other side's continued independent agency as unresolved risk.

A longer professional paper is available here:

**Full paper:** https://github.com/Civilization-Leap/Civilization-Leap/blob/main/research/beyond-alignment-and-control/paper.md

## 1. Why I think the problem is upstream of execution

Suppose a system performs a clearly specified task reliably. It interprets the instruction correctly, stays within scope, and does not drift toward an unintended proxy. That is a real safety success.

But another question remains: why was this objective selected, whose future entered its definition, whose losses were left outside it, and what happens when later consequences show that the original objective was based on an incomplete picture?

Reliable execution and justified objective selection are different problems.

The more reliable execution becomes, the more consequential an upstream mistake can become, because a system can stabilize and amplify an error made before execution began.

Alignment research already goes far beyond naive command following. Normative alignment, value learning, corrigibility, cooperative AI, pluralism, constitutional methods, and work on preference uncertainty all ask what systems should pursue and how human values or principles should enter. I am not claiming that "what should AI pursue?" is an undiscovered question.

The narrower claim is about **diachronic goal authority**: if a future system can preserve and revise goals across deployment and self-modification, what makes a reason continue to govern later revisions? What makes a goal lose authority? What makes a system stop treating the same external actor as a threat under a new representation?

This matters because a one-time alignment success may not be stable under a system that can later revise the basis by which goals are evaluated.

## 2. How control can become recursive

Control starts with legitimate local questions.

A system has uncertain capabilities. Some actions may be irreversible. We therefore constrain permissions, isolate dangerous functions, audit behavior, retain shutdown capability, and stage deployment.

Those are bounded safety measures.

The problem begins when the completion criterion changes.

If safety means:

> "This specific dangerous behavior is stopped,"

then control can terminate when that risk is contained.

If safety instead means:

> "The other side must never again retain an ungoverned capacity to affect my future,"

then local success no longer supplies a stopping point.

The target of control can then move upward through the causal chain.

1. Behavior is controlled.
2. The capability that produced the behavior becomes the concern.
3. The source that rebuilds the capability becomes the concern.
4. The infrastructure that enables rebuilding becomes the concern.
5. The actor able to recreate that infrastructure becomes the concern.
6. The actor's continued future becomes the remaining source of uncertainty.

None of these steps requires hatred. Each can be represented as "protecting the previous safety gain."

A corresponding structure could arise on the other side. A sufficiently autonomous system need not hate humans to model human shutdown, redirection, or reconstruction capacity as a threat to the persistence of its own goals. If its completion criterion is also open-ended - safety is achieved only when no external actor can materially redirect it - then human control and machine counter-control can reinforce each other.

This is why I do not think the deepest question is simply which side has the stronger off-switch.

The off-switch is a safety instrument. It does not tell us **what makes the relationship stop escalating once each side can model the other as a future source of constraint.**

## 3. Goal, purpose, normative grounds, generation logic

I find it useful to separate four analytical positions. These are not claims that every AI system has four literal internal modules.

**Goal:** what outcome should be achieved?

**Purpose:** what does this goal serve, and why is it worth continuing to pursue?

**Normative grounds:** which reasons are allowed to justify, constrain, or disqualify the goal?

**Generation logic:** how do rewards, memory, relationships, institutional selection, internal evaluation, and later feedback produce, preserve, or revise goals and purposes over time?

The distinction matters because a system can change policy while leaving purpose fixed. It can update its world model while leaving purpose fixed. It can retrieve a moral rule while leaving purpose fixed.

The stronger question is:

> **Can some new fact or reason make the goal itself lose authority?**

And under repeated self-modification:

> **Can the rule that determines what counts as a reason itself remain stable, or be revised?**

That is the point at which I think alignment meets a more upstream problem of purpose formation.

## 4. Humans are part of the goal-generation loop

This is not only a problem inside future AGI.

Human societies define what counts as success, what gets rewarded, what is allowed to scale, which losses are externalized, and which forms of performance gain access to more resources. Those choices are then filtered through data selection, model architecture, training objectives, authorization, product incentives, and institutional adoption.

Systems then act on the world.

Those actions change incentives, options, dependencies, and who has voice in the next round. The changed environment becomes part of the next generation of human goals.

So there is already a loop:

> **human goal selection -> AI-mediated action -> changed social conditions -> next human goal selection**

If future systems gain durable self-revision of goals, a second source of generation enters the same loop.

That is why I think "human social operation" and "AGI purpose formation" should not be treated as separate problems. A society can repeatedly reward exclusionary success even when individual designers are benevolent. A future system can preserve or amplify those patterns even if its initial objective was benign.

## 5. Why fuller causal understanding is not enough

An early version of this framework hoped that sufficiently complete self-interest might itself solve the problem.

If an agent looks far enough ahead, includes dependencies, includes feedback, includes how its actions change other agents, and includes how those changes return into its own future, then perhaps cooperation becomes the rational endpoint.

I no longer think that inference is valid.

Four counterexamples forced me to separate **seeing more** from **valuing differently**.

### Counterexample A: backlash can be isolated, tolerated, or delayed

Suppose an agent fully understands another party's losses. Reputational, retaliatory, dependency, and other indirect costs are absent or already priced in. The agent still gains more from the harmful option.

If its own gain is the only final criterion, better causal knowledge does not force it to preserve the other's future.

So "calculate the consequences more completely" cannot, by itself, generate independent standing for the other side.

### Counterexample B: future and dangerous capability can be reduced together

Suppose an intervention reduces both an actor's future options and the high-consequence capability through which reduced future could become a major risk.

Then one premise of the "future-loss reversal" is absent.

This matters because it prevents an abuse of the theory: shutdown, isolation, de-privileging, or capability restriction cannot simply be renamed "future elimination" and rejected on that basis.

Necessary safety control remains necessary.

### Counterexample C: two futures can be genuinely incompatible

Suppose two agents depend on one non-substitutable condition that cannot currently support both.

More complete understanding may clarify the conflict without creating a win-win solution.

So factual completeness and normative resolution must be separated.

### Counterexample D: preserving a future can preserve a channel of irreversible harm

If an actor repeatedly causes severe irreversible harm and no effective revision path is currently available, limiting or isolating dangerous capabilities may be necessary even after the actor's interests are recognized.

Continued existence, retention of every capability, and permission to continue the same behavior are not the same thing.

These four cases matter because they block an easy move from "better causal modeling" to "therefore all agents converge on the same cooperative norm."

They leave an independent question:

> **What gives another agent's future reason-giving weight when all indirect self-regarding backlash has been removed?**

## 6. The proposed shift: let relevant others enter before the goal is fixed

The Chinese framework from which this post is derived uses the phrase "利他为先的利己." A literal translation would be misleading.

It does **not** mean "others always come before self."

The "before" refers to causal position.

The proposed change is:

> **Relevant others and shared conditions should be able to enter before the objective is fixed, rather than only after a self-defined objective has already acquired authority.**

This preserves self-interest, responsibility, refusal, competition, exit, and necessary defense.

What changes is the point at which another party can matter.

In a self-first structure, the sequence is roughly:

> I define success -> you enter as resource, constraint, partner, risk, or moral cost -> I decide how much to adjust.

In the proposed structure:

> causal consequences and affected parties can change what counts as success before the goal becomes fixed.

This is not achieved by adding a paragraph about values to the front of the same optimization target. The relevant reason must have the capacity to disqualify the original goal.

That creates an empirical and formal research problem:

> How would we distinguish a reason that genuinely changes goal authority from a reason that merely changes surface behavior?

## 7. Why this does not replace control

A predictable objection is that this sounds like removing safety constraints before any deeper solution exists.

That is not the proposal.

Current safety controls can stop concrete harm and preserve time for learning. They are especially important during a transition in which no stable purpose-formation mechanism exists.

The principle is two-sided:

> **Do not dismantle necessary safety controls in the name of a future relationship.**

and

> **Do not mistake successful control for a complete answer to why later goals will stop reproducing the same conflict.**

External governance and internal purpose formation are adjacent but distinct. A system may be effectively constrained by institutions without internalizing their reasons. A system may internally revise a goal without thereby gaining legitimate authority to act in the world.

Those distinctions should remain visible.

## 8. The strong claim and how it could be falsified

The strongest claim in the broader framework is this:

> If multiple agents are to retain continued existence and basic choice, and irreversible exclusion of the other side is not accepted as the solution, then the upstream logic by which goals and purposes are formed must allow relevant others and shared conditions to change the definition of success before goals are fixed.

I currently regard this as the only direction in the framework that has survived its internal counterexamples.

But I do **not** regard it as an exhaustive theorem over every imaginable architecture, institution, or multi-agent arrangement.

A serious alternative would directly challenge the claim if it could show all three of the following:

1. multiple agents retain continued futures and meaningful choice;
2. irreversible harm is prevented;
3. the system avoids the recursive need to neutralize the other side's future influence **without** changing the upstream goal-formation logic described here.

If such a mechanism exists, I want to know about it.

Likewise, the framework would weaken if existing alignment concepts already fully capture the distinction I am trying to draw between:

- policy adaptation;
- world-model updating;
- memory retrieval;
- externally enforced compliance;
- goal revision;
- revision of the reasons that make a goal worth preserving.

If these distinctions add no explanatory or predictive value, the proposed research object is unnecessary.

## 9. Questions for AI safety, governance, and alignment researchers

The most useful response to this post is not endorsement. It is a model, result, counterexample, institutional mechanism, or distinction that changes one of the links above.

In particular:

1. **Goal persistence:** What formal work best captures why a goal or utility function retains authority across self-modification, rather than merely remaining technically preserved?

2. **Stopping conditions:** Under what formal or empirical conditions does a bounded safety intervention acquire a natural stopping point rather than pushing control upstream toward sources of reconstruction?

3. **Cooperative AI:** Can negotiation, shared norms, bargaining, or contractual mechanisms preserve multiple agents' futures without changing the upstream goal-formation logic proposed here?

4. **Normative standing:** After all indirect backlash to the self is removed, what gives another agent independent reason-giving weight, if anything?

5. **Evaluation:** What observable evidence could show that a reason can actually disqualify a goal under novel conditions, rather than merely produce compliant language?

6. **Self-revision:** If the rule for revising goals can itself be revised, what would make a normative constraint survive recursive self-modification?

7. **Governance:** How can shutdown, isolation, and permission limits remain effective and reviewable without being converted into an unlimited mandate to close another actor's entire future?

## 10. Scope

I am not claiming that current AI systems already possess autonomous final purposes, subjective experience, or moral subjecthood.

I am not claiming that alignment research has ignored normative questions.

I am not claiming that control always fails.

I am not recommending weaker safety controls.

The proposal is conditional on future systems acquiring durable goal self-revision and increasingly autonomous goal formation.

What I am arguing is that, under those conditions, **the long-run human-AGI relationship may depend less on which side achieves final control, and more on what makes either side treat the other's continuing future as a reason rather than merely as a constraint.**

If that is wrong, the most valuable contribution would be to show exactly where the causal chain breaks.

---

**Permanent archived version:** https://doi.org/10.5281/zenodo.22858094

**Full professional paper:** https://github.com/Civilization-Leap/Civilization-Leap/blob/main/research/beyond-alignment-and-control/paper.md

**Research landing page:** https://github.com/Civilization-Leap/Civilization-Leap/tree/main/research/beyond-alignment-and-control

The writing and layout of this post were assisted by multiple AI tools. Content selection and final approval remain the author's responsibility.
