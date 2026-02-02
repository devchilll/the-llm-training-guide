# Resources: Post-Training & Alignment

> Curated learning materials organized by topic for building LLM training expertise.

---

## 📚 Training Playbooks & Guides

- [**Smol Training Playbook**](https://huggingface.co/spaces/HuggingFaceTB/smol-training-playbook) — HuggingFace's comprehensive guide to training small LLMs
- [**LLM Course**](https://github.com/mlabonne/llm-course) — Complete roadmap to LLM engineering by Maxime Labonne
- [**RLHF Book**](https://rlhfbook.com/) — Nathan Lambert's free book on RLHF

---

## 🏛️ Foundational Papers

### Transformers & Pre-training
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Original Transformer paper
- [GPT-3: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) — OpenAI's scaling paper
- [LLaMA](https://arxiv.org/abs/2302.13971) — Meta's efficient pre-training recipe

### RLHF & Alignment
- [InstructGPT (RLHF)](https://arxiv.org/abs/2203.02155) — OpenAI's original RLHF paper
- [Constitutional AI](https://arxiv.org/abs/2212.08073) — Anthropic's RLAIF approach
- [DPO: Direct Preference Optimization](https://arxiv.org/abs/2305.18290) — RL-free preference learning
- [KTO: Model Alignment as Prospect Theoretic Optimization](https://arxiv.org/abs/2402.01306) — Kahneman-Tversky optimization

### Reasoning & RL
- [DeepSeek-R1](https://arxiv.org/abs/2501.12948) — GRPO for reasoning models
- [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050) — Process reward models
- [STaR: Self-Taught Reasoner](https://arxiv.org/abs/2203.14465) — Bootstrapping reasoning

### Synthetic Data
- [Self-Instruct](https://arxiv.org/abs/2212.10560) — Generating instruction data
- [Evol-Instruct (WizardLM)](https://arxiv.org/abs/2304.12244) — Evolving instruction complexity
- [Orca 2](https://arxiv.org/abs/2311.11045) — Teaching small models to reason

### Infrastructure & Efficiency
- [LoRA](https://arxiv.org/abs/2106.09685) — Low-Rank Adaptation for efficient fine-tuning
- [S-LoRA](https://arxiv.org/abs/2311.03285) — Multi-tenant LoRA serving at scale
- [Flash Attention](https://arxiv.org/abs/2205.14135) — IO-aware exact attention
- [Speculative Decoding](https://arxiv.org/abs/2211.17192) — Accelerating LLM inference

---

## 🔧 Tools & Frameworks

### Fine-Tuning
- [**Unsloth**](https://github.com/unslothai/unsloth) — 2x faster LoRA with 70% less VRAM
- [**Axolotl**](https://github.com/OpenAccess-AI-Collective/axolotl) — YAML-driven training pipelines
- [**LLaMA-Factory**](https://github.com/hiyouga/LLaMA-Factory) — Web UI for fine-tuning
- [**TRL**](https://github.com/huggingface/trl) — HuggingFace's RLHF library
- [**mergekit**](https://github.com/arcee-ai/mergekit) — Model merging (TIES, DARE, SLERP)

### Inference & Serving
- [**vLLM**](https://github.com/vllm-project/vllm) — High-throughput serving with PagedAttention
- [**SGLang**](https://github.com/sgl-project/sglang) — Structured generation + RadixAttention
- [**llama.cpp**](https://github.com/ggerganov/llama.cpp) — CPU/edge inference with GGUF
- [**Ollama**](https://ollama.ai/) — Local model deployment made easy

### Training Optimizations
- [**Flash Attention**](https://github.com/Dao-AILab/flash-attention) — Memory-efficient attention
- [**DeepSpeed**](https://github.com/microsoft/DeepSpeed) — Distributed training at scale

### Evaluation
- [**lm-eval-harness**](https://github.com/EleutherAI/lm-evaluation-harness) — Standard benchmark suite
- [**BFCL**](https://gorilla.cs.berkeley.edu/leaderboard.html) — Berkeley Function Calling Leaderboard
- [**DeepEval**](https://github.com/confident-ai/deepeval) — LLM evaluation framework

---

## 🎓 Courses & Lectures

- [**Karpathy: Let's build GPT**](https://www.youtube.com/watch?v=kCc8FmEb1nY) — Build GPT from scratch (2hr)
- [**Karpathy: nanoGPT**](https://github.com/karpathy/nanoGPT) — Minimal GPT training code
- [**Stanford CS224N**](https://web.stanford.edu/class/cs224n/) — NLP with Deep Learning
- [**Full Stack LLM Bootcamp**](https://fullstackdeeplearning.com/llm-bootcamp/) — Production LLM engineering

---

## 📝 Technical Blogs

### OpenAI
- [ChatGPT](https://openai.com/index/chatgpt/) — Original ChatGPT announcement
- [GPT-4 Technical Report](https://openai.com/index/gpt-4-research/)
- [Scaling Laws](https://openai.com/index/scaling-laws-for-neural-language-models/)

### Anthropic
- [Claude's Character](https://www.anthropic.com/research/claude-character)
- [Core Views on AI Safety](https://www.anthropic.com/research/core-views-on-ai-safety)

### Others
- [Chip Huyen's Blog](https://huyenchip.com/blog/) — ML systems & LLM engineering
- [Sebastian Raschka](https://magazine.sebastianraschka.com/) — LLM fundamentals
- [Lil'Log (Lilian Weng)](https://lilianweng.github.io/) — Deep dives on RL, transformers

---

## 💬 Communities

- [**r/LocalLLaMA**](https://reddit.com/r/LocalLLaMA) — Local model running & fine-tuning
- [**Latent Space Podcast**](https://www.latent.space/) — AI engineering podcast
- [**HuggingFace Discord**](https://discord.gg/huggingface) — Model training discussions

---

## 📊 Model Hubs & Datasets

- [**HuggingFace Hub**](https://huggingface.co/models) — Model repository
- [**Open LLM Leaderboard**](https://huggingface.co/spaces/HuggingFaceh4/open_llm_leaderboard) — Model benchmarks
- [**Anthropic HH-RLHF**](https://huggingface.co/datasets/Anthropic/hh-rlhf) — Human preference data
- [**OpenAssistant**](https://huggingface.co/datasets/OpenAssistant/oasst2) — Conversation data
