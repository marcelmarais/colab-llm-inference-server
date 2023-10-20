# Run an LLM inference server for free from a colab notebook

This notebook solves two problems I've been running into when using LLMs in colab notebooks:
1. Your LLM is contained within the notebook so any apps that need access to it also need to live in that environment.
2. Setting up an inference API & streaming requires a lot of boilerplate code.

I've found a way to solve these problems using Ollama and ngrok. At the end of the notebook you'll get an URL to your very own public inference server that supports generation and embedding with Orca-mini!
> This obviously shouldn't be used in any production environments

Notebook 🔗: https://lnkd.in/eYcGirze

(P.S: one of the benefits of using Ollama is that it's fully supported by LangChain 🎉)
