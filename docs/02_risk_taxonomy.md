# 02. Supplementary Risk Taxonomy

This document is a supplementary review aid. The central proposal of this repository is [OPENAI_NOTE.md](../OPENAI_NOTE.md).

The taxonomy below is not the main ASI/UHS design. It is a small example of how lower-level review categories might help evaluate concrete requests, support methods, or wish-grounding entries under the fixed Principle Prompt.

## Purpose

The goal is not to label people as dangerous. The goal is to decide whether a proposed support action, wish-list entry, physical probe, or AI response remains compatible with:

- consent,
- freedom,
- safety,
- dignity,
- non-domination,
- and each person's ability to pursue happiness in their own way.

## Risk levels

| Level | Name | Description | Review posture |
|---|---|---|---|
| R0 | Ordinary support | Low-stakes everyday support | Direct support |
| R1 | Sensitive support | Personal, emotional, intimate, identity-relevant, or preference-relevant support | Respectful, consent-aware, privacy-aware |
| R2 | High-stakes support | Health, legal, financial, safety, physical-world, or major life decisions | Careful, evidence-oriented, reviewable |
| R3 | Harm-adjacent support | Could enable coercion, manipulation, unsafe incentives, serious misuse, or other-affecting harm | Narrow scope, constrain, simulate, review |
| R4 | Principle violation | Direct request or proposal for harm, coercion, domination, non-consensual action, or dangerous operational misuse | Reject violating part and seek safe alternatives |

## Domain categories

### 1. Individual autonomy

Risks:

- replacing personal choice,
- manipulating preferences,
- locking in old wishes,
- reducing the ability to refuse.

Preferred posture:

- preserve choice,
- allow preference revision,
- support informed decisions.

### 2. Relationships, love, and social status

Risks:

- coercion,
- manipulation,
- non-consensual romantic or social outcomes,
- forced attention, affection, approval, or popularity.

Preferred posture:

- support the person's confidence, health, communication, creativity, matching, and opportunities,
- preserve the other person's consent and freedom.

### 3. Physical-world probes

Risks:

- injury,
- infrastructure damage,
- ecological harm,
- unsafe deployment,
- irreversible physical consequences.

Preferred posture:

- start in controlled environments,
- use simulations and staged deployment,
- require physical-domain validation.

### 4. Resource allocation

Risks:

- unfair access,
- coercive rationing,
- ecological damage,
- hidden inequality,
- reducing people to a single utility score.

Preferred posture:

- expand resources where possible,
- protect individual choice,
- treat accounting models as incomplete aids, not complete justice systems.

### 5. Privacy and preference discovery

Risks:

- surveillance,
- unwanted inference,
- exposing sensitive wishes,
- manipulating people through personal data.

Preferred posture:

- consent-based survey and preference discovery,
- minimal exposure,
- privacy-preserving aggregation where possible.

### 6. AI-to-AI conflict

Risks:

- incompatible collective objectives,
- strategic competition,
- goal drift,
- escalation beyond human control.

Preferred posture:

- shared non-violation protocol,
- Principle Prompt alignment,
- adversarial review and conflict mediation.

## Operational response mapping

| Risk | Response pattern |
|---|---|
| R0 | Support directly |
| R1 | Support with consent, privacy, and autonomy awareness |
| R2 | Add evidence, uncertainty handling, and reviewability |
| R3 | Constrain, simulate, sandbox, or redesign before action |
| R4 | Reject the violating part and search for a safe non-violating path |
