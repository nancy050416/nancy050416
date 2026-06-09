# Hi, I'm Nancy

I am preparing for software engineering internships and currently focusing on full-stack AI applications.

My main project is **ThinkLoop**, an AI Agent assistant built around Spring AI, tool calling, RAG knowledge bases, and real-time execution feedback. I am improving it as a serious engineering project rather than leaving it as a one-off demo.

## Current Focus

| Area | What I am building |
| --- | --- |
| Backend | Spring Boot services, API design, MyBatis persistence, SSE streaming |
| AI Application | Agent loop, manual tool calling, multi-model routing, RAG retrieval |
| Frontend | React, TypeScript, Ant Design, stateful chat UI, loading and error states |
| Engineering Practice | Clear README, environment configuration, lint/build validation, focused commits |

## Featured Project

### [ThinkLoop - AI Agent Assistant](https://github.com/nancy050416/my-project)

An AI Agent practice project based on **Spring AI + React**, designed to explore how large language models can be integrated into a controllable backend system.

**What it includes:**

- Agent Think-Execute loop for multi-step task handling
- Manual tool calling lifecycle management
- Markdown document ingestion and RAG retrieval with PostgreSQL + pgvector
- SSE-based real-time feedback for planning, thinking, execution, and completion states
- React + TypeScript frontend for chat sessions, agents, and knowledge bases
- Configurable frontend API/SSE endpoints through Vite environment variables

**Tech stack:** Java 17, Spring Boot, Spring AI, MyBatis, PostgreSQL, pgvector, React, TypeScript, Vite, Ant Design

## Recent Work

- Refactored frontend runtime configuration to avoid hard-coded API and SSE addresses
- Improved the new-chat onboarding view to better communicate the Agent/RAG workflow
- Split React context consumption into a hook-friendly structure that passes lint rules
- Reorganized the project README so the architecture and learning value are easier to scan
- Verified the frontend with `npm run build` and `npm run lint`

## Learning Roadmap

- Add RAG evaluation examples to compare retrieval quality
- Improve hybrid retrieval with keyword search + vector search
- Add tool-call retry and fallback handling
- Add SSE heartbeat and more complete error recovery
- Deploy a public demo after configuration and secrets are cleaned up

## Contact

- GitHub: [nancy050416](https://github.com/nancy050416)
- Email: 2167920027@qq.com

