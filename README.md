# AI Meeting Assistant

An AI-powered meeting automation workflow that transforms meeting transcripts or notes into structured summaries, decisions, action items, risks, and follow-up messages.

## Workflow

**Meeting Transcript → Prepare → AI Analysis → Summary & Decisions → Action Items → Follow-up**

## Features

- Meeting transcript processing
- AI-generated meeting summaries
- Key decision extraction
- Action-item detection
- Owner and deadline extraction
- Risk and blocker identification
- Follow-up message generation
- Structured JSON output
- n8n-ready workflow design

## Project Structure

```text
AI-Meeting-Assistant/
├── workflow/
│   └── meeting-assistant.json
├── prompts/
│   └── meeting-agent.json
├── config/
│   └── example.json
├── data/
│   └── output-schema.json
├── docs/
│   └── workflow.md
├── .gitignore
└── README.md
```

## Example Output

The workflow is designed to produce structured information such as:

- **Summary** — concise overview of the meeting
- **Decisions** — important decisions made during the meeting
- **Action Items** — tasks, owners, and deadlines when available
- **Risks** — blockers or concerns identified from the transcript
- **Follow-up** — a professional message based only on the meeting information

## Skills Demonstrated

- AI Automation
- n8n Workflow Design
- Prompt Engineering
- LLM Integration
- Text Processing
- Structured JSON Data
- Meeting Workflow Automation

## Security

No real API keys, private meeting transcripts, or credentials are stored in this repository. Use n8n credentials or environment variables for production.

## Production Extensions

A production version can connect transcription services, an AI provider, task-management tools, email, calendar systems, and secure persistent storage.

## Author

Abdul Nafay — AI Engineer & Web Developer
