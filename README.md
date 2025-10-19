# BookTutor AI: Convert Any Book into an AI Tutor
About This Project

This repository is a modified version of BookTutor AI
originally developed by @zenvanriel - https://github.com/AI-Engineer-Skool/booktutor-ai


The original project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0),
and this modified version remains under the same license.

## How does it work?
Transform any PDF book into an interactive AI tutor that can:

Answer questions about your material

Explain difficult concepts

Help you learn efficiently using Retrieval-Augmented Generation (RAG) and local LLMs

🎥 See the original explainer video here:
https://youtu.be/GTidrAiojbg

## Prerequisites

- Python 3.x
- LM Studio running a local LLM locally (default endpoint: http://localhost:1234)

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Ensure LM Studio is running a language model locally with the API endpoint available

## Usage

Start your AI tutor with any PDF book:
```bash
python booktutor.py path/to/your/textbook.pdf
```

The system will:
1. Process your book (first run only)
2. Create a knowledge base (first run only)
3. Save the processed data for faster future access
4. Start an interactive tutoring session


Original work by zenvanriel
Modification © 2025 Joshua-Alex23 
