# Neurons Lab Intro to LLM Agents workshop

This is a workshop to introduce the concept of LLM agents and how to build them using the Langchain platform.
Hosted by [Neurons Lab](https://neurons-lab.com/) and led by me, [Alex Honchar](https://www.alexhonchar.com/).
Link to the YouTube recording will be here soon.

# Run in Google Colab

1. Planning and reasining [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1SplDwEIbVfo9zNt6JOK0gJlV0wCNuz0F?usp=sharing)
2. Different types of memories [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13b_pD27aqcNXYI2M7fBxK1fRIO2pygZJ?usp=sharing)
3. Various types of tools [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-VpwkmSvzA-zQ_iVK-xjOQf5kA-Lzwg9?usp=sharing)
4. Building complete agents [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()
# Project setup

You need to install the following libraries in a fresh .venv environment:

```
! pip install langchain
! pip install -U langchain-community tavily-python
! pip install --upgrade --quiet langchain-openai tavily-python
! pip install beautifulsoup4
! pip install faiss-cpu
! pip install langchainhub
! pip install -U wandb
```

Then, ensure that you have registered in the following services and got the API key stored in the configuration file:

- Tavily - [Langchain search tool](https://app.tavily.com/home)
- Langsmith - [LLM tracing tool](https://smith.langchain.com/)
- Weights&Biases - [MLOps / LLM tracing tool](https://wandb.ai/site)

LLMOps resources used for this tutorial: [LangSmith](https://github.com/langchain-ai/langsmith-cookbook/blob/main/hub-examples/retrieval-qa-chain-versioned/prompt-versioning.ipynb) and [Weights&Biases](https://docs.wandb.ai/guides/prompts/quickstart).