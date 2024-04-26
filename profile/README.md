# Graphlit

[![npm version](https://badge.fury.io/js/graphlit-client.svg)](https://badge.fury.io/js/graphlit-client) [![PyPI version](https://badge.fury.io/py/graphlit-client.svg)](https://badge.fury.io/py/graphlit-client)

If you're building AI copilots, chatbots or other vertical AI apps, [Graphlit](https://www.graphlit.com) simplifies and accelerates your development.

Compared to existing Open Source solutions like LangChain or LlamaIndex, which require the DIY combination of vector databases, LLM embeddings, cloud storage and data pipelines, our managed Graphlit platform handles your AI and data infrastructure for you.

No need to be limited by the OpenAI Assistants API - no file size limits (on all tiers), or storage limitations (on the Growth tier).

💸 Graphlit is **free** to use, up to 1GB of content, and [paid plans](https://www.graphlit.com/#pricing) start at $49/mo + credit usage.

💡 [Signup today](https://portal.graphlit.dev/), and you can be ingesting data and having LLM conversations within minutes.

With integrated web scraping, Graphlit ingests existing websites by sitemap. With built-in audio transcription, it indexes podcasts, videos and meeting recordings. Any format of unstructured data will be made searchable, via metadata filtering and text and image embeddings. Slack, Notion, Google Mail and Microsoft Outlook email are supported as data feeds. Create automated LLM-generated alerts on people, places, companies or topics found in your content.

Use any content with RAG conversations, even images or websites described with the GPT-4 Vision model.

## Example

```python
from graphlit import Graphlit
from graphlit_api import *

await graphlit.client.ingest_uri(
  uri="https://www.graphlit.com"
)

response = await graphlit.client.prompt_conversation(
  prompt="How can Graphlit accelerate my Generative AI app development?"
)

message = response.prompt_conversation.message.message

print(message)
```

![Accelerate your Generative AI app development](https://github.com/graphlit/.github/assets/13594550/c0142ee5-3cf1-4f30-a14f-1d2c31ed396b)

### Features:

✅ API first: Made for app developers, not data scientists

✅ Graph-based: via LLMs, we build a knowledge graph from your unstructured data

✅ Multi-modal RAG: not just PDFs and web pages, we support audio, video and images

✅ Model-agnostic: we handle prompted retrieval with models from OpenAI, Anthropic, Meta, Mistral, etc.

✅ Managed cloud-native platform: fully automated unstructured data ETL pipelines

✅ No assembly required: no need for Langchain, Pinecone, S3, etc.

✅ Built-in multi-tenancy, semantic search, storage and workflow automation

### ✍️ Read more about use cases for Graphlit:

- [Slack audio alerts](https://www.graphlit.com/blog/slack-audio-alerts)
- [AI-generated podcasts](https://www.graphlit.com/blog/gpt-to-audio)
- [GPT-4 Vision for image analysis](https://www.graphlit.com/blog/multimodal-content-publishing)
- [LLM tools for data extraction](https://www.graphlit.com/blog/address-extraction)
- [Reddit market intelligence with LLM](https://www.graphlit.com/blog/exploring-market-intelligence-data-with-llms)

### Try one of our sample applications

- [Upload and Chat with Files, with Citations](https://graphlit-samples-chat-file-citations.streamlit.app/)
- [Extract Website Topics](https://graphlit-samples-extract-website-topics.streamlit.app/)
- [Publish GitHub Issues Report](https://graphlit-samples-publish-issues-feed.streamlit.app/)

All sample applications can be found in our [GitHub Repo](https://github.com/graphlit/graphlit-samples).

🔥 Get started with our [API documentation](https://docs.graphlit.dev/).

🆕 See our [changelog](https://changelog.graphlit.dev/) for all the latest features.


We want to learn how we can help you build your AI apps faster with Graphlit.
