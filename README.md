<p align="center">
  <img src="img/zack-proser-headshot.jpg" width="280" style="border-radius: 50%;" alt="Zack Proser" />
</p>

<h1 align="center">Zack Proser</h1>

<p align="center">
  <strong>Independent AI Researcher</strong> · Engineer · Consultant<br/>
  <em>Local inference economics · Eval methodology · Systems from silicon to prompt</em>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2510.25819"><img src="https://img.shields.io/badge/arXiv-Identity%20Mgmt%20for%20Agentic%20AI-B31B1B?style=flat-square" alt="arXiv"/></a>
  <a href="https://zackproser.com/blog?tag=blueprint"><img src="https://img.shields.io/badge/Blueprints-17%20technical%20drawings-1a1a1a?style=flat-square" alt="Blueprints"/></a>
  <a href="https://zackproser.com/blog/the-eval-harness"><img src="https://img.shields.io/badge/Benchmarks-60%2B%20controlled%20runs-2d37aa?style=flat-square" alt="Benchmarks"/></a>
  <a href="https://github.com/zackproser/portfolio"><img src="https://img.shields.io/badge/Demos-9%20live%20interactive-7c3aed?style=flat-square" alt="Demos"/></a>
  <a href="https://mindonfire.net"><img src="img/mind-on-fire-logo.png" width="18" alt="Mind on Fire"/> Mind on Fire AI Consultancy</a>
</p>

---

## Research

I run controlled experiments on local LLM inference, build eval harnesses with proper statistics, and publish everything as interactive technical drawings.

<table>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-price-floor"><img src="https://zackproser.b-cdn.net/images/og-images/the-price-floor.png" width="100%" alt="The Price Floor" /></a><br/>
<strong><a href="https://zackproser.com/blog/the-price-floor">The Price Floor</a></strong><br/><em>Local inference break-even analysis</em><br/>M5 Max memory-bandwidth ceilings · Engine tax (llama.cpp vs ds4 = 5×) · ~$34K Blackwell build-or-buy
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-eval-harness"><img src="https://zackproser.b-cdn.net/images/og-images/the-eval-harness.png" width="100%" alt="The Eval Harness" /></a><br/>
<strong><a href="https://zackproser.com/blog/the-eval-harness">The Eval Harness</a></strong><br/><em>Coding agent benchmark (60 runs)</em><br/>Local vs cloud vs frontier · Hidden-test design · Wilson interval statistics
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-cost-curve"><img src="https://zackproser.b-cdn.net/images/og-images/the-cost-curve.png" width="100%" alt="The Cost Curve" /></a><br/>
<strong><a href="https://zackproser.com/blog/the-cost-curve">The Cost Curve</a></strong><br/><em>DeepSeek V4 Flash economics</em><br/>MoE routing (284B/13B active) · Quantization ladder · Cache-hit dominance (96.6%)
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-inference-engine"><img src="https://zackproser.b-cdn.net/images/og-images/the-inference-engine.png" width="100%" alt="The Inference Engine" /></a><br/>
<strong><a href="https://zackproser.com/blog/the-inference-engine">The Inference Engine</a></strong><br/><em>Serving architecture deep-dive</em><br/>Prefill/decode · KV cache & PagedAttention · SARATHI · DistServe
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/the-benchmark"><img src="https://zackproser.b-cdn.net/images/og-images/the-benchmark.png" width="100%" alt="The Benchmark" /></a><br/>
<strong><a href="https://zackproser.com/blog/the-benchmark">The Benchmark</a></strong><br/><em>Measurement methodology</em><br/>MMLU · SWE-bench · Chatbot Arena · Goodhart's law in eval
</td>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/practical-local-inference-aug-2026"><img src="https://zackproser.b-cdn.net/images/og-images/practical-local-inference-aug-2026.png" width="100%" alt="Practical Local Inference" /></a><br/>
<strong><a href="https://zackproser.com/blog/practical-local-inference-aug-2026">Practical Local Inference</a></strong><br/><em>M5 Max + DeepSeek V4 Flash at 30-40 tok/s</em><br/>Workload routing matrix · $17/mo via Gateway
</td>
</tr>
</table>

### The Blueprint Series

17 technical drawings covering the full AI stack — each with SVG schematics, equations, academic citations, and interactive demos:

