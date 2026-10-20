# Hi, I'm Victor

Senior backend engineer with 10+ years of experience building distributed systems on the JVM
(Java, Kotlin, Spring Boot) and AWS, and 1.5+ years of shipping LLM agents, RAG pipelines and
chatbots to production. I speak English and German (C1), and Russian is my native language.

## About my work

**My main projects live in my employers' private GitHub organizations, so I can't show them here.**
Over the years they covered high-load backend services, payment provider integrations,
regulatory reporting and internal AI assistants.

What you find on this profile are **a few smaller examples** I built on my own and for freelance
clients. They are less complex than production systems at scale, but they are real, they run in
production, and they show how I design, test and operate things end to end.

## Selected projects

| Project | What it is | Highlights |
|---|---|---|
| [business-simple-ai-bot](https://github.com/v-umanskiy/business-simple-ai-bot) | Multi-tenant chatbot backend for small businesses (WhatsApp, Telegram, web chat), built for freelance clients | LangGraph flow, retrieval over structured knowledge sections without a vector DB, structured LLM output, human handoff, per-channel length control, privacy-friendly logging, 85 tests |
| [calendar-bot](https://github.com/v-umanskiy/calendar-bot) | Telegram assistant that manages Google Calendar with text and voice | Gemini tool calling with guardrails, OAuth 2.0, KMS-encrypted tokens, confirmation before destructive actions, prompt caching, 114 tests |
| [transcribe-bot](https://github.com/v-umanskiy/transcribe-bot) | Telegram bot that turns voice messages, audio files and Google Drive links into clean text | Whisper for short clips and AWS Transcribe for long ones, SQS chunk pipeline, Gemini refinement with fallback, monthly quotas, 64 tests |

All three are serverless Python on AWS Lambda, with secrets in AWS Secrets Manager and infrastructure
managed with Terraform.

## Tech I work with

**Backend:** Java, Kotlin, Spring Boot, Python, FastAPI, PostgreSQL, Hibernate, Kafka, SQS/SNS
**Cloud and ops:** AWS (Lambda, DynamoDB, S3, KMS, EKS), Terraform, Docker, GitHub Actions, Datadog
**AI:** OpenAI and Gemini APIs, tool calling, RAG, LangGraph, LangFuse, Pinecone
