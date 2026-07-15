### Hi, I'm Fernando 👋

Software engineer (7+ yrs) moving deep into **AI/LLM engineering**, with a focus on **evaluation-first RAG and production LLM systems** — building systems whose quality you can actually *measure*, not just demo.

My background is a bit unusual and I lean into it: a **Chemical Engineering** degree and a postgrad in **Enterprise Software Architecture**, then years shipping full-stack software. That mix means I'm comfortable with both the systems-design side and the domain-rigor side of hard problems — which is exactly what serious LLM work needs.

---

#### 🔬 Featured: an evaluation-first RAG pipeline

**[rag-pipeline](https://github.com/FernandoSanabria/rag-pipeline)** — a production RAG system for industrial-equipment-safety documents (OSHA / EPA / NIOSH regs, chemical SDS, equipment manuals), built **evaluation-first**: the measurement harness came *before* any retrieval or generation code, and every change was measured against it one variable at a time.

- Measured **v1 → v4**: faithfulness 0.71 → 0.97, answer-correctness 0.40 → 0.57, each change pre-registered with a falsifiable prediction
- **Killed two more-complex retrieval ideas with evidence** before building them — the shipped pipeline is *simpler* than the one I planned
- Live behind a **FastAPI service** with a typed citation contract · CI/CD (branch-protected, gated tests, auto-deploy) · [**live demo**](https://equip-docs-rag-api.onrender.com)

I wrote up what I learned — including the parts where my own metrics lied to me:

- 📝 **[Evaluation-first RAG: what happened when my own metrics lied to me](https://medium.com/@ing.fernandosanabria/evaluation-first-rag-what-happened-when-my-own-metrics-lied-to-me-6810744f88ec)** — the build story: pre-registration, reading the artifact over trusting the score, and the four times the measurement apparatus lied
- 💸 **[The $1.53 RAG pipeline](https://medium.com/@ing.fernandosanabria/the-1-53-rag-pipeline-2b1e5f2d029d)** — what it actually cost, and why most of the spend was *measuring* the system, not building it

---

#### 🛠️ Working with
`Python` · `RAG / retrieval` · `RAGAS eval` · `FastAPI` · `OpenAI` · `Pinecone` · `LangChain / LangSmith` · `Docker` · `CI/CD`

#### 🔗 Elsewhere
[LinkedIn](https://www.linkedin.com/in/edwin-fernando-sanabria-695060166/) · [Medium](https://medium.com/@ing.fernandosanabria)
