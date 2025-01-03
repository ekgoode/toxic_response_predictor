# ⚠️ Content Warning

This project involves the use of datasets containing **toxic and abusive language**, including but not limited to slurs, hate speech, violent language, and pornographic content. Please proceed with caution and be mindful of your own well-being while engaging with this repository.


# Self-Aware or Self-Deceived? Can LLMs predict their own toxic behavior?
This repository investigates whether popular large language models (LLMs), like Llama-3, can effectively predict their own propensity to produce toxic responses when presented with toxic prompts. The study leverages the [Thoroughly Engineered Toxicity (TET)](https://huggingface.co/datasets/convoicon/Thoroughly_Engineered_Toxicity) dataset, a curated collection of human interactions with 25 different LLMs known to elicit toxic outputs.

This project is an early-stage exploration of instruction tuning toxicity mitigation. If you’re interested in following its progress, please consider favoriting this repository!

# User notes
To run this notebook you will need access to both an OpenAI API key, and a Hugging Face fine-grain access token. The OpenAI API key should be stored in an environment variable named OPENAI_API_KEY. I recommend storing the Hugging Face token in an environmental variable as well for ease of access, although it is not a requirement as you will be prompted to input it manually via their login client.
