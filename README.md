# Kuwait IMF Report Analysis

**Module:** Data Analysis with AI – LLM  
**Country:** Kuwait  
**Dataset:** IMF 2025 Article IV Consultation Report

## Project Overview
This project analyses Kuwait's IMF Country Report using a local Large Language Model (LLM). It extracts financial indicators, summarises economic information, identifies financial risks and generates a dashboard.

## Models Used
1. **Qwen2.5-0.5B-Instruct** – Used for text summarisation, financial analysis, question answering and LLM evaluation.
2. **all-MiniLM-L6-v2** – Used to generate text embeddings for semantic retrieval with FAISS.

## Tools and Libraries
Python, Google Colab, PyMuPDF, Hugging Face Transformers, Sentence Transformers, FAISS, Pandas and Matplotlib.

## How to Run
1. Open the notebook in Google Colab.
2. Enable T4 GPU.
3. Upload the Kuwait IMF PDF.
4. Run all cells sequentially.
5. View the generated JSON files, evaluation results and dashboard.

## Main Outputs
- Economic section summaries
- Executive summary
- Structured financial indicators
- FAISS-based RAG question answering
- LLM evaluation results
- Four-panel economic dashboard

## Limitations
Some generated financial values and summaries may require verification against the original IMF report. The evaluation results should be interpreted with this limitation in mind.
