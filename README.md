# Resume Review Agentic System with CrewAI

## Overview
An AI-powered system that automates resume review, enhancement, and job matching using CrewAI's multi-agent framework.

## Features
- **Resume Analysis**: Extracts and analyzes resume content from PDF/DOCX files
- **AI Feedback**: Provides detailed resume improvement suggestions with scoring
- **Resume Optimization**: Rewrites resumes to highlight key qualifications
- **Job Matching**: Finds relevant job openings based on skills and location
- **Modular Architecture**: Easily extendable with additional agents

## How It Works
1. **Input**: User uploads resume (PDF or DOCX) and specifies location preference
2. **Processing**:
   - Text extraction from resume files
   - Multi-agent analysis through CrewAI framework
3. **Output**:
   - Scored resume feedback
   - Enhanced resume version
   - Curated job recommendations

## Technology Stack
- **Core Framework**: CrewAI
- **Document Processing**: PyMuPDF, python-docx
- **AI Models**: OpenAI GPT (via API)
- **Job Search**: Serper API

## Setup Instructions
```bash
# Install dependencies
pip install PyMuPDF python-docx crewai crewai-tools

# Configure API keys
echo "your_openai_key" > openai.txt
echo "your_serper_key" > serper.txt
