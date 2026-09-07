## Haikal Fairuzi Maulana

Software and AI engineer based in Banda Aceh, Indonesia. I build language
models and the systems around them — fine-tuning, retrieval, and the backends
that put them in front of real users.

Most of my current work is on **Indonesian-language AI**: models that reason
in Bahasa Indonesia without drifting into English, trained on hardware people
actually own rather than a data-centre cluster.

### What I've built

| Project | What it is |
|---|---|
| [Legal AI Chatbot](https://github.com/haikalmol/Chat-AI-Local-for-Legal-Company-Team) | Indonesian labour-law assistant. LoRA fine-tuning → GRPO reasoning RL → RAG with hybrid retrieval, HyDE, and a cross-encoder reranker. Whole pipeline runs on an 8GB RTX 4060 Ti. |
| [SkillMap AI](https://github.com/haikalmol/SkillMap-AI) | Career-readiness scoring from CVs — spaCy NER plus a TensorFlow model, served through FastAPI. Built with a team of six. |
| [SmartPricing XAI](https://github.com/haikalmol/smartpricing-xai) | Explainable dynamic pricing. Weather and location signals adjust the price, but a cost floor is enforced so a recommendation can never go below margin. |
| JakLom | Muslim-friendly tourism platform for Aceh, on Google Play. React Native + self-hosted Supabase. Funded under BIMA 2026. |

### Models on Hugging Face

- [`qwen2.5-7b-legal-id-sft`](https://huggingface.co/haikal1623/qwen2.5-7b-legal-id-sft) — supervised fine-tune on Indonesian legal instruction data
- [`qwen2.5-7b-legal-id-grpo`](https://huggingface.co/haikal1623/qwen2.5-7b-legal-id-grpo) — reasoning model trained with GRPO and four custom reward functions, including one that penalises drifting out of Bahasa Indonesia

### Working with

Python · PyTorch · Transformers · Unsloth · TRL · LangChain · FastAPI ·
PostgreSQL · Supabase · React Native · TypeScript · Docker

### Contact

Open to contract and retainer work on LLM fine-tuning, RAG systems, and
full-stack delivery.

- Web — [creagen.co](https://creagen.co)
- LinkedIn — [haikal-fairuzi-maulana](https://www.linkedin.com/in/haikal-fairuzi-maulana-4227ab213)
- Email — haikalfairuzim@gmail.com
