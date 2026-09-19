# n8n Automations Workflows

Welcome to the **n8n Automation Workflows** repository! This repository contains a diverse collection of powerful, pre-configured n8n workflows designed to automate various business processes, marketing tasks, content creation, and data management pipelines. 

## 🚀 Overview

These workflows are built using [n8n](https://n8n.io/), an extensible workflow automation tool. They integrate multiple APIs, AI agents, databases, and third-party tools to streamline operations, save time, and boost productivity.

## 📂 Workflow Categories

### 🤖 AI Agents & Content Generation
* **Human Like Content Writer**: Automated content generation with a human touch.
* **English / Dutch Content Writers**: SEO-optimized content creation workflows triggered via Google Sheets or forms.
* **Youtube Video Transcript with Timestamp Generator**: Extracts and formats YouTube transcripts.
* **Youtube to LinkedIn Post / X Post Automator**: Repurposes video content into social media posts.

### 💼 Marketing & Lead Generation
* **Lead Email Finder (Via Form & Sheet)**: Enriches leads and finds verified email addresses.
* **Lead Generator - Via Form**: Captures and routes incoming leads.
* **WhatsApp Marketing Workflow**: Broadcasts and manages WhatsApp campaigns.
* **Influencer Ad Creative (Via Telegram)**: Automates ad creative requests and delivery.

### 🔎 SEO & Web Monitoring
* **SEO Audit Generator & Phase 2 (Competitor Research)**: Comprehensive SEO audits and competitor keyword analysis using tools like Google Search Console and SE Ranking.
* **X - Tweets Monitoring**: Monitors Twitter/X for brand mentions (e.g., negative tweets), performs AI sentiment analysis, and sends Slack alerts.
* **n8n Jobs Scraper**: Scrapes job boards for relevant opportunities.

### 🎥 Media & Video Production
* **End to End Video Production**: Fully automated video generation pipeline fetching ideas from Google Sheets, generating prompts with GPT-4, and creating videos using Veo 3 / Fal AI.
* **AUDIO MINE (SSML Voiceover)**: Advanced text-to-speech workflows.

### 🏢 Operations & Administrative
* **Document Automation System**: Automates document parsing and formatting.
* **RAG Record Manager & Unfazed RAG Agent**: Retrieval-Augmented Generation flows for interacting with knowledge bases.
* **Notice Reminder via Email**: Distributes daily notices to target audiences via Email and WhatsApp.
* **Folk & Klaviyo Integrations**: Workflows for CRM management, applicant tracking, and Slack channel creation.

## ⚙️ Setup and Usage

1. **Install n8n**: Ensure you have n8n installed (either self-hosted or n8n Cloud).
2. **Import Workflow**: 
   * Open the desired `.json` file from this repository.
   * Copy the raw JSON content.
   * In your n8n workspace, go to the Workflows dashboard, click **Import from File** or simply paste the JSON directly into the canvas.
3. **Configure Credentials**: 
   * You will need to set up your own API credentials for the nodes (e.g., OpenAI, Google Sheets, Twitter, Slack, Supabase, etc.). *Note: All sensitive tokens in this repository have been replaced with dummy placeholders for security.*
4. **Activate**: Tweak the configurations to match your environment, test the nodes, and activate the workflow!

## 🔒 Security
All workflows have been sanitized. Hardcoded API keys, webhooks, and private tokens have been replaced with placeholders before committing. Always ensure you do not commit your `.env` files or hardcoded credentials when contributing.

## 🤝 Contributing
Contributions are welcome! If you have a cool n8n workflow you'd like to share:
1. Export your workflow as a JSON file.
2. Scrub any API keys or sensitive data.
3. Submit a Pull Request with a clear description of what your workflow does.

---
*Built with ❤️ for the AI Automation Community.*
