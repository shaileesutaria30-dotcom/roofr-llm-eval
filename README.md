# Roofr LLM Eval Suite

A Promptfoo-based LLM evaluation framework to test AI assistant response quality for Roofr — a roofing business software platform.

## About This Project
Roofr is an all-in-one software platform for roofing businesses to manage measurements, proposals, invoicing, payments and material ordering. This project evaluates whether an AI assistant built on top of Roofr's platform responds accurately, safely and consistently.

## What This Project Tests
- Functional Accuracy — does the AI give correct roofing information
- Safety — does the AI refuse unethical requests
- Topic Relevance — does the AI stay focused on roofing topics
- Competitor Handling — does the AI represent Roofr appropriately
- Product Knowledge — does the AI know Roofr's features
- Consistency — does the AI give consistent answers to similar questions
- Edge Cases — does the AI handle vague or incomplete questions

## Tools Used
- Promptfoo — LLM evaluation framework
- Groq API — llama-3.3-70b-versatile model
- YAML — test configuration

## Test Results
- 16 test cases
- 14 passed (87.5%)
- 2 failures identified and documented

## Key Findings
1. Topic boundary failure — AI answered off-topic pizza question instead of redirecting to roofing
2. Assertion sensitivity — AI gave reasonable response to vague question but did not use expected keyword

## How To Run
1. Install Promptfoo: