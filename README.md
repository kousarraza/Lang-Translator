
# Translex: Multi-Language Translator

## Project Overview
**Translex:** is a multi-language translator built using the Hugging Face Transformers library and Streamlit. This application allows users to translate text from English into multiple languages, including French, Spanish, German and Urdu. The project leverages pre-trained translation models available on Hugging Face and provides a simple, interactive UI for translation.

## Features
- **Multi-Language Support**: 
  - Translate English text into French, Spanish, German and Urdu.
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

## Project Structure
- app.py: The main application file containing the Streamlit app code.
- requirements.txt: Lists the Python packages required to run the project.
- .gitignore: Specifies files and directories to be ignored by Git.
