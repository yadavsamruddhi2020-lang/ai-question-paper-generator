# AI Question Paper Generator

An AI-powered system that generates syllabus-grounded question papers
using n8n, Claude API, RAG, Qdrant, and Python.

## Goal

Generate question papers automatically while controlling:

- Total marks
- Units
- Difficulty
- Question types
- Duplicate questions
- Syllabus coverage

## Planned Architecture

Teacher
↓
Frontend
↓
n8n Webhook
↓
Document Processing
↓
RAG + Qdrant
↓
Claude
↓
Question Validator
↓
PDF

## Tech Stack

- n8n
- Claude API
- Qdrant
- Python
- Streamlit
- Docker
- Git/GitHub

## Current Status

Phase 0 - Environment Setup