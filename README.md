# Practical LLM Engineering — From Zero to Production
![status](https://img.shields.io/badge/status-work_in_progress-lightgrey)
![focus](https://img.shields.io/badge/focus-system_design-lightgrey)
![scope](https://img.shields.io/badge/scope-practical_llm_engineering-lightgrey)

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

- `data/transcipts` — Sample dataset. The contents are taken from CS50x used for embeddings and rag
- `demo/` — Provider-specific implementations structured in icremental, self-contained learning units 
- `demo/embeddings/openai` — This repository implements a minimal retrieval-augmented generation pipeline from scratch: offline document embedding, semantic retrieval at query time, and grounded response generation. The focus is on understanding the mechanics and failure modes rather than relying on abstractions.
- `demo/chat` — This repository displays qualitative jumps from calling the model's API to get a stream out output from the model and how to get multi-turn memory
- `utils/` — Shared utilities

---



## Credits & Inspiration

This project is inspired by the CS50 AI Workshop and similar educational material and aims to build on top of that.
---

## Status

Work in progress — chapters are added and refined incrementally.
