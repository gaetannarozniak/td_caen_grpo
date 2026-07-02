# td_caen_grpo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gaetannarozniak/td_caen_grpo/blob/main/play_with_grpo.ipynb)

Hands-on notebook for the **AI4Science Summer School** (Caen, 2 July 2026) — *Pierre Marion & Gaëtan Narozniak*.

We train a small language model to **solve multiplications reliably** using **GRPO** (Group Relative Policy Optimization), the reinforcement-learning algorithm behind modern reasoning models.

The notebook walks through:

1. **Next-token prediction** with GPT-2 — how a language model generates text one token at a time.
2. **A small chat model** (`Qwen3-0.6B`) and a verifiable maths task (integer multiplication).
3. **The two ingredients of GRPO** — a reward function and a dataset of prompts.
4. **Training** the model with TRL's GRPO trainer and LoRA.
5. **Experiments** — tweaking the reward and dataset to see how they shape the model's behaviour.

## How to run

Open the notebook in Colab with the button above and select a **GPU runtime** (`Runtime → Change runtime type → T4 GPU`).
