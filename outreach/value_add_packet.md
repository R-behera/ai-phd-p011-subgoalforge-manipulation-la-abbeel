# Professor Outreach Value-Add Packet

## Bottom Line

This repository is currently a **research proposal and execution scaffold**, not a completed result. Use it to show Professor Abbeel that you understand the research area and can contribute a concrete, reproducible artifact.

## Target Professor

- **Professor:** Pieter Abbeel
- **University:** University of California Berkeley
- **Program:** EECS / BAIR
- **Research area from CSV:** Robot learning, RL, imitation learning
- **Representative paper from CSV:** Apprenticeship Learning via Inverse Reinforcement Learning; 2004; ICML
- **Scholar link:** https://scholar.google.com/scholar?q=Apprenticeship+Learning+via+Inverse+Reinforcement+Learning

## Proposed Value Add

Build **a language-conditioned robot learning benchmark focused on progress, recovery, and generalization** focused on **Robot learning**.

### What You Can Contribute

- Define subgoal/progress labels for a small manipulation or embodied task suite.
- Compare behavior cloning or diffusion-policy baselines against progress-aware variants.
- Analyze when policies fail because they miss preconditions, recovery actions, or instruction grounding.

## Concrete Starter Project

Use simulation or public robot datasets to build a reproducible progress-state evaluation before attempting any real-robot work.

## 30/60/90-Day Plan

### First 30 Days

- Re-read 3-5 recent lab papers and write a one-page problem framing memo.
- Build the first dataset or evaluation slice with documented source provenance.
- Reproduce one credible baseline and record exact commands.
- Create a failure bank with at least 20 concrete examples.

### Days 31-60

- Add the proposed method or evaluation contribution.
- Run ablations that isolate the contribution from data scale and model-size effects.
- Add robustness, temporal, domain-shift, or subgroup tests where relevant.
- Write interim results as a short lab-note style report.

### Days 61-90

- Expand the benchmark to 50-100 examples or the equivalent for the domain.
- Run statistical checks, seed variance checks, and cost/runtime analysis.
- Convert results into a paper-style technical report.
- Package the repo so another student can reproduce the main table.

## Deliverables To Offer The Professor

- A task suite with language instructions, subgoal states, and failure labels.
- Baseline policy training/evaluation scripts.
- Generalization tests for unseen instructions or object layouts.
- A progress and recovery analysis report.

## Skills This Demonstrates

robot learning evaluation, imitation learning, offline RL protocol design, simulation-first experimentation.

## Honest Outreach Framing

Do **not** claim this is finished. The honest claim is:

> I prepared a concrete research scaffold aligned with your work and would like to turn it into a reproducible contribution if it matches your lab's current priorities.

## Sharing Note

This GitHub repository is private unless you change visibility. Before emailing, either make this selected repo public, invite the professor, or attach/export the one-page plan instead of sending a private link.
