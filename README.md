<p align="center">
  <img src="img/zack-proser-headshot.jpg" width="280" style="border-radius: 50%;" alt="Zack Proser" />
</p>

<h1 align="center">Zack Proser</h1>

<p align="center">
  <strong>Independent AI Researcher</strong> · Engineer<br/>
  <em>Local inference economics · Eval methodology · Systems from silicon to prompt</em>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2510.25819"><img src="https://img.shields.io/badge/arXiv-Identity%20Mgmt%20for%20Agentic%20AI-B31B1B?style=flat-square" alt="arXiv"/></a>
  <a href="https://zackproser.com/blog?tag=blueprint"><img src="https://img.shields.io/badge/Blueprints-17%20technical%20drawings-1a1a1a?style=flat-square" alt="Blueprints"/></a>
  <a href="https://zackproser.com/blog/the-eval-harness"><img src="https://img.shields.io/badge/Benchmarks-60%2B%20controlled%20runs-2d37aa?style=flat-square" alt="Benchmarks"/></a>
  <a href="https://github.com/zackproser/portfolio"><img src="https://img.shields.io/badge/Demos-9%20live%20interactive-7c3aed?style=flat-square" alt="Demos"/></a>
</p>

---

## Research

I run controlled experiments on local LLM inference, build eval harnesses with proper statistics, and publish everything as interactive technical drawings.

<table>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-price-floor"><strong>The Price Floor</strong></a><br/><em>Local inference break-even analysis</em><br/>M5 Max memory-bandwidth ceilings · Engine tax (llama.cpp vs ds4 = 5× speedup) · GPU amortization math · ~$34K Blackwell build-or-buy
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-eval-harness"><strong>The Eval Harness</strong></a><br/><em>Coding agent benchmark (60 runs)</em><br/>Local vs cloud vs frontier model · Hidden-test design · Wilson interval statistics · Exact per-token billing
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-cost-curve"><strong>The Cost Curve</strong></a><br/><em>DeepSeek V4 Flash economics</em><br/>MoE routing (284B/13B active) · Token ledger arithmetic · Quantization ladder · Cache-hit dominance (96.6%)
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-inference-engine"><strong>The Inference Engine</strong></a><br/><em>Serving architecture deep-dive</em><br/>Prefill/decode phases · KV cache & PagedAttention · SARATHI chunked prefill · DistServe
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-benchmark"><strong>The Benchmark</strong></a><br/><em>Measurement methodology</em><br/>MMLU · SWE-bench · Chatbot Arena · Provenance chains · Goodhart's law in eval
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/practical-local-inference-aug-2026"><strong>Practical Local Inference</strong></a><br/><em>M5 Max + DeepSeek V4 Flash at 30-40 tok/s</em><br/>Workload routing matrix · $17/mo via Gateway vs $2,000 worst-case
</td>
</tr>
</table>

### The Blueprint Series

17 technical drawings covering the full AI stack — each with SVG schematics, equations, academic citations, and interactive demos:

