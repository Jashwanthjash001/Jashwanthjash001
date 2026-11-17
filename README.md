# Jashwanth Gowda B R

AI Engineer. I build **local / edge LLM systems** end to end — quantize a model to run on hardware
you already own, serve it, build real apps on it, fine-tune it, and wire agents on top.

Most of my recent work runs **fully on-device** (Apple Silicon / consumer GPUs) — no cloud API, no
data leaving the machine — because that's where a lot of real teams actually need LLMs: compliance,
cost, and latency rule out sending data to a hosted model.

### The local-LLM lifecycle, as projects

| | Project | What it shows |
| --- | --- | --- |
| 🔧 | **[edge-ai-client](https://github.com/Jashwanthjash001/edge-ai-client)** | Run Llama 3.1 8B on a 16 GB Mac. Quantization study: Q4_K_M vs Q8_0 — ~2× faster decode, 42% smaller on disk. |
| 📄 | **[local-document-assistant](https://github.com/Jashwanthjash001/local-document-assistant)** | Fully-offline RAG over your own PDFs. Grounded answers with page citations, abstains when the docs don't support an answer. |
| ⚡ | **[llm-serving-optimization-lab](https://github.com/Jashwanthjash001/llm-serving-optimization-lab)** | vLLM serving benchmark. Measured the latency-vs-throughput curve: ~238 tok/s at 8 concurrent users on an RTX 4060 Ti, then the saturation knee. |
| 🎛️ | **[finetuning-lab](https://github.com/Jashwanthjash001/finetuning-lab)** | LoRA fine-tune Llama 3.2 1B on Apple Silicon (MLX). Exact-match on a structured task: 15% → 100%. |
| 🤖 | **[sequence-agent](https://github.com/Jashwanthjash001/sequence-agent)** | Agentic outreach orchestrator — persistent state, deterministic guardrails, human handoff. |
| ⚖️ | **[llm-council](https://github.com/Jashwanthjash001/llm-council)** | Multi-model ensemble: three models answer, two judge, one auditable decision — prefers an honest *no decision* over false confidence. |

### Stack

Python · FastAPI · vLLM · llama.cpp · MLX · LangChain / LangGraph · ChromaDB · Docker · AWS

### Reach me

[LinkedIn](https://www.linkedin.com/in/jashgowda001/)
