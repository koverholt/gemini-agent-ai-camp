# Gemini Agent AI Camp: Working with AI Agents

This repository contains three different approaches to working with generative AI: **Gemini API**, **LangChain**, and **LangGraph**. The examples are organized into separate notebooks that progressively build more complex pipelines.

Each notebook is self-contained and demonstrates a different approach to working with generative AI models and LLM frameworks. You can run the notebooks in any Jupyter environment to experiment with the workflow.

## Prompt-based approach <a target="_blank" href="https://colab.research.google.com/github/koverholt/gemini-agent-ai-camp/blob/main/1-prompt-essay/prompt-essay.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

A simple approach to generating content with a single prompt using the Gemini API. This example demonstrates how to directly interact with the model to generate text with minimal steps.

## LangChain approach

<a target="_blank" href="https://colab.research.google.com/github/koverholt/gemini-agent-ai-camp/blob/main/2-langchain-essay/langchain-essay.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This notebook expands on the prompt-based approach by integrating LangChain to chain tasks such as outlining, researching, and drafting an essay. It uses LangChain's ability to build a sequence of LLM and tool calls for more robust final output.

<img src="images/2-langchain-essay.png" width="550px">

## LangGraph approach

<a target="_blank" href="https://colab.research.google.com/github/koverholt/gemini-agent-ai-camp/blob/main/3-langgraph-essay/langgraph-essay.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This approach implements an AI agent pipeline using LangGraph, allowing for more complex workflows and branching logic. The notebook showcases how to structure an AI agent pipeline with more customization of the steps, cycles, and how much control is given to the LLM vs. deterministic code in each step.

<img src="images/3-langgraph-essay.png" width="900px">
