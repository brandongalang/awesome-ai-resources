# 📚 Awesome AI Resources

A curated, opinionated list of AI tools, platforms, and libraries I use or track. Categorized with pros/cons so others can adopt, compare, or extend.

## 🚀 Index

- [Conversational & Code Assistants](#conversational--code-assistants)
- [Productivity / Studio Platforms](#productivity--studio-platforms)
- [Experimental & Niche Tools](#experimental--niche-tools)
- [Interesting & Emerging](#interesting--emerging)
- [Valuable Repositories](#valuable-repositories)
- [Contributing](#contributing)
- [License](#license)

## Conversational & Code Assistants

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| ChatGPT | [OpenAI](https://openai.com/chatgpt) | General-purpose LLM via web & API | Huge plugin ecosystem; strong code generation; easy to use | Closed-source; data residency concerns; subscription cost |
| Claude | [Anthropic](https://claude.ai) | Safety-focused conversational AI | Excellent guardrails; long context; thoughtful responses | Fewer integrations; pricing varies; slower at times |
| Claude Desktop | [Anthropic](https://claude.ai/download) | Native app experience for Claude | Local windowed app; faster access | Platform-dependent; feature parity unclear |
| Claude Code | [Anthropic](https://docs.anthropic.com/en/docs/claude-code) | Claude optimized for code tasks | Handles complex code; good at step-by-step reasoning | Context limits; still hallucinates |
| Gemini | [Google Gemini](https://gemini.google.com) | Multimodal Google LLM | Tight Workspace integration; vision+text support | Opaque pricing; limited 3rd-party plugins |
| Gemini CLI | [GitHub](https://github.com/google/generative-ai-cli) | Command-line interface for Gemini | Developer-friendly; scriptable interactions | In flux; needs API key; CLI complexity for novices |
| Granola AI | [Granola](https://granola.ai) | Enterprise-grade chat layer | Web embeds; analytics; fine-tunable | New entrant; vendor lock-in risk |
| Genspark | [Genspark](https://genspark.ai) | Lightweight code assistant | VS Code integration; code suggestions | Narrow language focus; sporadic updates |
| Notion AI | [Notion AI](https://notion.so/ai) | Note-taking + summarization | Seamless in-doc drafting; meeting roadmap help | Proprietary format; export limitations |
| NotebookLM | [Google NotebookLM](https://notebooklm.google.com) | Research-focused assistant | Cite-able snippets; doc-grounded answers | Early access; limited customization; privacy questions |
| Task Master AI | [GitHub](https://github.com/brandongalang/task-master-ai) | Task extraction & automation | Auto-creates to-dos; calendar/Asana integration | Over-automation risk; setup complexity |

## Productivity / Studio Platforms

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Graphiti | [GitHub](https://github.com/graphiti-ai/graphiti) | Personal knowledge graph with memory | Vector-search notes; knowledge embedding; persistent memory | Early-stage; integration gaps |
| Mem0 | [GitHub](https://github.com/mem0ai/mem0) | Memory layer for AI applications | Persistent memory; easy integration | Early-stage; limited enterprise features |
| Claude Code Requirements Builder | [GitHub](https://github.com/brandongalang/claude-code-requirements-builder) | Generates structured requirements from prompts | Automates early spec writing; reduces ambiguity | Requires Claude API key; prompt quality sensitive |

## Experimental & Niche Tools

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| RepoPrompt | [GitHub](https://github.com/brandongalang/repo-prompt) | LLM-powered codebase search/summarizer | Instant code search; repo insights | Struggles with large repos; security considerations |
| Context7 | [GitHub](https://github.com/upstash/context7) | Retrieval-augmented context framework for LLMs | Fully open-source; Upstash integration; simplifies RAG | Tied to Upstash; needs Vector DB setup; early-stage maturity |

## Interesting & Emerging

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| SuperClaude | [GitHub](https://github.com/jjohare/SuperClaude) | Extended Claude fork with massive context | Huge system prompt; extensive capabilities | Unclear usage; complex setup; huge system prompt makes it hard to use immediately |

## Valuable Repositories

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| DSPy | [GitHub](https://github.com/stanfordnlp/dspy) | Data-science pipelines & feature engineering | Clean API; easy to integrate; accelerates ML | Small community; minimal maintenance |
| BAML | [GitHub](https://github.com/BoundaryML/baml) | Bayesian ML / AML framework | Strong uncertainty quantification; modern design | Steep learning curve; niche use-cases |

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. When adding new tools:

1. Follow the existing table format
2. Include honest pros and cons
3. Verify links are working
4. Categorize appropriately

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Last updated: $(date +%Y-%m-%d)*