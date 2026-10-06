# SandBase Lab Guide

**Open-source agent experiments, from prototype to production.**

[中文](README.zh-CN.md) · [Project standard](docs/project-standard.md) · [Contribute](CONTRIBUTING.md)

SandBase Lab connects models, real-world APIs, and sandboxes in independent open-source agent projects. Start from a visible result, reproduce the workflow, adapt it, and validate it for production.

## Choose your path

| Your goal | Start here |
| --- | --- |
| Understand the collection | [Getting started](docs/getting-started.md) |
| Find an agent project | [Project directory](#project-directory) |
| Propose a new experiment | [Open a lab proposal](https://github.com/sandbase-lab/lab-guide/issues/new?template=lab-proposal.md) |
| Publish a reproducible project | [Project standard](docs/project-standard.md) and [README template](docs/project-readme-template.md) |
| Prepare a prototype for production | [Production checklist](docs/production-checklist.md) |

## Project directory

The collection is launching. No runnable agent project has been published yet. Each validated application will have an independent repository with setup, example inputs, evaluations, cost notes, and deployment guidance.

| Candidate direction | Expected artifact | Status |
| --- | --- | --- |
| Research Agent | A research report with sources | Proposed; not implemented |
| Content Agent | A package of copy and images | Proposed; not implemented |
| Data Analysis Agent | Charts and an analysis report | Proposed; not implemented |

Published entries will include repository, maturity stage, preview, setup instructions, service dependencies, cost evidence, maintainer, and last validation date.

## How a lab evolves

Experiment → reproducible prototype → evaluation → deployment and operations.

Projects declare **Experimental**, **Preview**, or **Production-ready** based on documented evidence. See the [stage requirements](docs/project-standard.md). Independent repositories own their dependencies, releases, and maintenance.

## Open source and service costs

This guide is licensed under [Apache-2.0](LICENSE). Other projects declare their own licenses. SandBase and third-party service access and usage charges are separate from the code license; fixtures or mock mode should allow initial exploration without paid calls.

## Contribute

Bring a real task, a reproducible result, a failure case, or a production lesson. Follow [CONTRIBUTING](CONTRIBUTING.md); organization membership is not required.

Initiated and maintained by [SandBase](https://www.sandbase.ai/).
