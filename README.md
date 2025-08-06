# 📚 Awesome AI Resources

A curated, opinionated list of AI tools, platforms, and libraries I use or track. Categorized with pros/cons so others can adopt, compare, or extend.

## 🚀 Index

- [Conversational AI](#conversational-ai)
- [Code & Development](#code--development)
- [MCP Servers](#mcp-servers)
- [Command Line & Automation](#command-line--automation)
- [Speech & Audio](#speech--audio)
- [Productivity & Knowledge](#productivity--knowledge)
- [Experimental & Research](#experimental--research)
- [Asynchronous Agent Workspaces](#asynchronous-agent-workspaces)
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
| Serena | [GitHub](https://github.com/oraios/serena) | Enhanced Claude Code experience | Adds features to Claude Code; improved context handling | Requires Claude Code; additional setup needed |
| RepoPrompt | [GitHub](https://github.com/id-2/repoprompt) | Repository context generator for AI | Optimized for Claude; XML formatting; file selection | CLI-only; manual file selection needed |
| Claude Code Specs Generator | [GitHub](https://github.com/kellemar/claude-code-specs-generator) | AWS Kiro spec approach for Claude Code | Generates structured specs; follows AWS best practices; improves code quality | Requires setup; AWS-specific methodology |
| Claude Code Proxy | [GitHub](https://github.com/fuergaosi233/claude-code-proxy) | Proxy server for Claude Code with OpenAI-compatible APIs | Multi-provider support; full API compatibility; streaming responses; function calling | Requires proxy setup; additional complexity layer |

## MCP Servers

Model Context Protocol (MCP) servers that extend AI capabilities with specialized tools and integrations.

### Browser & Testing

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Puppeteer MCP | [GitHub](https://github.com/modelcontextprotocol/servers) | Browser automation through Puppeteer | Real browser control; screenshot capture; JavaScript execution | Requires headless browser; resource intensive |
| Playwright MCP | [GitHub](https://github.com/microsoft/playwright-mcp) | Browser automation using Playwright | Accessibility tree interaction; cross-browser; deterministic | Microsoft dependency; setup complexity |
| Octomind MCP | [GitHub](https://github.com/OctoMind-dev/octomind-mcp) | E2E testing platform integration | Auto-test generation; failure analysis; auto-fix | Requires Octomind account; testing-focused only |
| Stagehand MCP | [GitHub](https://github.com/browserbase/mcp-server-browserbase) | AI browser automation with Browserbase | Cloud browser control; Gemini 2.0 Flash integration; production-ready | Requires Browserbase account; API key needed; cloud dependency |

### Context & Documentation

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Context7 | [GitHub](https://github.com/upstash/context7) | Live documentation and API reference | Up-to-date docs; prevents hallucination; version-specific | Upstash dependency; documentation-focused |
| Consult7 | [GitHub](https://github.com/szeider/consult7) | Large context analysis via external LLMs | Handles massive codebases; multiple provider support | Requires high-context models; API costs |

### Mobile & Device Integration

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Mobile MCP | [GitHub](https://github.com/mobile-next/mobile-mcp) | iOS/Android automation and testing | Real device control; emulator support; cross-platform | iOS support incomplete; device setup required |
| React Native Debugger MCP | [GitHub](https://github.com/twodoorsdev/react-native-debugger-mcp) | React Native debugging integration | Metro bundler connection; live error tracking | React Native specific; requires RN setup |

### Development & Project Management

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Taskmaster MCP | [GitHub](https://github.com/eyaltoledano/claude-task-master) | AI-powered task management system | PRD parsing; intelligent task breakdown; research mode | Requires multiple API keys; complex setup |
| Linear MCP | [Linear](https://mcp.linear.app/sse) | Linear project management integration | Official Linear support; issue tracking; project updates | Linear account required; hosted service |
| mcp-use | [GitHub](https://github.com/mcp-use/mcp-use) | Universal MCP server connector and agent builder | Connect any LLM to any MCP server; multi-server agent support; open source | Python/TypeScript specific; requires LangChain; early stage |

### Memory & Search

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Memory MCP | [GitHub](https://github.com/doobidoo/mcp-memory-service) | Long-term memory with semantic search | ChromaDB integration; persistent context; semantic search | ChromaDB dependency; storage overhead |
| ChunkHound | [GitHub](https://github.com/ofriw/chunkhound) | Semantic code search and RAG | Local-first; privacy-focused; regex + semantic search | Self-hosted embeddings; setup complexity |

### AI & Media

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| OpenAI Image MCP | [GitHub](https://github.com/SureScaleAI/openai-gpt-image-mcp) | Image generation and editing | GPT-4o vision; text-to-image; aspect ratio control | OpenAI API costs; image generation limits |
| Interactive Feedback MCP | [GitHub](https://github.com/noopstudios/interactive-feedback-mcp) | Human-in-the-loop workflows | Reduces API calls; confirmation prompts; improved accuracy | Requires human interaction; workflow interruption |

### Development Tools

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Cursor-DB MCP | [GitHub](https://github.com/jbdamask/cursor-db-mcp) | Cursor chat history and project access | SQLite database access; chat history exploration | Cursor-specific; privacy considerations |
| Octocode MCP | [Octocode](https://octocode.muvon.io/) | AI-powered code intelligence and repository analysis | Advanced GitHub/npm exploration; intelligent caching; persistent memory; semantic code search | Requires API keys; complex setup for advanced features |

## Command Line & Automation

Terminal-based AI agents and CLI tools for development automation and task management.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| Gemini CLI | [GitHub](https://github.com/google/generative-ai-cli) | Command-line interface for Gemini | Developer-friendly; scriptable interactions | In flux; needs API key; CLI complexity for novices |
| OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | AI software development agent for terminal | Full development capabilities; open-source; no Docker required | Complex setup; single-user only; requires powerful models |
| OpenCode | [GitHub](https://github.com/opencode-ai/opencode) | Provider-agnostic AI coding agent | Terminal-first design; supports multiple AI providers; LSP integration | Early stage; Go-based; limited documentation |
| Crush CLI | [GitHub](https://github.com/crush-dev/crush) | Enhanced OpenCode with sub-agent support | Same codebase as OpenCode; sub-agent orchestration; advanced workflow management | Early stage; additional complexity; documentation may lag behind features |
| Task Master AI | [GitHub](https://github.com/brandongalang/task-master-ai) | Task extraction & automation | Auto-creates to-docs; calendar/Asana integration | Over-automation risk; setup complexity |
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
| SuperClaude | [GitHub](https://github.com/jjohare/SuperClaude) | Extended Claude fork with massive context | Huge system prompt; extensive capabilities | Unclear usage; complex setup; huge system prompt makes it hard to use immediately |

## Asynchronous Agent Workspaces

Tools and workflows for managing multiple AI coding agents in parallel, enabling asynchronous development and orchestration.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| VibeTunnel Terminal | [steipete.me](https://steipete.me/posts/command-your-claude-code-army-reloaded) | Terminal tool for managing multiple Claude Code sessions | Automatic/manual title updates; clear session tracking; "Claude Code Army" workflow | Requires terminal management; limited to title tracking |
| Conductor (Chorus) | [Chorus](https://chorus.sh/) | Multi-model AI chat aggregator by Charlie Holtz | Chat with multiple AI models; MCP support; compare outputs in real-time | Desktop app only; requires multiple API keys; Mac-focused |
| Vibe Kanban | [Vibe Kanban](https://www.vibekanban.com/) | Kanban board for AI coding agent management | Git worktree integration; parallel task processing; prevents file conflicts | Early stage; open-source only; setup complexity |
| TestSprite MCP | [Cursor Directory](https://cursor.directory/mcp/testsprite-mcp) | AI testing agent with MCP server for IDE integration | Autonomous test generation; parallel cloud execution; 42% → 93% code accuracy boost | Requires TestSprite account; testing-focused; early stage |
| Magnet | [Magnet](https://www.magnet.run/) | AI-native workspace for building software | Integrated development workspace; AI-first design | Limited public information; early stage |

## Developer Libraries & Frameworks

APIs, SDKs, and underlying technologies for building AI-powered applications and workflows.

| Name | Link | Description | Pros | Cons |
|------|------|-------------|------|------|
| DSPy | [GitHub](https://github.com/stanfordnlp/dspy) | Data-science pipelines & feature engineering | Clean API; easy to integrate; accelerates ML | Small community; minimal maintenance |
| BAML | [GitHub](https://github.com/BoundaryML/baml) | Bayesian ML / AML framework | Strong uncertainty quantification; modern design | Steep learning curve; niche use-cases |
| Prompt-Kit Primitives | [Prompt-Kit](https://www.prompt-kit.com/primitives) | Fullstack building blocks for AI applications | Pre-built UI components; Vercel AI SDK integration; easy installation via shadcn registry | Requires Vercel AI SDK; limited primitive selection currently |

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