# Vertex_AI_Gemini_API

## Overview
* **Gemini**
  * Gemini is a family of generative AI models developed by Google DeepMind that is designed for multimodal use cases. The Gemini API gives you access to the Gemini Pro and Gemini Pro Vision models.
* **Vertex AI Gemini API**
* The Vertex AI Gemini API provides a unified interface for interacting with Gemini models. There are two Gemini 1.0 Pro models available in the Gemini API:

  * Gemini 1.0 Pro model (gemini-1.0-pro): Designed to handle natural language tasks, multi-turn text and code chat, and code generation.
  * Gemini 1.0 Pro Vision model (gemini-1.0-pro-vision): Supports multimodal prompts. You can include text, images, and video in your prompt requests and get text or code responses.
  * You can interact with the Gemini API using the following methods:
    * Use Vertex AI Studio for quick testing and command generation
    * Use cURL commands
    * Use the Vertex AI SDK
* This notebook focuses on using the Vertex AI SDK for Python to call the Vertex AI Gemini API.

## Objectives

In this tutorial, you will learn how to use the Vertex AI Gemini API with the Vertex AI SDK for Python to interact with the Gemini 1.0 Pro (`gemini-1.0-pro`) model and the Gemini 1.0 Pro Vision (`gemini-1.0-pro-vision`) model.

You will complete the following tasks:

- Install the Vertex AI SDK for Python
- Use the Vertex AI Gemini API to interact with each model
  - Gemini 1.0 Pro (`gemini-1.0-pro`) model:
    - Generate text from text prompts
    - Explore various features and configuration options
  - Gemini 1.0 Pro Vision (`gemini-1.0-pro-vision`) model:
    - Generate text from image(s) and text prompts
    - Generate text from video and text prompts
