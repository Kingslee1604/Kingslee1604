## Kingslee Velu

Senior engineer building reliable AI platforms (LLMs & SLMs, agents, RAG) and the backend
systems they run on. 15+ years in healthcare IT: claims, member enrollment, EDI and contact
centers, where a quiet bug means a wrong claim or a missed member.

**[Portfolio](https://kingslee1604.github.io)** · **[LinkedIn](https://www.linkedin.com/in/kingsleevelu/)**

### Featured work

**[AgentForge](https://kingslee1604.github.io/projects/agentforge/)**: a self-hosted platform
that answers security questionnaires only from your own documents, with a verbatim quote
behind every sentence and a person approving what goes out. Runs on a CPU-only laptop.
100% retrieval recall@5 · 50/50 runs survived worker crashes · 3x faster after a measured fix.
[Code](https://github.com/Kingslee1604/2026AIProjects/tree/main/agentforge)

**[MEDREx](https://kingslee1604.github.io/projects/medrex/)**: M.S. project sponsored by the
Cedars-Sinai AI Campus. Six NLP methods compared on 9,523 pathology reports to name the cancer
type out of 32. A TF-IDF + linear SVM reached 97.37% accuracy, ahead of fine-tuned BERT and RAG
with LLMs, and trains in 12 seconds on a CPU.
[Code](https://github.com/Kingslee1604/MEDREx-Masters-Project)

**[production-rag](https://github.com/Kingslee1604/2026AIProjects/tree/main/production-rag)**:
a CPU-only RAG prototype with hybrid retrieval, reranking, verified citations and an evaluation
gate in CI.

### How I work

- **Measure before claiming.** Every number in my case studies links to its raw data.
- **Design for failure.** Durable runs, idempotent steps, and tests that kill the worker on purpose.
- **Private by default.** Local models where the data can't leave the building.

### Tools

Python · C#/.NET · FastAPI · PostgreSQL/pgvector · Azure OpenAI · Azure AI Foundry ·
Semantic Kernel · LangChain/LangGraph · Ollama · MCP · Azure · AWS · Next.js
