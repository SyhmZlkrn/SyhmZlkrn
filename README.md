## Muhammad Syahmi Zulkarnain

Software engineer building LLM applications: RAG, agentic systems, and the full-stack products around them.

Final-year Software Engineering student at Universiti Tenaga Nasional (UNITEN), graduating January 2027. Based in Kuala Lumpur, open to graduate software and AI engineering roles, remote or with relocation.

[LinkedIn](https://linkedin.com/in/syhmzlkrn) · [Email](mailto:muhdsyahmiz2004@gmail.com)

---

### Currently

- **Software & AI Engineer (part-time contract), Wajie Ibrahim.** Building a multi-tenant RAG assistant and a generative AI design pipeline for a fashion retail brand, and shipped a consultation booking redesign on their Shopify store.

- **Previously:
- **System Analyst Intern, Tenaga Nasional Berhad (Jun – Aug 2026).** Built a map-based inspection dashboard (React, .NET Core, PostGIS) and led Power BI reporting for two cutover programmes.
- - **AI Annotator & Trainer, micro1.** Ranking model responses for RLHF preference data and labelling text, code and multimodal data against quality rubrics.

### Selected work

**[ToneHound](https://github.com/SyhmZlkrn/ToneHound)** · Python, PyTorch, C++, JUCE\
Windows app and VST3 plugin that suggests Neural Amp Modeler captures matching the guitar tone in a song passage. Separates the guitar with Demucs and runs similarity search over MERT embeddings. A LoRA-tuned matcher scored 58.0% top-5 against 61.4% for the frozen baseline, so it ships as an optional pilot rather than the default. ML runs in worker processes, off the real-time audio thread.

**[MyFlora](https://github.com/SyhmZlkrn/MyFlora)** · Kotlin, Jetpack Compose, TensorFlow Lite\
Android plant identification and care app (final year project). Identifies 1,081 species offline with a MobileNetV3-Small model trained on PlantNet-300K and int8-quantised for on-device use, plus disease diagnosis and weather-aware care schedules.

**RAG Knowledge Assistant** · Next.js, TypeScript, Supabase, pgvector · *client work, private*\
Bilingual (Malay and English) assistant over a business's own files and synced Shopify, Dropbox and Google Drive sources, citing sources in every answer. Hybrid retrieval (pgvector plus full-text, reciprocal rank fusion) under Postgres row-level security, a model router for hard questions, a semantic cache, 9 tools, and LLM-as-judge evaluation.

**Generative AI Design Pipeline** · Next.js, Supabase, OpenAI, FLUX.2 · *client work, private*\
Five-stage pipeline from a customer's request to a generated garment design: RAG retrieval, a schema-validated LLM design spec, then image generation. Atomic Postgres quotas, rate limiting, prompt-injection guardrails, and CIEDE2000 colour matching against 157 in-stock fabrics.

### Stack

| | |
|---|---|
| **LLM & GenAI** | RAG, embeddings, hybrid search, tool calling, MCP, structured outputs, LLM evaluation, OpenAI and Claude APIs |
| **Machine learning** | PyTorch, TensorFlow / TFLite, LoRA fine-tuning, quantisation, Pandas, NumPy |
| **Languages** | Python, TypeScript, JavaScript, Kotlin, C#, C++, Java, SQL |
| **Web & mobile** | Next.js, React, Vite, Node.js, .NET Core, Tailwind CSS, Shopify Liquid, Jetpack Compose |
| **Data & cloud** | PostgreSQL, pgvector, PostGIS, Supabase, Power BI, Azure, Docker, Linux |

### Also

- 1st place, CLICQ DIV:IDE Capture The Flag (Mar 2026); finalist, Hack@10 International CTF (Mar 2026)
- Generative AI with LLMs (DeepLearning.AI) · Microsoft AI & ML Engineering · IBM Data Science
- Former President of Anak Seni Tenaga Nasional (ASTENA), leading 60+ members across 5 performance divisions
