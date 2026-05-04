# n8n AI Security Bot

#Overview
This is an automated cybersecurity system built with n8n that detects phishing attempts and fraudulent messages in real-time. It specifically supports the Azerbaijani language, making it a unique solution for local digital safety.

How It Works
The workflow follows a sophisticated logic to ensure high accuracy:

Webhook Trigger: Receives incoming messages (e.g., from Telegram or SMS).

IF Logic (Filtering): Filters messages based on keywords (Bank, Card, HTTP) to focus only on potential threats.

JavaScript Processing: Custom JS code extracts URLs from the message body for individual analysis.

HTTP Request Verification: The system performs a live GET request to the extracted link to check its status and destination.

Gemini AI Analysis: An AI Agent analyzes the message context and the link's metadata to provide a final security verdict in Azerbaijani.

Google Sheets Logging: Every analysis is logged into a database for future monitoring.

Tech Stack
Automation: n8n

AI: Google Gemini 1.5 Flash

Programming: JavaScript

Integration: HTTP API, Google Sheets API

Language Support: Azerbaijani (Primary), English

Recent Updates (May 4, 2026)
Integrated HTTP Request node for real-time URL status verification.

Added IF Logic to reduce AI token usage by filtering non-suspicious messages.

Improved AI system prompts to recognize internal test environments (n8n webhooks).
- AI / LLM