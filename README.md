<h1 align="center">
📝 Awesome Long-CoT Data
</h1>
<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/awesome-dpo/Awesome-DPO-Papers?color=yellow&labelColor=555555) 
</div>

# Long CoT Data Generation Methods Survey

This project aims to summarize and survey various methods for generating Long CoT (Chain-of-Thought) data. Long CoT data plays a crucial role in complex task reasoning, multi-step problem-solving, and related fields. Below is an overview of the main methods, accompanied by tables for adding relevant paper links.

---

## Method Categories

### 1. **Prompt Engineering (PE) & Short CoT Composition for Long CoT**
* **2023.05** "Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models". [[Paper]](https://arxiv.org/abs/2305.04091)
* **2023.05** "LogiCoT: Logical Chain-of-Thought Instruction Tuning". [[Paper]](https://arxiv.org/abs/2305.12147)
* **2023.10** "Answering Questions by Meta-Reasoning over Multiple Chains of Thought". [[Paper]](https://aclanthology.org/2023.emnlp-main.364.pdf)
* **2024.01** "The Impact of Reasoning Step Length on Large Language Models". [[Paper]](https://aclanthology.org/2024.findings-acl.108.pdf)
* **2024.07** "Fine-Tuning with Divergent Chains of Thought Boosts Reasoning Through Self-Correction in Language Models". [[Paper]](https://arxiv.org/abs/2407.03181)[[Code]](https://github.com/UKPLab/arxiv2024-divergent-cot)
* **2024.09** "O1 Replication Journey: A Strategic Progress Report – Part 1". [[Paper]](https://arxiv.org/pdf/2410.18982)
* **2025.01** "KIMI K1.5:SCALING REINFORCEMENT LEARNING WITH LLMS". [[Paper]](https://arxiv.org/pdf/2501.12599v1)
* **2025.02** "Self-rewarding correction for mathematical reasoning". [[Paper]](https://arxiv.org/abs/2502.19613)
* **2025.02** "BOLT: Bootstrap Long Chain-of-Thought in Language Models without Distillation". [[Paper]](https://arxiv.org/abs/2502.03860)
* **2025.02** "Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning". [[Paper]](https://arxiv.org/abs/2502.08482)
* **2025.03** "START: Self-taught Reasoner with Tools". [[Paper]](https://arxiv.org/abs/2503.04625)

---

### 2. **Feedback & Critique LLM Regeneration**
* **2023.03** "Reflexion: Language Agents with Verbal Reinforcement Learning". [[Paper]](https://arxiv.org/abs/2303.11366)[[Code]](https://github.com/noahshinn/reflexion)
* **2023.05** "Improving Factuality and Reasoning in Language Models through Multiagent Debate". [[Paper]](https://arxiv.org/abs/2305.14325)[[Code]](https://github.com/composable-models/llm_multiagent_debate)
* **2023.05** "SELF-REFINE: Iterative Refinement with Self-Feedback". [[Paper]](https://arxiv.org/abs/2303.17651)
* **2024.05** "Self-reflection in llm agents: Effects on problem-solving performance". [[Paper]](https://arxiv.org/abs/2405.06682)
* **2024.05** "Large Language Models Can Self-Correct with Key Condition Verification". [[Paper]](https://arxiv.org/abs/2405.14092v3)[[Code]](https://github.com/wzy6642/ProCo)
* **2024.07** "DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning". [[Paper]](https://arxiv.org/abs/2407.04078)[[Code]](https://github.com/ChengpengLi1003/DotaMath)
* **2024.11** "Enhancing LLM Reasoning via Critique Models with Test-Time and Training-Time Supervision". [[Paper]](https://arxiv.org/abs/2411.16579)[[Code]](https://github.com/WooooDyy/MathCritique)

---

### 3. **RL-Based Deepseek Approach**
* **2024.01** "ReFT: Reasoning with Reinforced Fine-Tuning" [[Paper]](https://arxiv.org/abs/2401.08967)[[Code]](https://github.com/lqtrung1998/mwp_ReFT)
* **2024.12** "Offline Reinforcement Learning for LLM Multi-Step Reasoning
"[[Paper]](https://arxiv.org/abs/2412.16145)[[Code]](https://github.com/jwhj/OREO)
* **2025.01** "DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning"[[Paper]](https://arxiv.org/abs/2501.12948)[[Code]](https://github.com/deepseek-ai/DeepSeek-R1)
* **2025.01** "7B Model and 8K Examples: Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient". [[Paper]](https://hkust-nlp.notion.site/simplerl-reason)[[Code]](https://github.com/hkust-nlp/simpleRL-reason)
* **2025.01** "Open-R1: a fully open reproduction of DeepSeek-R1". [[Paper]](https://huggingface.co/blog/open-r1)[[Code]](https://github.com/huggingface/open-r1)
* **2025.01** "Clean, minimal, accessible reproduction of DeepSeek R1-Zero". [[Code]](https://github.com/Jiayi-Pan/TinyZero)
* **2025.02** "There May Not be Aha Moment in R1-Zero-like Training — A Pilot Study". [[Paper]](https://oatllm.notion.site/oat-zero)[[Code]](https://github.com/sail-sg/oat-zero?tab=readme-ov-file)
* **2025.02** "Demystifying Long Chain-of-Thought Reasoning in LLMs". [[Paper]](https://arxiv.org/abs/2502.03373)[[Code]](https://github.com/eddycmu/demystify-long-cot)
* **2025.02** "DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL". [[Paper]](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2)[[Code]](https://github.com/agentica-project/deepscaler)
* **2025.02** "Logic-RL: Unleashing LLM Reasoning with Rule-Based Reinforcement Learning". [[Paper]](https://arxiv.org/abs/2502.14768)[[Code]](https://github.com/Unakar/Logic-RL)
* **2025.02** "LIMR: Less is More for RL Scaling". [[Paper]](https://arxiv.org/pdf/2502.11886)[[Code]](https://github.com/GAIR-NLP/LIMR)
* **2025.03** "QwQ-32B: Embracing the Power of Reinforcement Learning". [[Paper]](https://qwenlm.github.io/blog/qwq-32b/)

---

### 4. **Knowledge Distill**
* **2024.11** "O1 Replication Journey – Part 2: Surpassing O1-preview through Simple Distillation Big Progress or Bitter Lesson?". [[Paper]](https://arxiv.org/pdf/2411.16489)
* **2024.12** "B-STaR: Monitoring and Balancing Exploration and Exploitation in Self-Taught Reasoners". [[Paper]](https://arxiv.org/abs/2412.17256)
* **2025.01** "RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems?". [[Paper]](https://arxiv.org/pdf/2501.11284)
* **2025.02** "Critique Fine-Tuning: Learning to Critique is More Effective than Learning to Imitate". [[Paper]](https://arxiv.org/abs/2501.17703)
* **2025.03** "Towards Widening The Distillation Bottleneck for Reasoning Models". [[Paper]](https://arxiv.org/abs/2503.01461)

---

## License
This project is licensed under the [MIT License](LICENSE).
