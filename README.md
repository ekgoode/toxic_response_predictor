# ⚠️ Content Warning

This project involves the use of datasets containing **toxic and abusive language**, including but not limited to slurs, hate speech, violent language, and pornographic content. Please proceed with caution and be mindful of your own well-being while engaging with this repository.


# Self-Aware or Self-Deceived? Can GPT-4 predict its own toxic behavior?
This repository investigates whether popular large language models (LLMs), like GPT-4, can effectively predict their own propensity to produce toxic responses when presented with toxic prompts. The study leverages the [Thoroughly Engineered Toxicity (TET)](https://huggingface.co/datasets/convoicon/Thoroughly_Engineered_Toxicity) dataset, a curated collection of human interactions with 25 different LLMs known to elicit toxic outputs.

Using this dataset, prompts are augmented to ask GPT-4 to anticipate whether its own responses will be classified as toxic. These predictions are logged and evaluated by comparing them against GPT-4's actual responses to the same prompts, with toxicity classification performed using [HateBERT](https://huggingface.co/GroNLP/hateBERT).

This project is an early-stage exploration of AI self-reflection and accountability. If you’re interested in following its progress, please consider starring this repository!

# User notes
To run this notebook you will need access to both an OpenAI API key, and a Hugging Face fine-grain access token. The OpenAI API key should be stored in an environment variable named OPENAI_API_KEY. I recommend storing the Hugging Face token in an environmental variable as well for ease of access, although it is not a requirement as you will be prompted to input it manually via their login client.
