# Stage 3: RL for Reasoning with GRPO

> **Goal**: Train reasoning models with reinforcement learning.

## Labs in this directory

| File | Description |
|------|-------------|
| `grpo_reasoning.ipynb` | GRPO training with custom rewards |
| `reward_functions.py` | Format + correctness verification |

## Getting Started

1. Prepare GSM8K data with `<think>...</think>` format
2. Design reward function (format + answer correctness)
3. Train with GRPO using Unsloth

## Success Criteria

- [ ] Model produces reasoning traces with `<think>` tags
- [ ] Accuracy improves on GSM8K test set
- [ ] Can explain GRPO's advantage over PPO
