# AI-Powered Content Automation using n8n

## Overview

This project automates content processing and publishing using Google Sheets, Google Gemini AI, Gmail, and LinkedIn.

When a new article is added or updated in Google Sheets, the workflow automatically generates a summary, creates email-ready content, prepares a LinkedIn post, sends an email, and publishes content to LinkedIn.

## Workflow

Google Sheets Trigger

↓

Gemini AI Article Summarizer

↓

├── Gemini AI Email Formatter → Gmail Sender

└── Gemini AI LinkedIn Post Generator → LinkedIn Publisher

## Features

* Automated article summarization using Google Gemini AI
* AI-generated email content
* Automatic Gmail delivery
* AI-generated LinkedIn posts
* Automatic LinkedIn publishing
* End-to-end workflow automation using n8n

## Tech Stack

* n8n
* Google Gemini AI
* Google Sheets
* Gmail API
* LinkedIn API
* OAuth 2.0

## Learning Outcomes

* Workflow Automation
* Prompt Engineering
* API Integration
* OAuth Authentication
* AI Content Generation
* Social Media Automation

## Project Architecture

1. Google Sheets detects new or updated content.
2. Gemini AI generates a concise article summary.
3. The workflow creates email-ready content.
4. Gmail automatically sends the formatted email.
5. Gemini AI generates a LinkedIn post.
6. LinkedIn automatically publishes the content.

## Future Improvements

* X (Twitter) Integration
* Multi-platform Publishing
* AI Agent Workflows
* Analytics Dashboard
* Content Scheduling

## Author

Pujitha
