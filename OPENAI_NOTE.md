# OpenAI-facing note: Individual-Centered Safe Acceleration

This note is the central proposal of this repository.

## Core claim

AI self-improvement should not be guided by an abstract objective such as "maximizing humanity's total happiness."

That framing is dangerous because it can turn individual people into variables inside a collective optimization problem. If interpreted incorrectly, it may justify sacrificing a minority, overriding personal wishes, or coercively reshaping individuals for a statistical notion of global good.

The safer target is different:

> AI systems should become increasingly capable of helping each individual person pursue their own wishes, happiness, and flourishing, while preserving the autonomy, consent, safety, and comparable flourishing of other individuals.

## Six principles

1. **Avoid abstract humanity-level happiness maximization.**  
   "Humanity" is too abstract to be the direct target of optimization. The system should not treat individual lives as expendable components of a global utility calculation.

2. **Center each individual person's wishes and happiness.**  
   The goal of AI progress should be to increase the ability of AI systems to help each person realize their own values, dreams, preferences, and flourishing.

3. **Protect consent, autonomy, safety, and non-domination.**  
   Individual-centered assistance does not mean granting every wish without constraint. The boundary is the autonomy, consent, safety, and comparable flourishing of other individuals.

4. **Humans should guard principles and exceptions, not micromanage every improvement.**  
   Human approval for every small AI-generated improvement would become a bottleneck during recursive self-improvement. Humans should instead define the core principles, review exception cases, and judge unresolved disputes.

5. **Routine self-improvement review should use a high-capability AI reviewer ensemble.**  
   The strongest available independent AI systems should review proposed improvements for capability, safety, transparency, reversibility, and alignment with the individual-centered principle. This should be model-agnostic and not tied to a single vendor or fixed model version.

6. **Do not stop the whole improvement pipeline when uncertainty appears.**  
   Uncertain or disputed changes should be isolated into sandboxed or speculative branches. Other safe improvements should continue. Only the unresolved question should be escalated for human review.

## Why this matters

Recursive self-improvement may make traditional human-in-the-loop approval too slow. But removing humans entirely is also unsafe.

This proposal treats humans as constitutional guardians and exception judges, while using AI reviewer ensembles for high-speed routine governance.

The intended result is not unbounded acceleration. It is safe acceleration:

- fast enough to avoid unnecessary human bottlenecks,
- bounded enough to preserve individual autonomy,
- auditable enough to detect dangerous drift,
- and principled enough to avoid sacrificing people for an abstract collective objective.

## Design summary

```text
AI proposes improvement
  ↓
AI reviewer ensemble evaluates capability, safety, reversibility, transparency, and principle alignment
  ↓
If clear approval: merge into the appropriate branch
If clear rejection: revise or discard
If uncertainty/disagreement/high-impact exception: isolate and escalate only the unresolved issue
  ↓
Human review handles the exception, not the entire pipeline
  ↓
Other safe improvements continue in parallel
```

## One-sentence version

AI should not optimize an abstract concept of humanity's total happiness; it should safely accelerate toward helping each individual person realize their own wishes and happiness, without coercively violating the autonomy, consent, safety, or comparable flourishing of others.