<table>
<tr>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-transformer"><img src="https://zackproser.b-cdn.net/images/og-images/the-transformer.png" width="100%" alt="The Transformer" /></a><br/><strong><a href="https://zackproser.com/blog/the-transformer">The Transformer</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-tokenizer"><img src="https://zackproser.b-cdn.net/images/og-images/the-tokenizer.png" width="100%" alt="The Tokenizer" /></a><br/><strong><a href="https://zackproser.com/blog/the-tokenizer">The Tokenizer</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-embedding-space"><img src="https://zackproser.b-cdn.net/images/og-images/the-embedding-space.png" width="100%" alt="The Embedding Space" /></a><br/><strong><a href="https://zackproser.com/blog/the-embedding-space">The Embedding Space</a></strong></td>
</tr>
<tr>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-rag-pipeline"><img src="https://zackproser.b-cdn.net/images/og-images/the-rag-pipeline.png" width="100%" alt="The RAG Pipeline" /></a><br/><strong><a href="https://zackproser.com/blog/the-rag-pipeline">The RAG Pipeline</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-diffusion-model"><img src="https://zackproser.b-cdn.net/images/og-images/the-diffusion-model.png" width="100%" alt="The Diffusion Model" /></a><br/><strong><a href="https://zackproser.com/blog/the-diffusion-model">The Diffusion Model</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/choosing-an-llm"><img src="https://zackproser.b-cdn.net/images/og-images/choosing-an-llm.png" width="100%" alt="Choosing an LLM" /></a><br/><strong><a href="https://zackproser.com/blog/choosing-an-llm">Choosing an LLM</a></strong></td>
</tr>
<tr>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-agent-fleet"><img src="https://zackproser.b-cdn.net/images/og-images/the-agent-fleet.png" width="100%" alt="The Agent Fleet" /></a><br/><strong><a href="https://zackproser.com/blog/the-agent-fleet">The Agent Fleet</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-attention-head"><img src="https://zackproser.b-cdn.net/images/og-images/the-attention-head.png" width="100%" alt="The Attention Head" /></a><br/><strong><a href="https://zackproser.com/blog/the-attention-head">The Attention Head</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-autonomy-boundary"><img src="https://zackproser.b-cdn.net/images/og-images/the-autonomy-boundary.png" width="100%" alt="The Autonomy Boundary" /></a><br/><strong><a href="https://zackproser.com/blog/the-autonomy-boundary">The Autonomy Boundary</a></strong></td>
</tr>
<tr>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-guard"><img src="https://zackproser.b-cdn.net/images/og-images/the-guard.png" width="100%" alt="The Guard" /></a><br/><strong><a href="https://zackproser.com/blog/the-guard">The Guard</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/designing-ai-evaluations"><img src="https://zackproser.b-cdn.net/images/og-images/designing-ai-evaluations.png" width="100%" alt="Designing AI Evaluations" /></a><br/><strong><a href="https://zackproser.com/blog/designing-ai-evaluations">Designing AI Evaluations</a></strong></td>
<td align="center" width="33%"><a href="https://zackproser.com/blog/the-workshop"><img src="https://zackproser.b-cdn.net/images/og-images/the-workshop.png" width="100%" alt="The Workshop" /></a><br/><strong><a href="https://zackproser.com/blog/the-workshop">The Workshop</a></strong></td>
</tr>
</table>

