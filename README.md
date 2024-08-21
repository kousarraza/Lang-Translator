
# Translex: Multi-Language Translator

## Project Overview
**LexoShift** is a multi-language translator built using the Hugging Face Transformers library and Streamlit. This application allows users to translate text from English into multiple languages, including French, Spanish, German, Urdu, and Sindhi. The project leverages pre-trained translation models available on Hugging Face and provides a simple, interactive UI for translation.

## Features
- **Multi-Language Support**: 
  - Translate English text into French, Spanish, German, Urdu, and Sindhi.
  - Easily extendable to other languages supported by Hugging Face models.
- **User-Friendly Interface**: 
  - Developed using Streamlit, offering an intuitive and interactive user interface.
  - Users can input text, select a target language, and receive translations instantly.
- **Modular and Scalable**: 
  - The project structure allows for easy addition of new languages and translation models.
  - The use of Hugging Face models ensures high-quality translations with minimal setup.

## Technical Stack
- **Programming Language**: Python
- **Key Libraries**:
  - `transformers`: For accessing pre-trained models and pipelines.
  - `torch`: For running models on the CPU or GPU.
  - `streamlit`: For creating the web-based user interface.
  - `sentencepiece`: Required for tokenization in certain models.

## Installation and Setup
To set up and run the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/lexoshift.git
   cd lexoshift
