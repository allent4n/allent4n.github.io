---
title: "Enhancing Large Language Models for Scientific Multimodal Summarization with Multimodal Output"
collection: projects
type: "---"
permalink: /projects/Uni-SciSum
venue: ""
location: ""
---

*COLING-2025*

<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://github.com/allent4n/Uni-SciSum" target="_blank" style="text-decoration: none;">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="40" height="40" style="vertical-align: middle; margin-right: 10px;">
    <span style="font-size: 18px; color: #000;">Visit the GitHub Repository</span>
  </a>
</div>

Uni-SciSum is a novel multimodal scientific summarisation model for multimodal output. Uni-SciSum aims to enable LLMs to effectively utilize textual, visual and auditoral content for scientific summarisation. Our model connects unimodal encoders to multimodal decoders via BridgeNet. During pretraining, the learnable queries in BridgeNet learn to extract modality-specific features from the encoders. During downstream tasks, the decoder generates embeddings based on different inputs and outputs (guided by the prompt and the learned queries), which the LLM then decodes into the target text summary and graphical abstract (GA).

<img width="1342" alt="framework_v3" src="https://github.com/user-attachments/assets/1fd2405f-2068-4679-abe9-3e2f5205cb6b" />


