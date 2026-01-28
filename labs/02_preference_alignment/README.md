# Stage 2: Preference Alignment with DPO

> **Goal**: Learn from preferences without explicit reward models.

## Labs in this directory

| File | Description |
|------|-------------|
| `dpo_training.ipynb` | DPO implementation with TRL |
| `preference_data_creation.py` | Building triplet datasets |

## Getting Started

1. Prepare preference triplets: `(prompt, chosen, rejected)`
2. Use [Anthropic HH-RLHF](https://huggingface.co/datasets/Anthropic/hh-rlhf) or create your own
3. Follow the notebook to train with DPO

## Success Criteria

- [ ] Aligned model shows measurable behavior shift
- [ ] Win-rate vs. base model >60%
- [ ] Can derive the DPO loss from scratch
