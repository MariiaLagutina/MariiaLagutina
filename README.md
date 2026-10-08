# Hi, I'm Mariia 👋

**AI Engineer · Python · Systems & Applied Mechanics Background**  
*Student at 42 Heilbronn*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mariia_Lagutina-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mariia-lagutina/)

I build reliable, observable AI systems and software — with measurable behavior, validated outputs, explicit failure handling, and automated tests.

My foundation in applied mechanics and mathematical modeling shapes how I write software: define the model, make constraints explicit, and verify invariants instead of trusting happy-path demos.

---

### 🛠 Tech Stack

**Languages & Systems:** Python, C, JavaScript, Linux, POSIX threads, concurrency<br>
**AI & Retrieval:** RAG, custom BM25, hybrid retrieval, RRF, embeddings, Hugging Face Transformers, Sentence Transformers, MiniLM, Qwen, constrained decoding, structured outputs<br>
**Backend & Applications:** FastAPI, Pydantic, Python Fire, Pygame, REST APIs, event-driven architecture<br>
**Quality & Tooling:** pytest, mypy, Flake8, uv, Make, Git, GitHub Actions, CI<br>
**Currently expanding:** PostgreSQL, NumPy, pandas, Docker (CLI fundamentals; project integration next)<br>
**Next:** LangChain, LangGraph, Qdrant, and production AI workflow orchestration

---

### 🚀 Featured Projects

#### **[Local RAG Pipeline (vLLM Codebase)](https://github.com/MariiaLagutina/RAG)**

*A deterministic, evaluation-first Retrieval-Augmented Generation system.*

- **Deterministic ingestion:** safe corpus discovery, strict source-exact chunking, and my own deterministic two-field BM25 inverted index with bounded reranking.
- **Grounding & Validation:** token-bounded context, local Qwen inference, caching, and structural citation-contract validation.
- **Evaluation & Rigor:** reproducible retrieval metrics (Recall@K, MRR), comprehensive test suite, and documented architectural decision records (ADRs).

#### **[Maria's Airlanes (42 Fly-in Simulator)](https://github.com/MariiaLagutina/42_Fly-in)**

*A turn-based routing, dispatch, and transport simulation with cooperative space-time planning.*

- **Scheduling:** capacity-aware reservations for hubs and transport lanes with dynamic rerouting and deadlock avoidance.
- **Design:** strict dependency boundaries, immutable simulation results, typed event bus, and CI test pipelines.
- **Visualization:** interactive Pygame dispatch views across European transport networks.

#### **[Call Me Maybe](https://github.com/MariiaLagutina/42_Call_me_maybe)**

*Schema-guided function-calling and constrained generation pipeline for small local LLMs.*

- Natural-language intent mapping to validated function calls via logit bias and token masks.
- Strict output verification with Pydantic and explicit failure modes.

#### **[Codexion](https://github.com/MariiaLagutina/42_Codexion)**

*Concurrent systems simulation in C managing multi-agent tasks and shared resources.*

- Implements FIFO and Earliest Deadline First (EDF) scheduling using POSIX threads, mutexes, and condition variables.
- Built with zero tolerance for race conditions, deadlocks, thread starvation, or busy-waiting.

---

### 📐 Engineering Principles

- **Define behavior first:** treat invalid user input and impossible internal states as distinct concerns.
- **Invariants over anecdotes:** rely on rigorous evaluation metrics and automated tests rather than cherry-picked examples.
- **Explicit architecture:** maintain visible dependency boundaries and clean abstractions; prune obsolete code as domain models evolve.
- **Failure-path focus:** test edge cases, resource exhaustion, and recovery paths with the same rigor as the happy path.
