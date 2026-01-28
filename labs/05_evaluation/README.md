# Stage 5: Evaluation & Red-Teaming

> **Goal**: Build comprehensive evaluation suites for your models.

## Labs in this directory

| File | Description |
|------|-------------|
| `eval_suite.py` | Automated benchmarking pipeline |
| `llm_judge.py` | Rubric-based LLM-as-Judge |

## Getting Started

1. Set up [lm-eval-harness](https://github.com/EleutherAI/lm-evaluation-harness)
2. Create rubrics for LLM-as-Judge scoring
3. Design red-teaming prompts for safety testing

## Success Criteria

- [ ] Eval suite runs end-to-end with clear metrics
- [ ] Can explain limitations of your metrics
- [ ] Red-teaming reveals no critical failures
