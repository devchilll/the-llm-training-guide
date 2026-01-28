# Stage 4: Tool Use & Function Calling

> **Goal**: Build production-ready agents with structured outputs.

## Labs in this directory

| File | Description |
|------|-------------|
| `function_calling_sft.ipynb` | Schema-aware fine-tuning |
| `vllm_multi_lora.py` | Multi-adapter serving |
| `slora_multitenant.py` | Multi-tenant LoRA serving (private adapters) |

## Getting Started

1. Get [BFCL](https://gorilla.cs.berkeley.edu/leaderboard.html) data
2. Fine-tune for JSON function calling
3. Deploy with vLLM and test LoRA swapping
4. Implement multi-tenant isolation for private adapters

## Key Concepts

- **S-LoRA**: Serve thousands of private LoRA adapters with unified paging
- **Multi-tenant isolation**: Customer A's adapter never exposed to Customer B
- **Dynamic loading**: Hot-swap adapters per request without reloading base

## Success Criteria

- [ ] Model correctly calls functions with proper args
- [ ] Outperforms base model on domain schemas
- [ ] Can hot-swap LoRA adapters on vLLM
- [ ] Understand S-LoRA's multi-tenant architecture
