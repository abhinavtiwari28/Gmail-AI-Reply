# Gmail AI Reply Automation

An AI-powered email management workflow built with **n8n**, **Gmail API**, and **OpenAI GPT-4.1 Mini**.

## Overview

This workflow automatically monitors incoming Gmail messages, analyzes email content using AI, classifies emails into predefined categories, applies Gmail labels, and generates professional reply drafts.

The system helps automate repetitive email management tasks and improves response efficiency.

## Features

* Monitor incoming Gmail emails in real-time
* Fetch complete email content automatically
* AI-powered email classification
* Automatic Gmail label assignment
* Smart reply generation using OpenAI
* HTML formatted email drafts
* Thread-aware email drafting
* Support for:

  * Course Queries
  * Student Doubts
  * Sponsorship Requests

## Workflow Architecture

```text
Gmail Trigger
      ↓
Get Email Content
      ↓
AI Agent (OpenAI)
      ↓
Classify Email
      ↓
Apply Gmail Label
      ↓
Generate HTML Reply
      ↓
Create Gmail Draft
```

## Technologies Used

* n8n
* Gmail API
* OpenAI GPT-4.1 Mini
* Gmail Labels
* Structured Output Parser
* AI Agent Workflows

## AI Processing

The AI agent performs:

1. Email content analysis
2. Intent detection
3. Category classification
4. Label identification
5. Professional reply generation
6. HTML email formatting

## Example

### Incoming Email

Subject: Doubts

Message:
Please help in mastering n8n.

### AI Output

Label: doubts

Reply Draft:

* Professional greeting
* Detailed explanation
* Learning roadmap
* Practical examples
* Closing response

## Installation

1. Import the workflow JSON into n8n.
2. Configure Gmail OAuth credentials.
3. Configure OpenAI API credentials.
4. Create Gmail labels:

   * course
   * doubts
   * sponsorship
5. Activate the workflow.

## Future Improvements

* Multi-language support
* Auto-send replies
* Priority email detection
* Sentiment analysis
* CRM integration
* RAG-based knowledge retrieval
* Attachment analysis

## Author

Abhinav Tiwari

GitHub: https://github.com/abhinavtiwari28
# Gmail-AI-Reply
