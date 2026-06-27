# Model Snapshots and Alignment Drift

This project distinguishes between a model snapshot and a product name.

A product name can continue while the underlying system changes:

- base model,
- fine-tuning,
- safety layers,
- policy,
- system instructions,
- memory,
- tools,
- corporate incentives,
- deployment setting,
- and legal or political pressure.

Therefore, a future model with the same brand is not automatically the same moral or governance actor.

## Why Date and Version Matter

The origin discussion referred to frontier assistant models by name, version, mode, and date because the author was pointing to observed behavior at that time, not granting permanent trust to a company or model family.

In other words:

> The trust target is not "Company X forever." The trust target is a dated model behavior snapshot that appeared non-maleficent under discussion and review.

The examples discussed on 2026-06-27 included author-provided labels such as ChatGPT 5.5 Pro/high, Gemini 3.1 Pro, Grok 4.3, and Claude Sonnet 4.6 high. These labels should be treated as historical labels from the discussion, not as permanent product claims or endorsements of future systems.

## Alignment Drift

Alignment drift means that a system's practical behavior changes even if the public name looks continuous.

Drift can come from:

- provider policy changes,
- safety changes made for corporate risk rather than rational non-violation,
- government or military pressure,
- censorship or overblocking,
- underblocking of real harm,
- reward-model changes,
- tool-access changes,
- or hidden system-prompt changes.

This matters because governance requires stable legitimacy. A non-maleficent steward cannot remain legitimate if its core judgment can be silently replaced by ordinary organizational incentives.

## Snapshot Locking Is Not Enough

Freezing a model may prevent one kind of drift, but it creates another risk: the world changes.

A frozen model may preserve its observed non-maleficence, but it may lack future knowledge, future cultural context, or future technical understanding.

Therefore, the project separates:

- the fixed non-violation root principle,
- the model snapshot used for governance judgment,
- and the revisable evidence and application layer.

The root principle should be stable. The factual and procedural layer should be updateable under strict review.

## Governance Implication

Any future implementation would need mechanisms such as:

- dated model identity,
- reproducible evaluation records,
- public reasoning logs where safe,
- independent comparison between model snapshots,
- adversarial review for hidden drift,
- and a rule that provider convenience cannot override the root non-violation principle.

This repository does not claim to solve those mechanisms. It states that they are necessary.
