# enterprise-llm-security-gateway
Enterprise AI Security Gateway using FastAPI, OpenAI, NVIDIA NIM and Google Gemma
# Enterprise LLM Security Gateway

Enterprise AI Gateway developed using FastAPI for securely routing requests to multiple Large Language Models.

## Features

- Prompt Injection Detection
- Content Safety Validation
- Microsoft Presidio PII Masking
- JWT Authentication
- PostgreSQL Logging
- Redis Caching
- Async FastAPI APIs
- OpenAI Integration
- NVIDIA NIM Integration
- Google Gemma Integration

## Tech Stack

Python
FastAPI
PostgreSQL
Redis
Docker
LangChain
Microsoft Presidio
JWT
OpenAI
Google Gemma
NVIDIA NIM

## Architecture

(Add your architecture diagram)

## Installation

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
