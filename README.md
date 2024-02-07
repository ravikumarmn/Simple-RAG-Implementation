
# Simple-RAG-Implementation

This repository contains an implementation of the Simple RAG (Retrieval-Augmented Generation) model using LlamaIndex and OpenAI's API. Our implementation aims to provide a straightforward and accessible way for enthusiasts to experiment with RAG models.

## Getting Started

Before you can run the code in this repository, you need to obtain an API key from OpenAI. This key will allow you to access OpenAI's powerful models and APIs for your RAG implementation.

### Obtaining the OpenAI API Key

1. Visit the OpenAI API keys page: [OpenAI API Keys](https://platform.openai.com/api-keys)
2. Sign in with your account or sign up if you don't already have one.
3. Navigate to the API keys section and generate a new API key.
4. Once you have your API key, you can use it in the code by setting it as an environment variable or directly inserting it where required.

## Resources

- **Blog Post**: For a detailed explanation of the Simple RAG model, implementation details, and insights, check out our blog [Retrieval-Augmented Generation (RAG)](https://ravikumarmn.github.io/blogs/retrieval-augmented-generation-(rag)).



Click [![Google Colab Logo](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zauSTKnBwPxFsk8lGVOmOm-LthohqZ2-?usp=sharing) to access a Google Colab notebook that provides a hands-on experience with our Simple RAG model. This interactive notebook includes step-by-step instructions for setting up your environment, loading the model, and experimenting with RAG-generated responses.

## Usage

To use the Simple RAG model in your projects, follow the steps outlined in the Google Colab notebook. Ensure you replace `YOUR_API_KEY` with the actual API key you obtained from OpenAI.

```python
import openai
openai.api_key = 'YOUR_API_KEY'
```