---
title: "Enhancing Large Language Models for Scientific Multimodal Summarization with Multimodal Output"
collection: projects
type: "---"
permalink: /projects/Uni-SciSum
venue: ""
location: ""
---

<div align="center">

[![Code](https://img.shields.io/badge/code-GitHub-blue)](https://github.com/allent4n/Uni-SciSum)
[![Paper](https://img.shields.io/badge/paper--blue)](https://coling2025.org/)

</div>

---


This paper is accepted in [COLING-2025](https://coling2025.org/)

Uni-SciSum is a novel multimodal scientific summarisation model for multimodal output. Uni-SciSum aims to enable LLMs to effectively utilize textual, visual and auditoral content for scientific summarisation. Our model connects unimodal encoders to multimodal decoders via BridgeNet. During pretraining, the learnable queries in BridgeNet learn to extract modality-specific features from the encoders. During downstream tasks, the decoder generates embeddings based on different inputs and outputs (guided by the prompt and the learned queries), which the LLM then decodes into the target text summary and graphical abstract (GA).
<img width="1342" alt="framework_v3" src="https://github.com/user-attachments/assets/1fd2405f-2068-4679-abe9-3e2f5205cb6b" />


