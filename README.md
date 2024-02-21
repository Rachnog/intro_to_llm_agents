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