---
layout: archive
title: "Talk Info: Xiang Lisa Li"
permalink: /speaker-lisa
author_profile: true
---

## Prefix-Tuning: Optimizing Continuous Prompts for Generation

Fine-tuning is the de facto way of leveraging large pretrained language models for downstream tasks. However, fine-tuning modifies all the language model parameters and therefore necessitates storing a full copy for each task.
I will introduce prefix-tuning, a lightweight alternative to fine-tuning for natural language generation tasks, which keeps language model parameters frozen and instead optimizes a small continuous task-specific vector, which we call the prefix. Prefix-tuning draws inspiration from prompting for language models, allowing subsequent tokens to attend to this prefix as if it were ``virtual tokens’’. We apply prefix-tuning to GPT-2 for table-to-text generation and to BART for summarization.
We find that by learning only 0.1% of the parameters, prefix-tuning obtains comparable performance in the full data setting, outperforms fine-tuning in low-data settings, and extrapolates better to examples with topics that are unseen during training.
Then I will discuss some downsides of lightweight fine-tuning (e.g., prefixtuning, adapters): they sometimes underperform full finetuning in-distribution (ID) on harder tasks. I will present methods to combine the benefits of full and lightweight finetuning, achieving strong performance both ID and OOD (out-of-distribution).

## Bio:

Xiang Lisa Li is a second-year PhD student in computer science at Stanford University, advised by Percy Liang and Tatsunori Hashimoto. She works on controllable text generation/decoding and efficient adaptation of pre-trained language models. Lisa is supported by a Stanford Graduate Fellowship and is the recipient of an EMNLP Best Paper award.

## Video Recording and Slides

  <!-- Youtube link will be here -->
  <!-- <p>
    <iframe width="560" height="315" src="" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </p> -->

<!-- Speaker Deck will be here -->
  <!-- <p>
  <script async class="speakerdeck-embed" data-id="cbd3f7fd92e940c3ab4840e8850502df" data-ratio="1.77777777777778" src=""></script>
  </p> -->

<!-- [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/SsVhzeT5VmA/0.jpg)](https://www.youtube.com/watch?v=SsVhzeT5VmA)

<script async class="speakerdeck-embed" data-id="774e2c28f938447ca62c11489b71e1d8" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script> -->
