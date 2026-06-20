# Nautam Ranpariya

SDE II at Advergrow Solutions, building production AI systems full-time.

Over two years I've been the largest individual contributor to two 
SaaS products: **adverti.chat** (ad-intelligence platform for Indian 
D2C brands) and **adverti.app** (self-serve ad launch for small 
businesses). 42% of all backend code, 8 of 10 third-party integrations, 
and the AI layer designed from scratch.

That AI layer is a multi-provider LLM gateway (Claude, OpenAI, Gemini, 
Groq) with an MCP-based tool layer and a Redis-backed real-time 
streaming chat system.

**Stack:** TypeScript · NestJS · Node.js · React · Next.js · 
PostgreSQL · Redis · AWS · socket.io

Production commits live at [@nautam-advergrow](https://github.com/nautam-advergrow) 
(all private). The architecture writeups below cover the AI layer, the 
auth system, and the async backbone:

**[LLM Gateway & Real-Time Chat Architecture](https://github.com/nautam-dev/llm-gateway-architecture)**  
Multi-provider gateway, MCP tool layer, streaming chat. Design decisions 
and tradeoffs, no proprietary code.

**[Authentication Architecture](https://github.com/nautam-dev/auth-architecture)**  
Cognito-backed login, Google One Tap, and a two-layer authorization 
model. Design decisions and tradeoffs, no proprietary code.

**[Async Queue Architecture](https://github.com/nautam-dev/async-queue-architecture)**  
BullMQ-based job system handling payments, ad publishing, AI workflows, 
and scheduled jobs. Design decisions and tradeoffs, no proprietary code.

[LinkedIn](https://www.linkedin.com/in/nautam-ranpariya/) · 
[adverti.chat](https://adverti.chat) · [adverti.app](https://adverti.app)
