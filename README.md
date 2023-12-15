# Overview
A conceptual understanding of Reinforcement Learning from Human Feedback (RLHF), as well as the datasets needed for this technique
Fine-tune the Llama 2 model using RLHF with the open source Google Cloud Pipeline Components Library
Evaluate tuned model performance against the base model with evaluation methods


Large language models (LLMs) are trained on human-generated text, but additional methods are needed to align an LLM with human values and preferences.
Reinforcement Learning from Human Feedback (RLHF) is currently the main method for aligning LLMs with human values and preferences. RLHF is also used for further tuning a base LLM to align with values and preferences that are specific to the use case.  

In this course, I gained a conceptual understanding of the RLHF training process, and then practice applying RLHF to tune an LLM.
- Explore the two datasets that are used in RLHF training: the “preference” and “prompt” datasets.
- Use the open source Google Cloud Pipeline Components Library, to fine-tune the Llama 2 model with RLHF.
- Assess the tuned LLM against the original base model by comparing loss curves and using the “Side-by-Side (SxS)” method.
