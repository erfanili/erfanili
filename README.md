# Erfan Esmaeili

PhD student in Electrical & Computer Engineering at **Purdue University**, advised by Prof. Qiang Qiu.  
I work on **RL post-training of generative models**: designing rewards that capture what we want and optimizing toward them, first for diffusion models (ECCV 2026), now for LLMs.

**Seeking Research Scientist / Research Intern positions for Summer 2027.** U.S. Permanent Resident (no sponsorship required).

[Website](https://erfanili.dev) · [Google Scholar](https://scholar.google.com/citations?user=7cQiKTIAAAAJ) · [LinkedIn](https://www.linkedin.com/in/erfanili) · [Email](mailto:erfan.esmaeili.f@gmail.com)

---

### Research

- **Steering Diffusion Models via Class-Contrastive Influence for Few-Shot Medical Classification**  
  Jeeyung Kim, **Erfan Esmaeili**, Qiang Qiu. *ECCV 2026*  
  RL fine-tuning of diffusion models with an influence-based reward, so generated data measurably helps downstream classifiers.  
  [Paper](https://arxiv.org/abs/2607.12464)

- **Text Embedding is Not All You Need: Attention Control for Text-to-Image Semantic Alignment with Text Self-Attention Maps**  
  Jeeyung Kim\*, **Erfan Esmaeili\***, Qiang Qiu. *CVPR 2025* (\*equal contribution)  
  Training-free control of cross-attention using the text encoder's self-attention to fix attribute binding and missing objects.  
  [Paper](https://arxiv.org/abs/2411.15236) · [Project page](https://t-sam-diffusion.github.io/)· [Code](https://github.com/t-sam-diffusion/code)

- **In progress: reward design for RL post-training of LLM agents.** GRPO on multi-turn tool use: which rewards produce the behavior we want, and which get hacked?

---

### Engineering

| Project | What it is |
|---|---|
| [qlora-summarization](https://github.com/erfanili/qlora-summarization) | LoRA vs. QLoRA fine-tuning of Llama-3.2-1B on SAMSum with multi-GPU training; ROUGE-1 0.18 → 0.35 over the base model |
| [inference-optimization-benchmark](https://github.com/erfanili/inference-optimization-benchmark) | Benchmarking LLM serving (vLLM fp16 / AWQ / GPTQ) across batch sizes: latency, throughput, peak memory |
| [llm-quantization-eval](https://github.com/erfanili/llm-quantization-eval) | Accuracy, latency and memory of fp16 / int8 / int4 LLMs |

---

### Tools

PyTorch · Hugging Face (Diffusers, Transformers, PEFT) · vLLM · Accelerate / multi-GPU · Docker · Linux

Before ML: PhD in theoretical physics (IPM, Tehran).
