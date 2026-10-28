# Hi, I am Yu Cheng

MS Computer Engineering at NYU, BS Data Science at Duke. I build practical AI systems with a focus on LLM infrastructure, inference performance, observability, and customer-facing AI workflows.

I like work that turns messy model-serving behavior into something measurable: benchmarks, traces, evals, small correctness tests, better docs, and tools that make AI systems easier to operate.

## Current Focus

- LLM serving infrastructure: SGLang, vLLM-style serving, llm-d, routing, KV-cache behavior, and OpenAI-compatible APIs.
- Performance tooling: inference benchmarks, kernel correctness checks, latency reports, and lightweight observability.
- Forward-deployed AI systems: support/onboarding agents, RAG workflows, citations, escalation paths, and eval loops.
- Applied AI products: local-first assistants and domain workflows where reliability matters more than demo polish.

## Selected Work

| Project | What it shows | Stack |
| --- | --- | --- |
| [langgraph-support-agent](https://github.com/Gloria72/langgraph-support-agent) | LangGraph support/onboarding agent for AI infrastructure repos, with local retrieval, evals, escalation, and a forward-deployed case study. | Python, LangGraph |
| [sglang-observability-router](https://github.com/Gloria72/sglang-observability-router) | OpenAI-compatible routing proxy and benchmark harness for SGLang-style serving experiments. | Python, LLM serving |
| [flashinfer-kernel-bench](https://github.com/Gloria72/flashinfer-kernel-bench) | Correctness-first microbenchmarks for attention and sampling code paths. | Python, NumPy, Torch |
| [rust-candle-gateway](https://github.com/Gloria72/rust-candle-gateway) | Rust inference gateway with bounded request handling, health checks, metrics, and a Candle-ready engine boundary. | Rust |
| [fitsnap-coach](https://github.com/Gloria72/fitsnap-coach) | Local-first AI fitness coach with form checks, recovery scoring, trend charts, and an agent task workspace. | JavaScript |

## Open Source

- [vLLM PR #64143](https://github.com/vllm-project/vllm/pull/64143) **(open, under review)**: fix SSE payload extraction across completion, chat, and audio benchmark clients, with HTTP regression tests and real-model CPU server validation.
- [LiteLLM PR #36018](https://github.com/BerriAI/litellm/pull/36018) **(open, under review)**: use the configured API docs base URL in MCP connection snippets, with URL-precedence and rendered-component tests.

## How I Work

- Start with a small reproducible path before optimizing.
- Prefer tests, eval cases, and traceable outputs over broad claims.
- Keep setup steps explicit because developer experience is part of the product.
- Write docs and runbooks when they make a system easier for the next person to operate.

## TECHNICAL SKILLS

**ML Systems & Inference:** Python, C++/CUDA, Triton Inference Server, vLLM, SGLang, TensorRT, ONNX Runtime, Profiling.

**Optimization & Architectures:** Instruction Tuning, PEFT, FSDP, DPO/RLHF, LangGraph, LangChain, LLM-as-Judge Evaluation, Guardrails. KV-Cache, Continuous/In-flight Batching, Quantization (AWQ, INT8, QLoRA), CUDA Streams, Nsight Systems/Compute.

**Backend & Data Integration:** PyTorch, PySpark, Airflow, FastAPI, gRPC, PostgreSQL, Snowflake, Docker, Kubernetes, AWS.

**DevOps & Observability:** OpenTelemetry, CI/CD (GitHub Actions), Prometheus/Grafana style metrics, structured logging, JUnit 5.

## Contact

- [LinkedIn](https://www.linkedin.com/in/yu-cheng-53515a236/)
- [Email](mailto:gloriacheng80@gmail.com)
