# 🧠 Graphlit – The semantic memory platform for AI

**Context engineering for developers.**

Ingest any content, extract what matters, give your AI the memory it needs.

[![Start Free](https://img.shields.io/badge/Start_Free-5_Minutes_to_First_Search-6366f1?style=for-the-badge)](https://portal.graphlit.dev/)
[![Documentation](https://img.shields.io/badge/Docs-docs.graphlit.dev-0ea5e9?style=for-the-badge)](https://docs.graphlit.dev)
[![Discord](https://img.shields.io/discord/1095189481335816243?label=Discord&logo=discord&style=for-the-badge)](https://discord.gg/ygFmfjy3Qx)

---

## What is Graphlit?

Graphlit is a **cloud-native platform** that gives AI applications semantic memory. Not just vector search – real knowledge retrieval with context, relationships, and understanding.

**One API** for the complete stack: content ingestion, extraction, enrichment, storage, and retrieval.

```typescript
import { Graphlit } from "graphlit-client";

const client = new Graphlit();

// Ingest and automatically extract entities, relationships
await client.ingestUri("https://example.com/report.pdf");

// Semantic search across all your content
const results = await client.queryContents({
  search: "Q4 revenue concerns enterprise pricing"
});

// Chat with your data using RAG
await client.streamAgent(
  "What are the key pricing concerns from enterprise customers?",
  (event) => console.log(event.message)
);
```

---

## Why Graphlit?

Building semantic memory is hard. Maintaining it in production is harder.

| Typical Solutions | 🚀 Graphlit |
|---|---|
| Just vectors – no semantic memory | **Semantic memory platform** |
| Basic pipelines | **Complete ingestion-to-retrieval stack** |
| Limited multimodal or text-only | **True multimodal** from day one |
| New to production | **Years of production hardening** |

**Save weeks of engineering time.** Skip the infrastructure. Ship features, not glue code.

---

## ✨ What You Get

### 📥 Ingest Anything
- **Documents**: PDF, DOCX, PPTX, Excel, Markdown
- **Media**: Audio transcription, video processing, image analysis
- **Web**: Scraping, RSS feeds, sitemaps
- **Platforms**: Slack, Gmail, Notion, GitHub, Jira, Linear, SharePoint, and more
- **Cloud Storage**: S3, Azure Blob, Google Drive, Dropbox, OneDrive, Box

### 🧠 Automatic Extraction
- Entity recognition and linking
- Relationship mapping
- OCR and visual object detection
- Audio transcription with speaker diarization
- Automated summarization

### 🔍 Smart Retrieval
- Semantic search (vector + hybrid)
- Knowledge graph queries
- RAG-powered conversations
- Multi-tenant filtering
- Context-aware results

### 🤖 Best-in-Class LLM Support
**OpenAI** • **Anthropic** • **Google** • **xAI** • **Deepseek** • **Groq** • **Mistral** • **Cohere** • **Cerebras** • **AWS Bedrock**

All models support tool calling, streaming, and reasoning modes.

---

## 🔌 MCP-Native Integration

Connect Graphlit to your favorite AI coding tools:

**Cursor** • **VS Code** • **Windsurf** • **Claude Desktop** • **Claude Code** • **ChatGPT**

```bash
npx -y graphlit-mcp-server
```

[Learn more →](https://github.com/graphlit/graphlit-mcp-server)

---

## 🛠️ SDKs & Resources

### Official SDKs
- [**TypeScript/JavaScript**](https://github.com/graphlit/graphlit-client-typescript) – `npm install graphlit-client`
- [**Python**](https://github.com/graphlit/graphlit-client-python) – `pip install graphlit-client`
- [**C# / .NET**](https://github.com/graphlit/graphlit-client-dotnet) – `dotnet add package Graphlit.Client`

### Documentation & Learning
- 📖 [**Documentation**](https://docs.graphlit.dev) – Complete API reference and guides
- 🎥 [**YouTube Channel**](https://www.youtube.com/@graphlit) – Video tutorials and demos
- 💬 [**Discord Community**](https://discord.gg/ygFmfjy3Qx) – Get help and share ideas
- 🌐 [**Website**](https://www.graphlit.com) – Platform overview and pricing

### Sample Applications
- [**Sample Apps**](https://github.com/graphlit/graphlit-samples) – Production-ready examples
- [**MCP Server**](https://github.com/graphlit/graphlit-mcp-server) – Model Context Protocol integration

---

## 🚀 Get Started

**Free tier includes:**
- ✓ 1GB storage • 1K content items • 3 feeds • 100 conversations
- ✓ All content types (PDFs, audio, video, web pages)
- ✓ Full API access
- ✓ Community support

[**Start building in 5 minutes →**](https://portal.graphlit.dev/)

No credit card required. No infrastructure to manage.

---

## 💡 Use Cases

- **AI Agents & Copilots** – Give your AI memory and context
- **Knowledge Management** – Build searchable repositories from unstructured data
- **Document Intelligence** – Extract insights from PDFs, reports, contracts
- **Customer Support** – RAG-powered chatbots over your documentation
- **Research Tools** – Semantic search across academic papers, articles
- **Media Analysis** – Transcribe and analyze audio/video content
- **Content Platforms** – Automated ETL for LLM training data

---

## 🏢 Production-Ready

- **Multi-tenant** architecture with RBAC
- **Encrypted at rest** and in transit
- **Usage-based pricing** – pay only for what you use
- **Serverless** – no infrastructure to deploy
- **SOC 2 & SLA** available on Growth tier (Coming Soon)

---

<div align="center">

### Ready to give your AI semantic memory?

[**Get Started Free**](https://portal.graphlit.dev/) • [**Read the Docs**](https://docs.graphlit.dev) • [**Join Discord**](https://discord.gg/ygFmfjy3Qx)

**Built by developers, for developers.** 🚀

</div>
