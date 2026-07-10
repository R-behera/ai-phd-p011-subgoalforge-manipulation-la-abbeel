# Unique Prototype Algorithm

## Algorithm

**AbbeelRobustRobotLearningScoreAgent** (`P011-Abbeel-RobotLearning`)

## Professor Alignment

- Professor: Pieter Abbeel
- Research area: Robot learning, RL, imitation learning
- Focus terms: Robot learning, RL, imitation learning

## Core Mechanism

This prototype prioritizes trajectory steps where progress estimates diverge from expected subgoals.

## Decision Rule

Rank seed cases by robotics-specific priority score with Abbeel-aligned focus term 'Robot learning'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `robotics` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Pieter Abbeel's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