| Drawing | Topic |
|---------|-------|
| [The Transformer](https://zackproser.com/blog/the-transformer) | Attention, KV cache, positional encoding, feed-forward layers |
| [The Tokenizer](https://zackproser.com/blog/the-tokenizer) | BPE vocabulary training, merge tables, Unicode, cost implications |
| [The Embedding Space](https://zackproser.com/blog/the-embedding-space) | Vector geometry, word2vec → Sentence-BERT → SimCSE, HNSW ANN |
| [The RAG Pipeline](https://zackproser.com/blog/the-rag-pipeline) | Chunk → embed → retrieve → rerank → generate, ColBERT, Lost in Middle |
| [The Diffusion Model](https://zackproser.com/blog/the-diffusion-model) | DDPM → flow matching, noise schedules, CFG, DiT architecture |
| [Choosing an LLM](https://zackproser.com/blog/choosing-an-llm) | Dense vs MoE, quantization formats, Chinchilla scaling, distillation |
| [The Agent Fleet](https://zackproser.com/blog/the-agent-fleet) | 11-bot architecture, Slack orchestration, mechanic-agent pattern |
| [The Attention Head](https://zackproser.com/blog/the-attention-head) | Mechanistic interpretability, induction heads, superposition, causal intervention |
| [The Autonomy Boundary](https://zackproser.com/blog/the-autonomy-boundary) | Agent limits, permission systems, human-in-the-loop, OWASP LLM Top 10 |
| [The Guard](https://zackproser.com/blog/the-guard) | Prompt injection as trust-boundary, defense architecture for tool-using agents |
| [Designing AI Evaluations](https://zackproser.com/blog/designing-ai-evaluations) | Eval framework: contracts, sampling, graders, slices, thresholds, regression |
| [The Workshop](https://zackproser.com/blog/the-workshop) | AI training as RFP funnel, hands-on pedagogy |

[→ View all 17 Blueprints](https://zackproser.com/blog?tag=blueprint)

---

## Interactive Demos

Live tools you can use right now — built into my portfolio site:

| Demo | What it does | Link |
|------|-------------|------|
| **Local vs Cloud Benchmark** | 60-run evidence explorer with per-cell inspection, scoring lenses, cost calculator | [Try it](https://zackproser.com/demos/local-vs-cloud-ai-coding) |
| **Tokenization Lab** | Character → word → BPE → WordPiece tokenization with pricing calculator | [Try it](https://zackproser.com/demos/tokenize) |
| **RAG Visualized** | Animated pipeline step-through with chunking strategy inspector | [Try it](https://zackproser.com/demos/rag-visualized) |
| **Embeddings Explorer** | 3D vector space projection, similarity geometry, dimensionality reduction | [Try it](https://zackproser.com/demos/embeddings) |
| **Voice AI Pipeline** | Meeting intelligence dashboard, ASR pipeline visualization | [Try it](https://zackproser.com/demos/voice-ai) |

---

## Publications

- **[Identity Management for Agentic AI](https://arxiv.org/abs/2510.25819)** (Oct 2025) — Co-authored white paper on authentication, authorization, and security for AI agents. With Tobin South, Alex Pentland (MIT), and others.
- **RAG Evaluation chapter** — Official contribution to Pinecone's *Vector Databases in Production* book series.
- **50+ technical articles** at WorkOS, Pinecone, Cloudflare, Gruntwork — AI agents, RAG pipelines, fine-grained auth, vector DBs, IaC.
- **134+ articles** on [zackproser.com](https://zackproser.com/blog) + external publications on [The New Stack](https://thenewstack.io), [Prefect.io](https://prefect.io), [Pinecone Learning Center](https://www.pinecone.io/learn/).

[→ Full publications list](https://zackproser.com/publications)

---

## Open Source

| Project | Description | Stars |
|---------|-------------|-------|
| [coding-agent-eval-harness](https://github.com/zackproser/coding-agent-eval-harness) | Open-source benchmark harness for coding agent comparison | NEW |
| [portfolio](https://github.com/zackproser/portfolio) | This site — Next.js 15, 17 Blueprints, 9 interactive demos, 672 articles | — |
| [handwave](https://github.com/zackproser/handwave) | watchOS app controlling Claude Code from your wrist | — |
| [git-xargs](https://github.com/gruntwork-io/git-xargs) | Run commands across many GitHub repos simultaneously | ⭐ 1,086 |
| [cloud-nuke](https://github.com/gruntwork-io/cloud-nuke) | AWS resource cleanup — nuke entire accounts safely | ⭐ 3,121 |
| [cf-terraforming](https://github.com/cloudflare/cf-terraforming) | Generate Terraform from existing Cloudflare config | ⭐ 1,324 |

---

## Speaking

| Event | What | When |
|-------|------|------|
| **DevSecCon 2025** | [Keynote: "Walking and Talking in the Woods with AI"](https://www.youtube.com/watch?v=kwIzRkzO_Z4) — Voice-first development, agent autonomy | 2025 |
| **WorkOS x Anthropic** | [Claude Cowork GTM Workshop](https://zackproser.com/blog/claude-cowork-workshop-anthropic) — 800 registrations, hands-on build | Feb 2026 |
| **AI Engineer World Fair** | [Workshop: AI Pipelines & Agents](https://zackproser.com/blog/ai-pipelines-and-agents-mastra) — Taught 70 engineers | Jun 2025 |
| **a16z San Francisco** | [From Jupyter Notebooks to Production](https://zackproser.com/blog/a16z-sf-dec-2023-ai-apps-production) — ~125 attendees | Dec 2023 |

[→ All speaking engagements](https://zackproser.com/speaking)

---

## Career

| Role | Company | Years | What I did |
|------|---------|-------|------------|
| **Applied AI** | [WorkOS](https://workos.com) | 2025–present | AI workflows, internal tooling, developer education. Created Claude Cowork workshop with Anthropic. |
| **Staff DevRel** | [Pinecone](https://pinecone.io) | 2023–2025 | RAG pipelines, AWS reference architectures, dev education during the vector DB explosion. Spoke at a16z SF. |
| **Software Engineer** | [Cloudflare](https://cloudflare.com) | 2020–2023 | Joined at ~100 engineers globally. Built `cf-terraforming` (1.3K⭐). APIs, edge infra, dev tools at scale. |
| **Infrastructure Engineer** | [Gruntwork](https://gruntwork.io) | 2018–2020 | Built `git-xargs` (1K⭐), contributed to `cloud-nuke` (3.1K⭐). Multi-account AWS, Terraform, production IaC. |

---

## Reach

**104K+ visitors/year** (+82% YoY) · **133K+ page views** (+60%) · **4,000+ newsletter subscribers**

Regularly advising hedge funds and PE firms on AI infrastructure, developer tools, and cloud platforms via AlphaSights, Guidepoint, Tegus, GLG, Coleman.

---

<p align="center">
  <a href="https://zackproser.com">zackproser.com</a> ·
  <a href="https://twitter.com/zackproser">Twitter/X</a> ·
  <a href="https://www.linkedin.com/in/zackproser/">LinkedIn</a> ·
  <a href="https://youtube.com/@zackproser">YouTube</a> ·
  <a href="https://github.com/zackproser/portfolio">Portfolio Repo</a>
</p>
