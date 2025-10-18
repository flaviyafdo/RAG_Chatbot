## LangChain + Gemini AI Project

This project demonstrates how to build intelligent AI workflows using LangChain and Google’s Gemini models.
You can use it as a foundation for Retrieval-Augmented Generation (RAG), document question answering, or agent-based AI applications.

### Features

- Integration with Gemini 1.5 (via langchain-google-genai)
- Modular LangChain pipeline design
- Support for RAG (retrieval + generation)
- Extendable to AI Agents and memory-based chat
- Fully compatible with Jupyter Notebook or Python scripts

### Installation

- Make sure you have Python 3.10+ installed.
- Then install the required dependencies:

  `pip install langchain langchain-community langchain-google-genai`

- Optionally, install additional tools if you plan to work with PDFs or embeddings:

  `pip install langchain-text-splitters langchain-openai faiss-cpu pypdf`

### Environment Setup

- Get your Google API key from Google AI Studio
- Set it as an environment variable:

  `export GOOGLE_API_KEY="your_api_key_here"`

  or in Windows PowerShell:

  `setx GOOGLE_API_KEY "your_api_key_here"`

