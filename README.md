# AI-Powered Anti-Phishing Workflow
An advanced cybersecurity automation tool designed to detect and analyze phishing attempts in the Azerbaijani language. This project integrates AI-driven context analysis with real-time URL verification.

🚀 Key Features
Intelligent Filtering: Uses IF Logic to filter suspicious keywords (e.g., "Bank", "Card", "Urgent") before processing, optimizing resource usage.

Custom JS Extraction: Employs JavaScript to precisely extract URLs from complex message structures.

Live URL Verification: Performs real-time HTTP Request status checks to verify the accessibility and destination of suspicious links.

AI Analysis: Powered by Google Gemini AI, providing a detailed security verdict and threat score in the Azerbaijani language.

Automated Logging: Saves all analysis results to Google Sheets for monitoring and reporting.

🛠️ Tech Stack
n8n: Workflow orchestration.

Google Gemini 1.5 Flash: Context-aware threat detection.

JavaScript: Data manipulation and URL parsing.

HTTP API: External link status checks.

Google Sheets API: Database and logging.

📂 Project Structure
fraud-detection-workflow.json: The complete n8n workflow file.

README.md: Project documentation.