[→ View all 17 Blueprints](https://zackproser.com/blog?tag=blueprint)

---

## Interactive Demos

Live tools you can use right now — built into my portfolio site:

<table>
<tr>
<td align="center" width="33%">
<a href="https://zackproser.com/demos/local-vs-cloud-ai-coding"><img src="https://zackproser.b-cdn.net/images/blueprint-the-eval-harness-hero.webp" width="100%" alt="Local vs Cloud Benchmark" /></a><br/>
<strong><a href="https://zackproser.com/demos/local-vs-cloud-ai-coding">Local vs Cloud Benchmark</a></strong><br/><em>60-run evidence explorer</em>
</td>
<td align="center" width="33%">
<a href="https://zackproser.com/demos/tokenize"><img src="https://zackproser.b-cdn.net/images/tokenization-demo-hero.webp" width="100%" alt="Tokenization Lab" /></a><br/>
<strong><a href="https://zackproser.com/demos/tokenize">Tokenization Lab</a></strong><br/><em>BPE pricing calculator</em>
</td>
<td align="center" width="33%">
<a href="https://zackproser.com/demos/rag-visualized"><img src="https://zackproser.b-cdn.net/images/rag-demo-hero.webp" width="100%" alt="RAG Visualized" /></a><br/>
<strong><a href="https://zackproser.com/demos/rag-visualized">RAG Visualized</a></strong><br/><em>Pipeline step-through</em>
</td>
</tr>
<tr>
<td align="center" width="33%">
<a href="https://zackproser.com/demos/embeddings"><img src="https://zackproser.b-cdn.net/images/embeddings-demo-hero.webp" width="100%" alt="Embeddings Explorer" /></a><br/>
<strong><a href="https://zackproser.com/demos/embeddings">Embeddings Explorer</a></strong><br/><em>3D vector space</em>
</td>
<td align="center" width="33%">
<a href="https://zackproser.com/demos/voice-ai"><img src="https://zackproser.b-cdn.net/images/voice-ai-hero.webp" width="100%" alt="Voice AI Pipeline" /></a><br/>
<strong><a href="https://zackproser.com/demos/voice-ai">Voice AI Pipeline</a></strong><br/><em>Meeting intelligence</em>
</td>
<td align="center" width="33%"></td>
</tr>
</table>

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
| [portfolio](https://github.com/zackproser/portfolio) | This site — Next.js 15, 17 Blueprints, 9 demos, 672 articles | — |
| [handwave](https://github.com/zackproser/handwave) | watchOS app controlling Claude Code from your wrist | — |
| [git-xargs](https://github.com/gruntwork-io/git-xargs) | Run commands across many GitHub repos simultaneously | ⭐ 1,086 |
| [cloud-nuke](https://github.com/gruntwork-io/cloud-nuke) | AWS resource cleanup — nuke entire accounts safely | ⭐ 3,121 |
| [cf-terraforming](https://github.com/cloudflare/cf-terraforming) | Generate Terraform from existing Cloudflare config | ⭐ 1,324 |

---

## Speaking

<table>
<tr>
<td align="center" width="50%">
<a href="https://www.youtube.com/watch?v=kwIzRkzO_Z4"><img src="https://img.youtube.com/vi/kwIzRkzO_Z4/hqdefault.jpg" width="100%" alt="DevSecCon 2025 Keynote" /></a><br/>
<strong>DevSecCon 2025</strong><br/><em>Keynote: Walking and Talking in the Woods with AI</em><br/>Voice-first development · Agent autonomy
</td>
<td align="center" width="50%">
<a href="https://www.youtube.com/watch?v=8bjcx5Hkj5w"><img src="https://img.youtube.com/vi/8bjcx5Hkj5w/maxresdefault.jpg" width="100%" alt="Claude Cowork Workshop" /></a><br/>
<strong>WorkOS × Anthropic</strong><br/><em>Claude Cowork GTM Workshop</em><br/>800 registrations · Hands-on build with Lydia from Anthropic
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://zackproser.com/blog/aie-london-skills-at-scale"><img src="https://img.youtube.com/vi/pFsfax19yOM/maxresdefault.jpg" width="100%" alt="Skills at Scale Workshop" /></a><br/>
<strong>AI Engineering London</strong><br/><em>Skills at Scale Workshop (80 min)</em><br/>Claude Code skills across workflows & teams
</td>
<td align="center" width="50%">
<a href="https://www.youtube.com/watch?v=so9l_MwS2yg"><img src="https://img.youtube.com/vi/so9l_MwS2yg/maxresdefault.jpg" width="100%" alt="Untethered Productivity Talk" /></a><br/>
<strong>AI Engineering London</strong><br/><em>Untethered Productivity</em><br/>Staying healthy, creative & shipping in the AI era
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://www.youtube.com/watch?v=V2PuEAeNXUU&t=3765s"><img src="https://img.youtube.com/vi/V2PuEAeNXUU/maxresdefault.jpg" width="100%" alt="Applied AI Showcase" /></a><br/>
<strong>WorkOS Applied AI Showcase</strong><br/><em>Three Learnings from Shipping</em><br/>Interface beats stack · Complete the loop
</td>
<td align="center" width="50%">
<a href="https://www.youtube.com/watch?v=GIwt3P_5b9g"><img src="https://img.youtube.com/vi/GIwt3P_5b9g/maxresdefault.jpg" width="100%" alt="a16z Pinecone Talk" /></a><br/>
<strong>a16z San Francisco</strong><br/><em>From Jupyter Notebooks to Production</em><br/>Pinecone AWS Reference Architecture · ~125 attendees
</td>
</tr>
</table>

[→ All speaking engagements](https://zackproser.com/speaking)

---

## Career

| Role | Company | Years | What I did |
|------|---------|-------|------------|
| **Applied AI** | [WorkOS](https://workos.com) | 2025–present | AI workflows, internal tooling, developer education. Created Claude Cowork workshop with Anthropic. |
| **Staff DevRel** | [Pinecone](https://pinecone.io) | 2023–2025 | RAG pipelines, AWS reference architectures, dev education during the vector DB explosion. Spoke at a16z SF. |
| **Senior Software Engineer** | [Cloudflare](https://cloudflare.com) | 2020–2023 | Joined at ~100 engineers globally. Built `cf-terraforming` (1.3K⭐). APIs, edge infra, dev tools at scale. |
| **Infrastructure Engineer** | [Gruntwork](https://gruntwork.io) | 2018–2020 | Built `git-xargs` (1K⭐), contributed to `cloud-nuke` (3.1K⭐). Multi-account AWS, Terraform, production IaC. |

---

## Reach

**12.4M impressions/year** (Google Search Console) · **104K+ visitors/year** (+82% YoY) · **133K+ page views** (+60%) · **5,000+ newsletter subscribers**

Regularly advising hedge funds and PE firms on AI infrastructure, developer tools, and cloud platforms via AlphaSights, Guidepoint, Tegus, GLG, Coleman.

---

<p align="center">
  <a href="https://zackproser.com">zackproser.com</a> ·
  <a href="https://twitter.com/zackproser">Twitter/X</a> ·
  <a href="https://www.linkedin.com/in/zackproser/">LinkedIn</a> ·
  <a href="https://youtube.com/@zackproser">YouTube</a> ·
  <a href="https://mindonfire.net"><img src="img/mind-on-fire-logo.png" width="16" alt="Mind on Fire"/> mindonfire.net</a>
</p>
