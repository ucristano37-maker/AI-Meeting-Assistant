# Workflow Documentation

## Flow

1. **Meeting Input** starts the workflow.
2. **Prepare Transcript** stores the meeting transcript.
3. **Build AI Prompt** creates structured analysis instructions.
4. **AI Processing Input** prepares the request for an AI provider.
5. Connect the output to storage, email, task management, or a calendar workflow as needed.

## Production Extensions

Add transcription, authentication, an AI provider, persistent storage, task creation, and follow-up notifications for a production implementation.

## Security

Keep API keys and private meeting transcripts out of GitHub. Use n8n credentials or environment variables for secrets.