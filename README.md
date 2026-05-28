# CAFI — Cultural Fidelity Evaluation for AI Assistants

CAFI is a framework for evaluating whether AI assistants respond faithfully inside a cultural, linguistic, and social context.

Most AI evaluation asks whether a model is factually correct, helpful, or safe. Those questions matter, but they are not enough for cultural AI assistants. A model can know cultural facts and still answer in a way that sounds unnatural, uses the wrong social tone, misses local expectations, or behaves incorrectly for the assistant role.

CAFI focuses on open-text assistant behavior. It asks whether an answer fits the user's language, role, relationship, situation, and practical needs — not only whether it contains correct cultural information.

Soztaz (Kazakh: Сөзтас), a Kazakh cultural AI assistant, is the first reference implementation where this evaluation problem became visible. CAFI itself is intended as an independent evaluation framework for cultural AI systems more broadly, especially in low-resource and culturally rich language settings.

The current work is at the position-paper and validation-design stage. Public materials may describe the problem, the high-level framework idea, and the planned validation approach. Operational evaluation details are not released.

## What CAFI is for

CAFI is intended to support:

- private development review of cultural AI assistants;
- clearer methodology for cultural-fidelity evaluation;
- structured human review by native speakers and domain-sensitive reviewers;
- future calibrated comparison of cultural AI systems, after validation boundaries are clear;
- low-resource language evaluation where generic English-first benchmarks miss important cultural and linguistic failures.

## What CAFI is not

CAFI is not a single score that declares one model "the best".

It should not be used to:

- rank models publicly before calibrated human validation;
- replace native-speaker, cultural, legal, or domain judgment;
- claim that any system is globally superior based on early internal checks;
- reduce cultural meaning to one hidden number;
- copy one cultural reference design blindly into every language or community.

CAFI is best understood as a structured evaluation framework: it helps reviewers see cultural-fidelity failures more clearly, but it does not replace human cultural authority.

## Current status

CAFI is currently a framework proposal and validation design, not a completed public benchmark.

What exists now:

- a private position-paper draft;
- a high-level framework for cultural-fidelity evaluation;
- a role-conditioned evaluation idea;
- a planned human-calibration path;
- a clear boundary around what remains private.

What does not exist yet as public-grade evidence:

- completed calibrated human validation;
- public leaderboard;
- publication-grade cross-model ranking;
- public raw dataset;
- final release protocol.

Safe wording for the current stage:

> CAFI proposes a framework and validation design for cultural-fidelity evaluation in AI assistants.

Unsafe wording for the current stage:

> CAFI proves that system X is better than system Y.

## Release boundary

Future public materials based on this README should remain high-level. Operational evaluation details and private validation materials are not released at this stage.

Future releases should be staged. Early public materials should explain what CAFI is and is not. More detailed materials should appear only after validation scope, reporting rules, and safety boundaries are clear.

## Relationship to Soztaz

Soztaz is the first reference implementation for CAFI: the practical cultural AI assistant environment where the evaluation problem became concrete.

CAFI is the measurement framework that emerged from that problem. It should not be understood as a product feature limited to Soztaz. The longer-term goal is to develop CAFI as a reusable framework for evaluating cultural AI assistants across languages and communities.
