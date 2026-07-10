# RecoverableRobot Learning Suite: Robot learning for Abbeel-Aligned Research

A professor-outreach research proposal aligned with **Pieter Abbeel** at **University of California Berkeley**.

## For Professor Outreach

This repo is intended to support an honest outreach email. It contains a concrete proposal for what value you can add, but it does **not** yet contain completed experiments or results.

Start here:

- `outreach/value_add_packet.md` - professor-specific contribution plan.
- `outreach/email_draft.md` - short mail draft you can personalize before sending.
- `docs/one_page_project_plan.md` - one-page project summary.
- `PROJECT_STATUS.md` - clear statement of what exists and what does not exist yet.

## Research Question

How can a focused, reproducible artifact around **Robot learning** create useful research infrastructure for a lab working on **Robot learning, RL, imitation learning**?

## Advisor Fit

- **Professor:** Pieter Abbeel
- **University:** University of California Berkeley
- **Program:** EECS / BAIR
- **CSV research area:** Robot learning, RL, imitation learning
- **Representative paper:** Apprenticeship Learning via Inverse Reinforcement Learning; 2004; ICML
- **Scholar link:** https://scholar.google.com/scholar?q=Apprenticeship+Learning+via+Inverse+Reinforcement+Learning

## Proposed Research-Grade Deliverable

Build **a language-conditioned robot learning benchmark focused on progress, recovery, and generalization** with:

- A task suite with language instructions, subgoal states, and failure labels.
- Baseline policy training/evaluation scripts.
- Generalization tests for unseen instructions or object layouts.
- A progress and recovery analysis report.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `outreach/value_add_packet.md` - value-add plan for this professor.
- `outreach/email_draft.md` - email draft; personalize before sending.
- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/one_page_project_plan.md` - one-page project summary.
- `docs/experiment_plan.md` - baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Proposal scaffold only. Before external use, verify the professor's current lab page and make a selected repo public or shareable.
