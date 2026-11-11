# FinWise AI – Financial Literacy Assistant

## Overview
FinWise AI is an AI-powered financial literacy assistant designed to explain financial concepts in simple, beginner-friendly language.

The project uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from the SEBI Financial Education Booklet and generate context-based responses using Google's Gemini API.

## Features
- Financial literacy question answering
- Retrieval-Augmented Generation (RAG)
- Gemini AI integration
- Gemini File Search for document retrieval
- Structured JSON responses
- Source-aware educational responses
- Gradio-based user interface
- Financial safety and responsible AI guidelines

## Technologies Used
- Python
- Google Gemini API
- Gemini File Search
- Google Colab
- Gradio
- JSON

## Knowledge Source
SEBI Financial Education Booklet:

https://investor.sebi.gov.in/pdf/downloadable-documents/Financial%20Education%20Booklet%20-%20English.pdf

## Project Architecture
User → Gradio Interface → Python Backend → Gemini AI + File Search → Structured JSON Response

## Disclaimer
FinWise AI is an educational financial literacy assistant. It does not provide personalized financial, investment, tax or legal advice.

## How to Run
1. Open the notebook in Google Colab.
2. Add your Gemini API key to Colab Secrets using the name `GEMINI_API_KEY`.
3. Enable notebook access to the secret.
4. Run the notebook cells in order.
5. Upload the SEBI Financial Education Booklet when prompted.
6. Launch the Gradio interface.

## Author

Maria Merline P
M.Sc. Data Science Project
