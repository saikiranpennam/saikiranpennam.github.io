---
title: "Mechanistic Interpretability of Vision-Language Models"
excerpt: "Fine-tuned Gemma 3 4B IT VLMs to study emergent misalignment; latent text-direction interventions and MMSafetyBench evaluation with vLLM. Manuscript accepted to InterpScience Workshop @ NeurIPS<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Research conducted at Algoverse (advisor: [PLACEHOLDER — advisor name]) on how narrow fine-tuning causes unsafe or misaligned behavior in vision-language models:

- Fine-tuned Gemma 3 4B IT VLMs on targeted datasets using Nvidia A100 GPUs to study emergent misalignment.
- Reproduced a latent intervention method for text representations, testing whether changing internal text-related directions reduces or induces misaligned behavior.
- Ran high-throughput inference with vLLM across many intervention, prompt, and model-output conditions.
- Evaluated with MMSafetyBench plus LLM-as-a-judge and human review to confirm effects were real, consistent, and not artifacts of flawed or out-of-distribution inputs.
- Compared text- and image-conditioned representations mechanistically; evidence showed text-direction interventions, not vision-direction interventions, were causally responsible for the observed misalignment.

Anonymous manuscript accepted to the InterpScience Workshop at NeurIPS; camera-ready in progress.
