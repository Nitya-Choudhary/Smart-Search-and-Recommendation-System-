# Smart Search & Recommendation Engine

## Overview
A DSA-powered search engine with autocomplete, spell correction, trending suggestions, and semantic similarity search. Built with Python (FastAPI), React, Tailwind, and optional ML embeddings.

## Features
- **Autocomplete**: Efficient Trie-based prefix search
- **Spell Correction**: Levenshtein distance DP
- **Trending Search**: Top-k frequent searches using heap
- **Similar Items**: Cosine similarity for semantic search
- **Frontend**: React + Tailwind UI with live suggestions

## Tech Stack
- **Backend**: Python, FastAPI
- **Frontend**: React, TailwindCSS
- **Optional ML Layer**: Cosine similarity / sentence embeddings

## Installation

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload --port 8000
