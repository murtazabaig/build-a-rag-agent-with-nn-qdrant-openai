

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Build a RAG Agent with n8n, Qdrant & OpenAI

Advanced n8n automation for Build a RAG Agent with n8n, Qdrant & OpenAI.

## Overview
- Category: Internal Wiki, AI RAG
- Complexity: intermediate
- Source: n8n workflow template export

## What This Automation Does
Turn Google Docs into an AI-powered assistant with this RAG template: upload, chat, and get accurate, source-cited answers. Easy setuplearn more!

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.documentDefaultDataLoader`
- `@n8n/n8n-nodes-langchain.embeddingsOpenAi`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `@n8n/n8n-nodes-langchain.textSplitterRecursiveCharacterTextSplitter`
- `@n8n/n8n-nodes-langchain.vectorStoreQdrant`
- `n8n-nodes-base.googleDriveTrigger`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.