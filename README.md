# LLMs

This repository contains Jupyter Notebooks related to LLMs.  The rendered notebooks can be viewed at:

* [sft1.0](https://lzrdgreen.github.io/LLMs/sft1.0.html)
* [SFT](https://lzrdgreen.github.io/LLMs/SFT.html)
* [Adapters](https://lzrdgreen.github.io/LLMs/adapters.html)

To view a specific notebook, please, replace `sft1.0.html` in the URL with the desired filename (e.g., `the_notebook_name.html`).  All rendered notebooks are available in this directory.

Recently I saw a post on LinkedIn which reported that GRPOTrainer can be used for fine tuning on a dataset which, to my mind, was better suited for the usual Supervised Fine Tuning (SFT). I repreoduced 
both: [GRPOonTS2](https://lzrdgreen.github.io/LLMs/GRPOonTS2.html) and [SFTonTS](https://lzrdgreen.github.io/LLMs/SFTonTS.html). It turned out that the conventional SFT training resulted in significanly better perplexity value. However, the idea was worth exploring!

[GRPO fine-tuning of Gemma 3-1B-it](https://lzrdgreen.github.io/LLMs/GRPO_Gemma-3-1B.html), a tiny LLM, for improving its reasoning using GRPO on BBH 'causal_judgement' subset.

[LoRA on IMDB - various configurations](https://lzrdgreen.github.io/LLMs/LoRAonIMDB.html)
