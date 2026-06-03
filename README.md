# Hi, I'm Luther 👋
**AI Software Developer focused on building production-ready AI applications**: RAG pipelines, LLM integrations, and full-stack systems that ship.

I approach every problem top-down, defining what actually needs to be built before writing a line of code. My background in Computer Science and Philosophy gives me the ability to see the bigger picture, articulate abstract concepts clearly, and translate technical decisions into real business impact. I've co-founded a startup, won a pitch competition, and managed a cross-functional team from idea to product.

---
## What I Build

**Production RAG Systems** -- full pipeline architecture from ingestion and chunking strategy through embedding, retrieval, and response generation, with attention to retrieval quality, failure modes, and evaluation

**LLM-Powered Backends** -- services that orchestrate multiple foundation models into reliable, scalable workflows using structured outputs, agent pipelines, and clean separation between HTTP concerns and business logic

**Full-Stack AI Applications** -- end-to-end products spanning Python backends, TypeScript frontends, and cross-platform mobile apps, designed around real user workflows rather than demos

**Multi-Agent Systems** -- agentic pipelines that break complex tasks into specialized agents with defined inputs, outputs, and failure handling, built for observability and iterative improvement

**AI SaaS Products** -- co-founded and shipped a commercial AI product with auth, payments, cloud storage, and a generative multi-agent core

---
## Featured Projects
### Docent AI
RAG-powered document intelligence platform. Upload a PDF or text file, ask questions, and get answers grounded in your source material with citations.
  - Built a full RAG pipeline using sliding-window chunking (512-token chunks, 64-token overlap), OpenAI embeddings, and pgvector cosine similarity retrieval for semantically accurate answers
  - Async document processing with FastAPI BackgroundTasks, streaming responses via SSE, and a polling state machine on the frontend for real-time status updates
  - Component-driven Next.js/TypeScript frontend with 16 typed components built around progressive disclosure, visual hierarchy, and consistent design tokens via Tailwind CSS 4

  Stack: Python · FastAPI · PostgreSQL · pgvector · OpenAI API · Next.js · React · TypeScript · Tailwind CSS · Docker

---
### Scale66
Co-founded an AI SaaS that generates branded social media carousels from a single prompt.
  - Owned the entire backend: 5-stage multi-agent pipeline (format selection, template matching, copywriting, image generation), all API routes, and prompt engineering
  - Reference image chaining keeps visual style consistent across all slides
  - Full product: auth, Stripe subscriptions, cloud storage, and a Next.js frontend built and managed end-to-end

  Stack: Python · FastAPI · Anthropic API · Gemini API · Next.js · Supabase · Stripe
  
---
### Ultra Onboarding Agent
Built an agentic onboarding pipeline for [useultra.ai](https://useultra.ai) that converts a student resume into a fully scored, actionable profile in a single session.
  - Designed a three-agent sequential architecture: Resume Parser, SSE-streamed Interviewer, and a Pydantic-validated Synthesizer using tool-forced structured output
  - Interviewer dynamically tracks coverage across five rubric areas internally, driving an adaptive 8-10 question conversation
  - Synthesizer fuses resume fields, interview transcript, and GitHub activity into confidence-scored profiles for four downstream agents (College Chance, Internship Match, Research, Entrepreneurship)
  - Built full-stack: FastAPI backend with streaming endpoints, Next.js/TypeScript frontend with drag-and-drop upload, live chat UI, and a profile results page

---
### Project Master
Built a two-stage AI pipeline that converts a rough idea into a structured project plan and dual tech stack recommendations in a single session.
  - Designed a conversational ideation agent that extracts vision, target audience, problem statement, and MVP scope through adaptive multi-turn dialogue
  - Generated paired tech stack recommendations for MVP and full production architectures, tailored to the confirmed project plan
  - Enforced structured output across all agents using Claude's tool use API with `tool_choice`, eliminating free-text parsing entirely via Pydantic validation
  - Built full-stack: FastAPI backend with Alembic-managed PostgreSQL, Next.js frontend with type-safe view state and a unified API communication layer



---
## Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tldavid-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/tldavid)
