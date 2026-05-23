
# TalentCheck AI

TalentCheck AI is an AI-powered Resume Analyzer and Document Q&A system designed to help recruiters and candidates analyze resumes intelligently using NLP, embeddings, vector search, and LLMs.

## Features

- Resume Upload (PDF/DOCX)
- ATS Score Analysis
- Skill Extraction
- Semantic Resume Search
- AI-Based Resume Feedback
- Retrieval-Augmented Generation (RAG)
- Vector Database Search
- Natural Language Question Answering
- Semantic Matching for Recruiter Queries

## Architecture

```text
Resume Upload
      ↓
Text Extraction
      ↓
Chunking
      ↓
Embedding Generation
      ↓
Vector Database
      ↓
Semantic Retrieval
      ↓
LLM Response Generation
```

## Tech Stack

- Python
- FastAPI
- OpenAI API
- FAISS / Pinecone
- Sentence Transformers
- PyPDF2
- pdfplumber
- python-docx

## Retrieval Strategy

The system uses:
- Semantic Chunking
- Embedding-Based Retrieval
- Hybrid Search (Keyword + Vector Search)
- Top-K Retrieval
- Context Aggregation

## Biggest Challenge

One major challenge is retrieval miss, where relevant resume information exists but is not retrieved due to semantic mismatch.

### Mitigation
- Hybrid Retrieval
- Better Chunking
- Query Expansion
- Reranking Models

## Future Improvements

- Multi-resume comparison
- Recruiter dashboard
- Job-role matching
- Interview question generation
- Resume ranking system

## Author

Sandeep Gujjeti
