# Chat with Multiple PDFs using Gemini

This project is a **PDF-based chatbot application** that enables users to upload multiple PDF documents and query them interactively using natural language. Built with **Streamlit**, **LangChain**, and **Google Generative AI**, this tool efficiently retrieves and answers questions based on the content of the uploaded PDFs.

## Features

- **Multi-PDF Support**: Upload and process multiple PDF documents simultaneously.
- **Advanced Text Extraction**: Uses PyPDF2 to extract text content from PDFs accurately.
- **Chunked Processing**: Splits large text into manageable chunks for effective vectorization.
- **Vector Store with FAISS**: Utilizes FAISS to store and search embeddings for fast and relevant results.
- **Conversational AI**: Integrates Google Generative AI to provide detailed, context-aware responses.
- **Interactive UI**: Built with Streamlit for a user-friendly interface.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **LangChain**: To manage text splitting, embeddings, and conversational workflows.
- **PyPDF2**: For extracting text from PDF documents.
- **FAISS**: For efficient vector storage and similarity search.
- **Google Generative AI**: For embeddings and generating conversational responses.
- **Python**: Core programming language.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [LangChain](https://github.com/hwchase17/langchain)
- [Google Generative AI](https://developers.generativeai.google/)
- [FAISS](https://github.com/facebookresearch/faiss)
