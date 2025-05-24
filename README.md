# Epishape

Epishape is a research suite for prototyping and evaluating **epistemically-informed reward shaping** in reinforcement learning. The goal is to explore how agents can:

- Represent uncertainty or belief about the environment
- Use epistemic assessments to modify reward-seeking behavior
- Learn more robust, interpretable, or aligned behaviors over time

## Experiments

1. **Cursed Gold (exp1)** – Agent collects gold with variable reward based on confidence about whether it is cursed.

More coming soon.

## Getting Started

```bash
pip install -r requirements.txt
python epishape/experiments/run_exp1_cursed_gold.py
