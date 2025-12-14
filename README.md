# Practical LLM Engineering — From Zero to Production

A living, hands-on guide to building systems powered by Large Language Models (LLMs).

This repository progresses incrementally from basic SDK usage to
production-oriented patterns such as memory management, retrieval-augmented
generation (RAG), evaluation, safety, and cost control.

The focus is **not** on clever prompts, but on **system design**.

---

## Philosophy

With this project i wanted to have a repository where i could log, stack and show the ever evolving understanding that i have of LLMs from a practical standpoint. 
This is a living-breathing project, meant to go on as far as my knowledge on the matter is, which is sadly not that far as of right now. I pledge to polish, maintain and eventually finish this project of mine. I welcome the reader on this journey of learning we've undertaken. May it be used for the good. 


---

## Structure

- `chapters/` — Incremental, self-contained learning units (0 → 100)
- `providers/` — Provider-specific implementations (OpenAI, Anthropic, etc.)
- `utils/` — Shared utilities (chunking, similarity, guards, memory)
- `data/` — Sample datasets used across chapters

Each chapter includes:
- a conceptual README
- minimal, focused code
- explicit scope and limitations

---

## Chapter Roadmap

1. SDK & Environment Basics
2. Single-Turn Calls
3. Interactive CLI
4. Prompt Hierarchy (Developer vs User)
5. Multi-Turn Memory
6. Streaming Responses
7. Embeddings
8. Semantic Retrieval
9. RAG — Basic
10. RAG — Advanced
11. Memory Strategies
12. Evaluation & Grounding
13. Safety & Guardrails
14. Cost & Token Control
15. Multi-Provider Abstractions

---

## Credits & Inspiration

This project is inspired by the CS50 AI Workshop and similar educational material.
Original examples were used strictly as learning references and have been
reimplemented, reorganized, and extended.

---

## Status

🚧 Work in progress — chapters are added and refined incrementally.
