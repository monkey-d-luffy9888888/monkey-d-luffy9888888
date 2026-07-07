# Manikandan Santhosh

**AI Systems Engineer** — I build production AI systems: multi-model extraction pipelines, LoRA fine-tuning workflows, document AI, and real-time intelligence platforms.

Based in India. Open to AI Engineer roles at teams building serious infrastructure.

[![Portfolio](https://img.shields.io/badge/Portfolio-manikandan--portfolio--delta.vercel.app-0f172a?style=flat-square&logo=vercel&logoColor=white)](https://manikandan-portfolio-delta.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manikandan_Santhosh-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manikandan-s-032518285/)
[![Email](https://img.shields.io/badge/Email-maniappu7777@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:maniappu7777@gmail.com)

---

## What I Build

**Document AI & Extraction Pipelines**  
Multi-stage pipelines combining YOLO region detection, Tesseract OCR, and dual-LLM verification to extract structured data from engineering PDFs, CAD drawings, and product specifications. Every LLM output is validated against a Pydantic schema — no silent data corruption in production.

**LLM Fine-Tuning**  
End-to-end fine-tuning pipelines for Google Gemma using LoRA/PEFT. Dataset curation, mixed-precision training on A100, gradient checkpointing, adapter merge, Hugging Face Hub deployment, FastAPI inference endpoint.

**Browser AI Extensions**  
Chrome extensions (Manifest V3) with local or cloud AI backends. Dual-model product data extraction (Perplexity sonar-pro + Gemini), real-time candlestick pattern detection with Binance API, all with JSON schema validation and corrective retry logic.

**Enterprise Automation**  
Full-stack systems handling end-to-end workflows: AI-enriched product data pipelines publishing to Shopify via AWS S3 + Lambda, Excel audit automation with rule-based + LLM validation layers writing PostgreSQL audit trails.

---

## Featured Projects

| Project | Stack | Description |
|---------|-------|-------------|
| [ADM Retail Platform](https://manikandan-portfolio-delta.vercel.app/project/adm-retail-platform) | FastAPI · React · PostgreSQL · AWS · Shopify | 5-stage AI pipeline: supplier Excel → enrich → classify → review → Shopify publish |
| [DTLP Data Extraction Extension](https://manikandan-portfolio-delta.vercel.app/project/dtlp-data-extraction-extension) | Chrome MV3 · Perplexity sonar-pro · Gemini | Dual-LLM product attribute extraction with schema validation and IndexedDB storage |
| [AI Trading Extension](https://manikandan-portfolio-delta.vercel.app/project/ai-trading-extension) | Flask · Binance API · Chrome MV3 | 14-pattern candlestick detector with local-first Flask backend and AI trade signals |
| [Gemma Fine-Tuning](https://manikandan-portfolio-delta.vercel.app/experience/gemma-fine-tuning) | LoRA · PEFT · Colab A100 · HF Hub | Full LoRA fine-tuning pipeline: dataset → bf16 training → merge → FastAPI inference |
| [PDF + CAD AI Extractor](https://manikandan-portfolio-delta.vercel.app/experience/pdf-cad-ai-extractor) | YOLO · Tesseract · FastAPI | Custom YOLO region detection → region-specific OCR → AI structuring layer |
| [Enterprise Audit AI](https://manikandan-portfolio-delta.vercel.app/experience/enterprise-audit-ai) | Python · OpenPyXL · LLMs · PostgreSQL | Two-layer validation: rule-based + LLM contextual error detection on Excel datasets |

---

## Stack

```
AI / ML        Python · Transformers · LoRA/PEFT · Gemma · Tesseract · YOLO (Ultralytics)
               Perplexity sonar-pro · Google Gemini · LLM Orchestration · JSON Schema Validation

Backend        FastAPI · Flask · PostgreSQL · SQLAlchemy · Pydantic · OpenPyXL · Pandas
               REST APIs · WebSocket · Async I/O

Frontend       React 19 · TypeScript · Vite · TailwindCSS · Framer Motion
               Chrome Extensions (Manifest V3) · IndexedDB

Infrastructure Docker · Google Cloud Platform · AWS S3 · AWS Lambda · Hugging Face Hub
               Git · GitHub Actions
```

---

## Engineering Approach

I treat schema validation on LLM outputs as non-negotiable — silent malformed data in production is harder to debug than a noisy retry loop. I prefer local-first architectures for tools that handle sensitive data (trading signals, proprietary documents). I use deterministic rule-based logic where it covers the problem precisely, and reach for LLMs only where deterministic approaches break down.

Full engineering write-ups for every project at [manikandan-portfolio-delta.vercel.app](https://manikandan-portfolio-delta.vercel.app).

---

*Available for AI Engineer roles · India · Open to remote*
