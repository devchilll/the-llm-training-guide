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

## Usage
1. Open the notebook in Google Colab.
2. Select **Runtime > Change runtime type > T4 GPU**.
3. Run the cells!