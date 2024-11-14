# LLM OpenAI Notebook
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![GitHub Issues](https://img.shields.io/github/issues/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/issues)
[![GitHub Forks](https://img.shields.io/github/forks/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/network)
[![GitHub Stars](https://img.shields.io/github/stars/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/stargazers)

This repository contains Jupyter notebooks to explore and utilize OpenAI's Large Language Models (LLMs) for various applications, including chatbots, retrieval-augmented generation, text generation, prompt engineering, and vector embedding. These notebooks provide a comprehensive toolkit for working with OpenAI models in diverse contexts.

## Repository Structure

- **[OPENAI-CHAT.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI-CHAT.ipynb)**: Demonstrates the setup of a chatbot using OpenAI models, focusing on conversational interactions and response generation.
- **[OPENAI-RAG.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI-RAG.ipynb)**: Implements Retrieval-Augmented Generation (RAG), combining retrieval of relevant data with OpenAI model responses for context-aware answers.
- **[OPENAI-TEXTGEN.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI-TEXTGEN.ipynb)**: Focuses on text generation using OpenAI models, suitable for creative writing, content creation, and informative text outputs.
- **[OPENAI_PROMPTING.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI_PROMPTING.ipynb)**: Provides methods and techniques for effective prompt engineering, demonstrating how to optimize prompts to guide model behavior.
- **[OPENAI_REFERENCE_RAG.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI_REFERENCE_RAG.ipynb)**: An advanced notebook on Retrieval-Augmented Generation that includes reference material integration for highly accurate responses.
- **[OPENAI_VECTOR_EMB.ipynb](https://github.com/simonpierreboucher/llm_openai_notebook/blob/main/OPENAI_VECTOR_EMB.ipynb)**: Explores vector embeddings with OpenAI models, showcasing how to use embeddings for similarity search, clustering, and other applications in natural language processing.

## Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Python 3.8+**
- **Jupyter Notebook**
- Dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher/llm_openai_notebook.git
   cd llm_openai_notebook
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Open Jupyter by navigating to the repository folder and running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open any of the notebooks to explore functionalities such as chat, RAG, or text generation.
3. **Follow Instructions**: Each notebook contains instructions and steps for interacting with OpenAI models in the respective application.

## Use Cases

- **Chatbot Development**: With `OPENAI-CHAT.ipynb` and `OPENAI_PROMPTING.ipynb`, you can create and optimize a conversational agent.
- **Information Retrieval**: Use `OPENAI-RAG.ipynb` and `OPENAI_REFERENCE_RAG.ipynb` for applications that require accurate, source-grounded responses.
- **Content Creation**: `OPENAI-TEXTGEN.ipynb` provides tools for generating creative or informational content.
- **Embedding and Similarity Search**: `OPENAI_VECTOR_EMB.ipynb` is ideal for NLP tasks involving similarity matching, clustering, and more.

## Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance the functionality, add features, or fix bugs.

## License

This repository is licensed under the MIT License.
