# AI-Augmented Agile MVP Development for Lean Tech Startups

**MS thesis, Software Project Management, FAST-NUCES · 2025–2026 · Muhammad Owais Mushtaq (sole author)**

- **Paper:** [DOI 10.21203/rs.3.rs-10346557/v1](https://doi.org/10.21203/rs.3.rs-10346557/v1) (Research Square preprint, CC BY 4.0)
- **Status:** under review at *Innovations in Systems and Software Engineering* (Springer)
- **Plain-language summary:** [Gist.Science](https://gist.science/paper/rs/rs-10346557)

---

## The problem

Lean tech startups often depend on a single product, so a late or low-quality Minimum Viable Product (MVP) can end the company. Even with Agile methods, small teams on tight budgets struggle to deliver on time and with quality. This study asks how generative AI can help these teams move faster without lowering quality.

## Method

The study follows **Design Science Research (DSR)**: identify a real problem, design an artefact that addresses it, then demonstrate and evaluate it in practice.

1. **Problem investigation:** semi-structured interviews with **18 industry practitioners** on why MVP delivery fails in resource-constrained teams.
2. **Artefact:** an AI-augmented Agile framework that assigns AI tools to each stage of delivery.
3. **Evaluation:** a live enterprise legacy-API migration (Jersey to Spring Boot), in two phases.

## The framework

| Agile stage | How AI is used |
|---|---|
| Inception and planning | Reading legacy code and estimating user-story effort |
| Implementation | Context-aware agents for multi-file migration and refactoring |
| Quality assurance | Generating test cases and edge cases |
| Code review | Automated review, followed by human verification |

## Findings

- **Planning:** user-story estimation took roughly half the time, while staying close to domain experts' estimates.
- **Implementation:** AI-assisted migration reached high accuracy in few iterations.
- **Quality:** AI-supported testing and review improved software quality.
- **Verification fatigue:** automated reviews raised many false alarms, so engineers shifted from writing code to auditing it. Human oversight stays essential, especially for architecture.

## Contribution

A practical, stage-by-stage guide for small teams that want to adopt AI in Agile delivery, grounded in practitioner evidence and tested on a real project.

## Limitations and future work

The evaluation covers one enterprise case. Next steps are more case studies across startups of different sizes and domains, and tracking how results change as AI tools evolve.
