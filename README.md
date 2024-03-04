# AiRes
Ai4Researchers - Your Research assistant... Chat with your scientific document!
Follow this [link](https://drive.google.com/drive/folders/1D5eJtdLSYhUJ0dgnw1IMhDGQmNjO505t) for demo video 

# Introduction 
This presentation introduces an AI chatbot designed to assist researchers in answering research paper-related queries. The chatbot is capable of extracting text from various document formats, including PDF, DOCX, PPTX, and LaTeX, and provides intelligent responses based on the content.

# Tech Stack 
* Python: Core programming language for development.
* Streamlit: UI development tool for creating interactive web applications.
* PyPDF2, python-docx, pptx: Libraries for parsing and extracting text from document formats.
* pylatexenc: Library for converting LaTeX equations into human-readable text.
* PyTesseract: Optical character recognition (OCR) tool for extracting text from images.
* Transformers (Hugging Face): Library for natural language processing (NLP) tasks, including question-answering and image captioning.
* PyTorch: Deep learning framework for tasks such as image captioning using pre-trained models.
* NLTK: Toolkit for natural language processing tasks like tokenization and part-of-speech tagging.
* Aspose.Slides: Library for extracting images from PPTX files.
* OpenAI GPT-3: Language model for generating responses to user queries and conducting conversations.
* Langchain: Library for advanced text processing tasks such as text splitting, embeddings, and conversational chains.

# External Dependencies 
Ensure the following dependencies are installed externally:
* Tesseract OCR: Install Tesseract OCR for PyTesseract to work properly. (Install via: sudo apt install tesseract-ocr)
* TeX/LaTeX Distribution: Install a TeX/LaTeX distribution for pylatexenc (Find some help [here](https://www.tug.org/texlive/))

# Installation Instructions
1. Create a virtual environment with Python 3.9:
  * conda create -p venv python==3.9
2. Activate the virtual environment:
  * conda activate venv
3. Install the required Python packages using pip:
  * pip install streamlit pypdf2 langchain python-dotenv faiss-cpu openai huggingface_hub InstructorEmbedding sentence_transformers==2.2.2 tiktoken aspose.slides spire.pdf python-pptx python-docx
4. Install external dependencies:
  * sudo apt install tesseract-ocr ``

# Usage
