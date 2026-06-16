# FreightMind — AI Freight Document Parser

An AI-powered tool that extracts structured data from
messy freight documents using the Claude API.

## What it does
- Accepts unstructured freight documents (invoices,
  bills of lading, carrier emails)
- Sends document to Claude AI API with prompt engineering
- Extracts structured JSON data automatically
- Shows confidence scoring and field-by-field results
- Outputs clean JSON record ready for database storage

## Tech used
Claude API · Prompt Engineering · HTML · CSS · 
Vanilla JavaScript

## How it works
1. User pastes any messy freight document
2. Selects which fields to extract
3. JavaScript sends document + prompt to Claude API
4. Claude returns structured JSON
5. UI renders results field by field with confidence score

## Why I built this
Demonstrates LLM integration for real-world logistics
data extraction — directly mirrors how platforms like
Loop structure supply chain data using AI.

## Author
Harsha Vardhan Repudi
GitHub: https://github.com/HarshaVardhanRepudi
