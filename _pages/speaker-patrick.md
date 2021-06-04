---
layout: archive
title: "Talk Info: Patrick Lewis"
permalink: /speaker-patrick
author_profile: true
---

Title:
PAQ: 65 Million Probably-Asked Questions and What You Can Do With Them

Abstract:
Open-Domain Question Answering is the task of answering natural language questions with short factual answers. These questions are not accompanied by evidence, and can be from an open set of domains. Models must understand questions, search for and assemble evidence necessary to answer the question, and then generate an answer.
Models which directly leverage question-answer (QA) pairs, such as closed-book QA (CBQA) models and QA-pair retrievers, show promise in terms of speed and memory compared to conventional models which retrieve and read from text corpora. QA-pair retrievers also offer interpretable answers, a high degree of control, and are trivial to update at test time with new knowledge. However, these models lack the accuracy of retrieve-and-read systems, as substantially less knowledge is covered by the available training QA-pairs relative to text corpora like Wikipedia. To facilitate improved QA-pair models, we introduce Probably Asked Questions (PAQ), a very large resource of 65M automatically-generated QA-pairs. We introduce a new QA-pair retriever, RePAQ, to complement PAQ. We find that PAQ preempts and caches test questions, enabling RePAQ to match the accuracy of recent retrieve-and-read models, whilst being significantly faster. RePAQ can be configured for size (under 500MB) or speed (over 1K questions per second) whilst retaining high accuracy. Lastly, we demonstrate RePAQ’s strength at selective QA, abstaining from answering when it is likely to be incorrect. This enables RePAQ to “back-off” to a more expensive state-of-the-art model, leading to a combined system which is both more accurate and 2x faster than the state-of-the-art model alone.



Papers covered by the talk: 

- Retrieval-augmented Generation for Knowledge-intensive NLP tasks: [https://arxiv.org/abs/2005.11401](https://arxiv.org/abs/2005.11401)
- Question and answer overlap in open domain QA :[https://arxiv.org/abs/2008.02637](https://arxiv.org/abs/2008.02637)
- PAQ: [https://arxiv.org/pdf/2102.07033.pdf](https://arxiv.org/pdf/2102.07033.pdf )

Some Background reading for interested folks
- [https://arxiv.org/abs/2002.08910](https://arxiv.org/abs/2002.08910)
- [https://arxiv.org/abs/2004.04906](https://arxiv.org/abs/2004.04906)
- [https://www.aclweb.org/anthology/P19-1612.pdf](https://www.aclweb.org/anthology/P19-1612.pdf)





Bio:
Patrick Lewis is a final year PhD student splitting his time between University College London and Facebook AI Research in London, supervised by Sebastian Riedel and Pontus Stenetorp. Patrick’s research interests center on Knowledge-intensive Natural Language Processing. His recent work has won Best Paper Awards at AKBC 2020 and EACL 2021, and he led a team which won 2 tracks of the EfficientQA competition at NeurIPS 2020. Patrick focuses on how to represent, store and access knowledge and building more powerful, efficient and robust models for knowledge-intensive NLP tasks such as Question Answering.

