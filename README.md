# 📚 Awesome AI Resources

A curated, opinionated list of AI tools, platforms, and libraries I use or track. Categorized with pros/cons so others can adopt, compare, or extend.

## 🚀 Index

- [Conversational AI](#conversational-ai)
- [Code & Development](#code--development)
- [Command Line & Automation](#command-line--automation)
- [Speech & Audio](#speech--audio)
- [Productivity & Knowledge](#productivity--knowledge)
- [Experimental & Research](#experimental--research)
- [Developer Libraries & Frameworks](#developer-libraries--frameworks)
- [Contributing](#contributing)
- [License](#license)

## Conversational AI

General-purpose conversational AI models and interfaces for reasoning, research, and general assistance.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| ChatGPT | [OpenAI](https://openai.com/chatgpt) | General-purpose LLM via web & API | Huge plugin ecosystem; strong reasoning; easy to use | Closed-source; data residency concerns; subscription cost |
| Claude | [Anthropic](https://claude.ai) | Safety-focused conversational AI | Excellent guardrails; long context; thoughtful responses | Fewer integrations; pricing varies; slower at times |
| Claude Desktop | [Anthropic](https://claude.ai/download) | Native app experience for Claude | Local windowed app; faster access; system integration | Platform-dependent; feature parity unclear |
| Gemini | [Google Gemini](https://gemini.google.com) | Multimodal Google LLM | Tight Workspace integration; vision+text support | Opaque pricing; limited 3rd-party plugins |
| Granola AI | [Granola](https://granola.ai) | Enterprise-grade chat layer | Web embeds; analytics; fine-tunable | New entrant; vendor lock-in risk |
| NotebookLM | [Google NotebookLM](https://notebooklm.google.com) | Research-focused assistant | Cite-able snippets; doc-grounded answers | Early access; limited customization; privacy questions |

## Code & Development

IDEs, coding assistants, and specialized development environments with AI integration.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Claude Code | [Anthropic](https://docs.anthropic.com/en/docs/claude-code) | Claude optimized for code tasks | Handles complex code; good at step-by-step reasoning | Context limits; still hallucinates |
| Cursor | [Cursor](https://cursor.com) | AI-first code editor (VS Code fork) | Deep codebase understanding; multi-file edits; excellent autocomplete | $20/month for Pro; requires internet; some features locked to custom models |
| Genspark | [Genspark](https://genspark.ai) | Lightweight code assistant | VS Code integration; code suggestions | Narrow language focus; sporadic updates |

## Command Line & Automation

Terminal-based AI agents and CLI tools for development automation and task management.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Gemini CLI | [GitHub](https://github.com/google/generative-ai-cli) | Command-line interface for Gemini | Developer-friendly; scriptable interactions | In flux; needs API key; CLI complexity for novices |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | AI software development agent for terminal | Full development capabilities; open-source; no Docker required | Complex setup; single-user only; requires powerful models |
| OpenCode | [GitHub](https://github.com/opencode-ai/opencode) | Provider-agnostic AI coding agent | Terminal-first design; supports multiple AI providers; LSP integration | Early stage; Go-based; limited documentation |
| Task Master AI | [GitHub](https://github.com/brandongalang/task-master-ai) | Task extraction & automation | Auto-creates to-dos; calendar/Asana integration | Over-automation risk; setup complexity |
| Goose | [GitHub](https://github.com/block/goose) | Open-source AI development agent by Block | Beyond code suggestions; executes & tests code; works with any LLM; MCP support | Requires LLM API keys; resource intensive; newer project |

## Speech & Audio

Voice-to-text transcription and audio processing tools for AI-powered dictation and transcription.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| MacWhisper | [Gumroad](https://goodsnooze.gumroad.com/l/macwhisper) | Privacy-focused transcription app for macOS | On-device processing; meeting recording; speaker recognition; 100+ languages | macOS only; $39.99 one-time; requires 8GB+ RAM |
| SuperWhisper | [SuperWhisper](https://superwhisper.com) | AI-powered voice-to-text for macOS | System-wide dictation; context-aware; translation; works offline | macOS only; freemium model; limited free tier |

## Productivity & Knowledge

Note-taking, knowledge management, and productivity platforms with AI integration.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Notion AI | [Notion AI](https://notion.so/ai) | Note-taking + summarization | Seamless in-doc drafting; meeting roadmap help | Proprietary format; export limitations |
| Graphiti | [GitHub](https://github.com/graphiti-ai/graphiti) | Personal knowledge graph with memory | Vector-search notes; knowledge embedding; persistent memory | Early-stage; integration gaps |
| Mem0 | [GitHub](https://github.com/mem0ai/mem0) | Memory layer for AI applications | Persistent memory; easy integration | Early-stage; limited enterprise features |
| Claude Code Requirements Builder | [GitHub](https://github.com/brandongalang/claude-code-requirements-builder) | Generates structured requirements from prompts | Automates early spec writing; reduces ambiguity | Requires Claude API key; prompt quality sensitive |
| Vibe Kanban | [Vibe](https://vibe.us) | Interactive whiteboard with Kanban features | Real-time collaboration; visual workflow; integrates with Jira/Trello | Hardware-dependent; enterprise pricing; primarily for teams |
| Glass | [GitHub](https://github.com/pickle-com/glass) | Ambient AI assistant to explore | Real-time assistance; exploration-focused; ambient computing | Early experimental stage; limited documentation; requires setup |

## Experimental & Research

Cutting-edge tools and research projects that are still in active development or experimental phases.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| RepoPrompt | [GitHub](https://github.com/brandongalang/repo-prompt) | LLM-powered codebase search/summarizer | Instant code search; repo insights | Struggles with large repos; security considerations |
| Context7 | [GitHub](https://github.com/upstash/context7) | Retrieval-augmented context framework for LLMs | Fully open-source; Upstash integration; simplifies RAG | Tied to Upstash; needs Vector DB setup; early-stage maturity |
| SuperClaude | [GitHub](https://github.com/jjohare/SuperClaude) | Extended Claude fork with massive context | Huge system prompt; extensive capabilities | Unclear usage; complex setup; huge system prompt makes it hard to use immediately |

## Developer Libraries & Frameworks

APIs, SDKs, and underlying technologies for building AI-powered applications and workflows.

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