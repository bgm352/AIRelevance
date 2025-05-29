# AI Relevance Tool

## Overview

This Streamlit app is designed for advanced SEO and content optimization using AI. It allows you to upload a CSV of search queries and their types, then queries multiple large language models (OpenAI GPT-4, Google Gemini, Anthropic Claude) for each query. The app collects and analyzes the responses, providing insights such as response quality, length, topic analysis, and type-specific metrics. Additionally, it supports extracting passages from URLs, scoring their semantic relevance to queries, and using AI to suggest improved, more relevant passages.

## Features

- **CSV Upload:** Accepts CSV files with `query` and `type` columns.
- **Multi-LLM Queries:** Supports querying OpenAI, Google Gemini, and Anthropic Claude (API keys required).
- **Response Analysis:** Measures quality, length, and success rates of LLM responses.
- **Type-Specific Insights:** Breaks down results by query intent (informational, transactional, etc.).
- **Passage Extraction:** Extracts and cleans passages from your and competitor URLs.
- **Semantic Scoring:** Vectorizes and scores passages for semantic relevance to the query.
- **AI Optimization:** Uses GPT-4 to suggest improved passages based on query and competitor content.
- **Visualizations:** Displays query type distributions and other analytics.

## Requirements

- **Python 3.8+**
- **Dependencies:**
  - streamlit
  - pandas
  - numpy
  - sentence-transformers
  - scikit-learn
  - plotly
  - nltk
  - requests
  - beautifulsoup4
  - openai
  - google-generativeai
