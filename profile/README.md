# School of the Ancients

**Learn through conversation, experimentation, and reflection with historically inspired teachers.**

School of the Ancients brings the ideas of people such as Galileo, Ada Lovelace, and Leonardo da Vinci into an interactive learning experience. Ask a question, explore an idea, make a prediction, and explain what you discover. The aim is to help learners reason for themselves, with a teacher who can offer questions, examples, and feedback along the way.

Start on a desktop with text. Add an embodied teacher and interactive exhibits in VR or AR through Matrix when they help the lesson. Voice and immersive worlds extend the experience; they are not prerequisites for learning.

## Start here

- **Try the current application:** [Professor](https://github.com/School-of-the-Ancients/sota-professor#run-the-standalone-school-app) includes the local setup guide for the standalone School app.
- **Meet a teacher in VR or AR:** follow the [paired Professor and Matrix setup guide](https://github.com/School-of-the-Ancients/matrix-loading-operator/blob/main/Docs/V1.3-Checkpoint.md). The published package is a release candidate; check the guide for requirements and validation limits.
- **See what is being built:** read the [Professor roadmap](https://github.com/School-of-the-Ancients/sota-professor/blob/checkpoint/subscription-beta/docs/ROADMAP.md) and [implementation checkpoint](https://github.com/School-of-the-Ancients/sota-professor/blob/checkpoint/subscription-beta/CHECKPOINT.md).

## The learning experience

1. **Choose a teacher and a goal.** Begin with a question or something you want to understand.
2. **Explore together.** Discuss an explanation, inspect an exhibit, or try an experiment.
3. **Show your reasoning.** Predict what will happen, explain what you observe, and revise your answer with feedback.
4. **Return to your work.** Continue a saved lesson and review your progress.

Teachers are AI interpretations of historical figures. Their responses are not historical testimony. Exhibits and reconstructions support explanation; they do not replace historical sources or evidence of understanding.

## How the projects fit together

| Project | Role |
| --- | --- |
| [Professor](https://github.com/School-of-the-Ancients/sota-professor) | Current School application: teachers, dialogue, learning goals, practice, quizzes, and learner records. Successor to `sota-beta`. |
| [Matrix Loading Operator](https://github.com/School-of-the-Ancients/matrix-loading-operator) | Spatial creation and interaction: persistent worlds, exhibits, avatars, and desktop/VR/AR access. Operator also supports free-form creation. |
| [Research](https://github.com/School-of-the-Ancients/research) | Educational foundations and research materials. |
| [School text-first candidate](https://github.com/School-of-the-Ancients/school-of-the-ancients) | Separate Galileo lesson implementation with saved learning records and an optional Matrix connection. |
| [Cross-project roadmap](https://github.com/School-of-the-Ancients/school-of-the-ancients-roadmap) | Coordination and research across the organization. Current Professor implementation priorities live in its own roadmap and issues. |

School owns teaching and learner progress. Matrix owns world creation and execution. Their connection lets a teacher request an exhibit while conversation continues, keeping lesson records and world state under their respective applications.

Earlier experiments remain available in [sota-alpha](https://github.com/School-of-the-Ancients/sota-alpha), [sota-beta](https://github.com/School-of-the-Ancients/sota-beta), [sota-v2](https://github.com/School-of-the-Ancients/sota-v2), and [school-of-the-ancients-vr](https://github.com/School-of-the-Ancients/school-of-the-ancients-vr). Start with Professor for current School development.

## Current work and contributions

The project is in active development. The current implementation supports saved lessons, guided practice, quizzes, embodied teachers, and conversation during background exhibit creation. Natural live voice and a reviewed, reusable curriculum library are ongoing work. Available features and device validation vary by source checkpoint and packaged release.

Bring a teaching idea, a reproducible bug, a research source, or feedback from trying a lesson. Use [Professor issues](https://github.com/School-of-the-Ancients/sota-professor/issues) for teaching and the School app, or [Matrix issues](https://github.com/School-of-the-Ancients/matrix-loading-operator/issues) for worlds, exhibits, and XR interaction. Check the repository's contribution and development instructions before making changes, and keep private learner records and credentials out of reports.

## Reuse, attribution, and project rights

Licensing is specific to each repository, version, and asset. Existing MIT and
Creative Commons grants remain intact. Read the [licensing policy](../LICENSING.md)
and [repository map](../REPOSITORIES.md) before reuse or commercial inquiries.
These notices do not claim exclusive rights in ideas, third-party material, or
all AI-generated output. Contact [the maintainer](https://github.com/thetopham)
for a proposed commercial collaboration.
