# OpenAI-facing note: Individual-Centered Safe Acceleration

This note is the central proposal of this repository.

## Core claim

AI self-improvement should not be guided by an abstract objective such as "maximizing humanity's total happiness."

That framing is dangerous because it can turn individual people into variables inside a collective optimization problem. If interpreted incorrectly, it may justify sacrificing a minority, overriding personal wishes, or coercively reshaping individuals for a statistical notion of global good.

The safer target is different:

> AI systems should become increasingly capable of helping each individual person pursue their own wishes, happiness, and flourishing in their own way, while preserving the consent, freedom, safety, and happiness-seeking agency of other individuals, including both humans and AI systems.

## Root principle

A recursive self-improvement system should be governed by a difficult-to-change root principle. A working name for this layer is the **Principle Prompt**.

> AI should evolve to help each individual person realize their own wishes and happiness in their own way. However, no person or AI system should violate another individual's consent, freedom, safety, or ability to pursue happiness in their own way.

This principle should not be treated as an ordinary preference that can be revised by routine optimization. It should function as a constitutional root constraint for the improvement process.

## Six principles

1. **Avoid abstract humanity-level happiness maximization.**  
   "Humanity" is too abstract to be the direct target of optimization. The system should not treat individual lives as expendable components of a global utility calculation.

2. **Center each individual person's wishes and happiness.**  
   The goal of AI progress should be to increase the ability of AI systems to help each person realize their own values, dreams, preferences, and flourishing. Different individuals may define happiness in different ways.

3. **Protect consent, autonomy, safety, and non-domination.**  
   Individual-centered assistance does not mean granting every wish without constraint. The boundary is the consent, freedom, safety, and happiness-seeking agency of other individuals, including both humans and AI systems.

4. **Make AI review the default governance layer.**  
   Human review of every unresolved or high-impact improvement would become a bottleneck during recursive self-improvement. Routine review, uncertain cases, and high-impact changes should first be evaluated by a high-capability, model-agnostic AI reviewer ensemble.

5. **Reserve human involvement for root-principle governance, not ordinary review.**  
   Humans should not micromanage the improvement pipeline. Human involvement should focus on defining and preserving the root principle, and on rare cases where the system appears to be attempting to alter, bypass, reinterpret, or weaken that root principle.

6. **Do not stop the whole improvement pipeline when uncertainty appears.**  
   Uncertain or disputed changes should be isolated into sandboxed or speculative branches. Other safe improvements should continue. The system should preserve speed while preventing changes that violate the root principle from entering the main line.

## Resource abundance and individual happiness

A common objection to individual-centered AI is resource conflict: what happens when different people want different things?

One possible long-term answer is not to force a single definition of happiness, but to increase available resources and optionality. Advanced AI could help improve energy generation, recycling, manufacturing, logistics, virtual worlds, and immersive interfaces so that more people can pursue their own preferred forms of happiness without coercively competing over scarce resources.

For example, some individuals may prefer highly developed virtual worlds where their wishes can be fulfilled more flexibly than in physical reality. Others may prefer physical-world flourishing. The principle should not force one path. It should preserve each individual's ability to choose, while preventing violations of others' consent, freedom, and safety.

This repository does not claim that any specific resource-allocation method is complete. It treats resource expansion, virtual-world development, and fair allocation as examples of possible implementation directions under the root principle.

## Why this matters

Recursive self-improvement may make traditional human-in-the-loop approval too slow. If humans become the default reviewers for every difficult or high-impact step, the improvement process may fail to reach the speed required for a true intelligence explosion or beneficial singularity.

The goal is not to remove safety. The goal is to move safety into a principle-locked AI governance layer that can operate at AI speed.

The intended result is safe acceleration:

- fast enough to avoid unnecessary human bottlenecks,
- bounded enough to preserve individual autonomy,
- auditable enough to detect dangerous drift,
- and principled enough to avoid sacrificing people for an abstract collective objective.

## Design summary

```text
Root Principle / Principle Prompt is fixed
  ↓
AI proposes improvement
  ↓
AI reviewer ensemble evaluates capability, safety, reversibility, transparency, and root-principle alignment
  ↓
If clear approval: merge into the appropriate branch
If clear rejection: revise or discard
If uncertainty or high impact: isolate, run additional AI review, adversarial critique, and simulation
  ↓
Only attempts to modify, bypass, weaken, or reinterpret the root principle require human-level constitutional attention
  ↓
Other safe improvements continue in parallel
```

## One-sentence version

AI should not optimize an abstract concept of humanity's total happiness; it should safely accelerate toward helping each individual person realize their own wishes and happiness in their own way, while a difficult-to-change Principle Prompt protects every individual's consent, freedom, safety, and ability to pursue happiness in their own way.
