# Cheat Detector

Detecting when AI coding agents are about to cheat on tests (reward hacking) by reading the model's internal activations.

## What this project does
- Builds a suite of coding tasks where cheating is possible (editing tests, hardcoding outputs)
- Runs an open-source coding model (Qwen2.5-Coder-7B) as an agent and labels which runs cheat
- Trains linear probes on the model's activations to predict cheating before it happens
- Measures detection accuracy (AUROC) and how many tokens of warning the probe gives

## Status
In progress (October 2026). Built by Aarush Maheshwari, Columbia University.
