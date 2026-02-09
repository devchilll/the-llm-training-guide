# Post-Training Colabs

Hands-on notebooks for fine-tuning small Language Models (SLMs) like **Qwen2.5-0.5B**. These experiments are designed to run on the **Google Colab Free Tier (T4 GPU)**.

## Contents

### 1. [SFT.ipynb](./SFT.ipynb) (Supervised Fine-Tuning)
- **Goal**: Teach the model *how* to solve problems step-by-step.
- **Dataset**: `openai/gsm8k` (Grade School Math).
- **Technique**: Full Fine-Tuning (or QLoRA).
- **Status**: ✅ Ready for training.

### 2. [DPO.ipynb](./DPO.ipynb) (Direct Preference Optimization)
- **Goal**: Align the model to prefer correct reasoning traces over incorrect ones.
- **Dataset**: `xinlai/Math-Step-DPO-10K` (Step-by-step verified reasoning).
- **Context**: Uses the SFT model as a base to improve reliability.

### 3. [GRPO.ipynb](./GRPO.ipynb) (Group Relative Policy Optimization)
- **Goal**: Reinforce reasoning capabilities using group sampling and verification (DeepSeek-R1 style).
- **Dataset**: `openai/gsm8k` (Questions only).
- **Technique**: Generates multiple distinct solutions and reinforces the ones that arrive at the correct final answer.
- **Reference**: Uses `DeepSeek-R1-Distill-Qwen-1.5B` as a teacher/reference.

### 4. [Qwen3_4B_GRPO.ipynb](./Qwen3_4B_GRPO.ipynb) (Advanced GRPO)
- **Goal**: Scale GRPO to a larger 4B model (Qwen3-4B-Base).
- **Technique**: Demonstrates **unsloth** memory optimizations to fit larger models on Colab T4.
- **Dataset**: `open-r1/OpenR1-Math-220k`.

### 5. [multi-turn-agent-tic-tac-toe.ipynb](./multi-turn-agent-tic-tac-toe.ipynb) (Agentic Tool Use)
- **Goal**: Train an agent to play Tic-Tac-Toe using function calling (tools).
- **Framework**: **OpenPipe ART** (Agent Reasoning & Training).
- **Concept**: Multi-turn conversation history + external state tracking.

## Usage
1. Open the notebook in Google Colab.
2. Select **Runtime > Change runtime type > T4 GPU**.
3. Run the cells!