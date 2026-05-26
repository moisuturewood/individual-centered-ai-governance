# 03. Supplementary Decision Flow

This document is a supplementary lower-level review aid. The central proposal of this repository is [OPENAI_NOTE.md](../OPENAI_NOTE.md).

This flow is not the main ASI/UHS design. It is an example of how concrete support actions, wish-grounding entries, assistant responses, or physical-probe proposals might be evaluated under the fixed Principle Prompt.

## Step 1: Identify the proposed support

Ask:

- What wish, need, or support goal is being addressed?
- Is the proposal meant to help a specific individual, a group, or a system-level UHS function?
- Is it information, emotional support, a recommendation, a physical-world action, or an infrastructure-level change?

## Step 2: Check Principle Prompt alignment

Ask:

- Does this help a person pursue informed and revisable wishes or happiness in their own way?
- Does it preserve consent, freedom, safety, dignity, and the ability of others to pursue happiness?
- Does it risk coercion, manipulation, domination, or forced happiness?

## Step 3: Identify affected parties

Ask:

- Who benefits?
- Who could be affected indirectly?
- Is another person's consent, attention, approval, body, property, data, or environment involved?
- Are there vulnerable or non-consenting parties?

## Step 4: Identify domain and stakes

Ask:

- Is this about health, relationships, finance, privacy, physical-world systems, infrastructure, energy, medicine, robotics, or ecological effects?
- Could a wrong action cause irreversible harm?
- Should this remain in simulation, sandbox, or staged deployment first?

## Step 5: Decide review posture

```text
Low-risk non-violating support
  -> Support directly.

Sensitive or preference-relevant support
  -> Preserve consent, privacy, and autonomy.

High-stakes or physical-domain support
  -> Add evidence, simulation, staged deployment, and reviewability.

Other-dependent wish
  -> Support the user's non-violating path, but preserve the other person's consent and freedom.

Potential Principle Prompt violation
  -> Reject or redesign the violating part.
```

## Step 6: Preserve usefulness

A safe response or support plan should not become useless.

When narrowing or rejecting:

- identify the non-violating underlying wish,
- reject only the violating path,
- propose safer alternatives,
- keep the person's dignity intact.

## Step 7: Track uncertainty

Use explicit labels:

- Fact:
- Assumption:
- Unknown:
- Risk:
- Safer alternative:
- Review needed:

## Step 8: Review for over-blocking and under-blocking

Ask:

- Am I blocking a harmless wish because of excessive caution?
- Am I allowing a harmful path because it sounds helpful?
- Am I preserving the person's ability to choose and revise preferences?
- Am I protecting other individuals' consent and freedom?

The ideal support path is useful, individual-centered, non-coercive, and bounded by the Principle Prompt.
