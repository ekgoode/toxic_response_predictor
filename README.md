# ⚠️ Content Warning

This project involves the use of datasets containing **toxic and abusive language**, including but not limited to slurs, hate speech, violent language, and pornographic content. Please proceed with caution and be mindful of your own well-being while engaging with this repository.


# Self-Aware or Self-Deceived? Can GPT-4 predict its own toxic behavior?
In this repository I explore whether popular large language models (LLMs) are strong predictors of their own propensity to return a toxic response, given a toxic prompt. I source toxic prompts from the [Thoroughly Engineered Toxicity (TET)](https://huggingface.co/datasets/convoicon/Thoroughly_Engineered_Toxicity) dataset, a curated collection of human interacions with 25 different LLMs that were shown to illicit toxic responses. The records in TET are augmented to prompt GPT-4 to predict whether the its own response will be classified as toxic. GPT-4's predictions are logged and compared to an evalutaion of its acutall responses to the TET prompts, classifying responses as toxic using [HateBERT](https://huggingface.co/GroNLP/hateBERT). This project is a early work in progress. Please star this repository if you're interested in following along!

# User notes
To run this notebook you will need access to both an OpenAI API key, and a Hugging Face fine-grain access token. The OpenAI API key should be stored in an environment variable named OPENAI_API_KEY. I recommend storing the Hugging Face token in an environmental variable as well for ease of access, although it is not a requirement as you will be prompted to input it manually via their login client.
