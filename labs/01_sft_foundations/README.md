# Stage 1: SFT Foundations

> **Goal**: Master supervised fine-tuning with LoRA on instruction datasets.

## Labs in this directory

| File | Description |
|------|-------------|
| `unsloth_sft_tutorial.ipynb` | 4-bit LoRA fine-tuning with Unsloth |
| `data_formatting.py` | Chat template utilities |

## Getting Started

1. Install [Unsloth](https://github.com/unslothai/unsloth)
2. Download `yahma/alpaca-cleaned` dataset
3. Follow the notebook to fine-tune Llama-3.2-1B

## Success Criteria

- [ ] Model follows instructions in target format
- [ ] Can explain LoRA's memory savings mathematically
- [ ] Loss plateaus appropriately (not overfitting)
