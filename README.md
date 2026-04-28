# n8n AI Security Bot

## Overview
AI-powered fraud and phishing detection system built with n8n.

It analyzes messages and URLs to detect suspicious behavior in real-time.

---

## How it works
- Input: user message (text / URL)
- Processing: n8n workflow + AI analysis
- Output: risk score + label (safe / suspicious / phishing)

---

## Example

**Input:**
"Təcili! Bank hesabınız bloklanıb: https://saxta-link.com"

**Output:**
- Label: Phishing
- Risk score: High
- Reason: Suspicious URL + urgency pattern

---

## Tech Stack
- n8n
- AI / LLM