# 📚 Awesome AI Resources

A curated, opinionated list of AI tools, platforms, and libraries I use or track. Categorized with pros/cons and confidence ratings so others can adopt, compare, or extend.

## Rating System
- ⭐⭐⭐ **Actively use & recommend** - Tools I currently use and highly recommend
- ⭐⭐ **Tested & positive impression** - Tools I've tested with good results but don't use regularly
- ⭐ **Promising but untested** - Tools that look interesting but I haven't fully evaluated
- ❌ **Tested & disappointed** - Tools I tried but didn't work well for my needs
- 📝 **Reference/tracking** - Tools I'm tracking but haven't tested yet

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

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | ChatGPT | [OpenAI](https://openai.com/chatgpt) | General-purpose LLM via web & API | General all-rounder with tremendous value; great UX; safe choice; access to Codex CLI, async web agent, Sora, VideoGen, Deep Research, Agent Code | Not best for setting up generalized agents; closed-source; data residency concerns |
| ⭐⭐⭐ | Claude | [Anthropic](https://claude.ai) | Safety-focused conversational AI | Access to Claude Code on subscription; broader access to connectors and MCP tools (native web connectors, custom desktop ones) | Fewer integrations; pricing varies; slower at times |
| ⭐⭐⭐ | Claude Desktop | [Anthropic](https://claude.ai/download) | Native app experience for Claude | Setting up agents in React loop is incredibly easy; broader MCP tool access; system integration | Platform-dependent; feature parity unclear |
| ⭐⭐⭐ | Gemini | [Google Gemini](https://gemini.google.com) | Multimodal Google LLM | Pretty good app experience; strong models; Canvas tool very effective; Deep Research works well; Veo 3 image generation excellent | Agent implementation quite bad outside of code generation, deep research, and chat |
| ⭐⭐⭐ | Gemini Mobile App | [Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.bard) / [App Store](https://apps.apple.com/app/google-gemini/id6477247706) | Mobile version of Gemini | Native mobile experience; voice input; camera integration | Mobile limitations; data usage on cellular |
| ⭐⭐⭐ | AI Studio | [Google AI Studio](https://aistudio.google.com) | Google's AI experimentation platform | Better than mobile apps; access to all models and developer settings/API; build functionality like Vercel V0 | Google account required; limited model selection |
| ⭐⭐⭐ | Granola AI | [Granola](https://granola.ai) | Enterprise-grade chat layer | Web embeds; analytics; fine-tunable | New entrant; vendor lock-in risk |
| ⭐⭐⭐ | NotebookLM | [Google NotebookLM](https://notebooklm.google.com) | Research-focused assistant | Cite-able snippets; doc-grounded answers | Early access; limited customization; privacy questions |

## Code & Development

IDEs, coding assistants, and specialized development environments with AI integration.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | Claude Code | [Anthropic](https://docs.anthropic.com/en/docs/claude-code) | Claude optimized for code tasks | Handles complex code; good at step-by-step reasoning | Context limits; still hallucinates |
| ⭐⭐⭐ | Cursor | [Cursor](https://cursor.com) | AI-first code editor (VS Code fork) | Deep codebase understanding; multi-file edits; excellent autocomplete | $20/month for Pro; requires internet; some features locked to custom models |
| 📝 | Genspark | [Genspark](https://genspark.ai) | Lightweight code assistant | VS Code integration; code suggestions | Narrow language focus; sporadic updates |
| 📝 | Serena | [GitHub](https://github.com/oraios/serena) | Enhanced Claude Code experience | Adds features to Claude Code; improved context handling | Requires Claude Code; additional setup needed |
| ⭐ | RepoPrompt | [GitHub](https://github.com/id-2/repoprompt) | Repository context generator for AI | Optimized for Claude; XML formatting; file selection; seen really great things about it | CLI-only; manual file selection needed; don't code as much production code |
| 📝 | Claude Code Specs Generator | [GitHub](https://github.com/kellemar/claude-code-specs-generator) | AWS Kiro spec approach for Claude Code | Generates structured specs; follows AWS best practices; improves code quality | Requires setup; AWS-specific methodology |
| 📝 | Claude Code Proxy | [GitHub](https://github.com/fuergaosi233/claude-code-proxy) | Proxy server for Claude Code with OpenAI-compatible APIs | Multi-provider support; full API compatibility; streaming responses; function calling | Requires proxy setup; additional complexity layer |
| ⭐⭐⭐ | Vercel V0 | [V0](https://v0.app/) | AI-powered UI generator for React components | Natural language to code; supports multiple frameworks; integrates with Vercel; agentic; one-click deployment | Limited to React/web; requires Vercel ecosystem |
| ⭐⭐⭐ | Replit | [Replit](https://replit.com/) | AI-powered coding platform with Replit Agent | No-setup development; 50+ languages; real-time collaboration; one-click deployment; AI agent builds full apps | Limited customization vs traditional IDEs; subscription required for full features |
| ⭐⭐⭐ | Lovable | [Lovable](https://lovable.dev/) | AI app builder using chat interface | Natural language to full-stack apps; React/Tailwind/Vite; instant deployment; screenshot to code | Alpha stage for backend features; limited to web applications |

## MCP Servers

Model Context Protocol (MCP) servers that extend AI capabilities with specialized tools and integrations.

### Browser & Testing

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | Puppeteer MCP | [GitHub](https://github.com/modelcontextprotocol/servers) | Browser automation through Puppeteer | Real browser control; screenshot capture; JavaScript execution | Requires headless browser; resource intensive |
| ⭐⭐ | Playwright MCP | [GitHub](https://github.com/microsoft/playwright-mcp) | Browser automation using Playwright | Accessibility tree interaction; cross-browser; deterministic | Microsoft dependency; setup complexity |
| 📝 | Octomind MCP | [GitHub](https://github.com/OctoMind-dev/octomind-mcp) | E2E testing platform integration | Auto-test generation; failure analysis; auto-fix | Requires Octomind account; testing-focused only |
| 📝 | Stagehand MCP | [GitHub](https://github.com/browserbase/mcp-server-browserbase) | AI browser automation with Browserbase | Cloud browser control; Gemini 2.0 Flash integration; production-ready | Requires Browserbase account; API key needed; cloud dependency |

### Context & Documentation

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | Context7 | [GitHub](https://github.com/upstash/context7) | Live documentation and API reference | Up-to-date docs; prevents hallucination; version-specific | Upstash dependency; documentation-focused |
| 📝 | Consult7 | [GitHub](https://github.com/szeider/consult7) | Large context analysis via external LLMs | Handles massive codebases; multiple provider support | Requires high-context models; API costs |

### Mobile & Device Integration

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | Mobile MCP | [GitHub](https://github.com/mobile-next/mobile-mcp) | iOS/Android automation and testing | Real device control; emulator support; cross-platform | iOS support incomplete; device setup required |
| 📝 | React Native Debugger MCP | [GitHub](https://github.com/twodoorsdev/react-native-debugger-mcp) | React Native debugging integration | Metro bundler connection; live error tracking | React Native specific; requires RN setup |

### Development & Project Management

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | Taskmaster MCP | [GitHub](https://github.com/eyaltoledano/claude-task-master) | AI-powered task management system | PRD parsing; intelligent task breakdown; research mode | Requires multiple API keys; complex setup |
| 📝 | Linear MCP | [Linear](https://mcp.linear.app/sse) | Linear project management integration | Official Linear support; issue tracking; project updates | Linear account required; hosted service |
| 📝 | mcp-use | [GitHub](https://github.com/mcp-use/mcp-use) | Universal MCP server connector and agent builder | Connect any LLM to any MCP server; multi-server agent support; open source | Python/TypeScript specific; requires LangChain; early stage |

### Memory & Search

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | Memory MCP | [GitHub](https://github.com/doobidoo/mcp-memory-service) | Long-term memory with semantic search | ChromaDB integration; persistent context; semantic search | ChromaDB dependency; storage overhead |
| 📝 | ChunkHound | [GitHub](https://github.com/ofriw/chunkhound) | Semantic code search and RAG | Local-first; privacy-focused; regex + semantic search | Self-hosted embeddings; setup complexity |

### AI & Media

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | OpenAI Image MCP | [GitHub](https://github.com/SureScaleAI/openai-gpt-image-mcp) | Image generation and editing | GPT-4o vision; text-to-image; aspect ratio control | OpenAI API costs; image generation limits |
| 📝 | Interactive Feedback MCP | [GitHub](https://github.com/noopstudios/interactive-feedback-mcp) | Human-in-the-loop workflows | Reduces API calls; confirmation prompts; improved accuracy | Requires human interaction; workflow interruption |

### Development Tools

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | Cursor-DB MCP | [GitHub](https://github.com/jbdamask/cursor-db-mcp) | Cursor chat history and project access | SQLite database access; chat history exploration | Cursor-specific; privacy considerations |
| 📝 | Octocode MCP | [Octocode](https://octocode.muvon.io/) | AI-powered code intelligence and repository analysis | Advanced GitHub/npm exploration; intelligent caching; persistent memory; semantic code search | Requires API keys; complex setup for advanced features |

## Command Line & Automation

Terminal-based AI agents and CLI tools for development automation and task management.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐ | Gemini CLI | [GitHub](https://github.com/google/generative-ai-cli) | Command-line interface for Gemini | Developer-friendly; scriptable interactions; sometimes use for experimentation or simple agentic tasks (organizing files, scripts) | In flux; needs API key; CLI complexity for novices |
| ⭐ | OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | AI software development agent for terminal | Full development capabilities; open-source; no Docker required | Complex setup; single-user only; requires powerful models |
| ⭐⭐ | OpenCode | [GitHub](https://github.com/opencode-ai/opencode) | Provider-agnostic AI coding agent | Terminal-first design; supports multiple AI providers; LSP integration | Early stage; Go-based; limited documentation |
| ⭐⭐ | Crush CLI | [GitHub](https://github.com/crush-dev/crush) | Enhanced OpenCode with sub-agent support | Same codebase as OpenCode; sub-agent orchestration; advanced workflow management | Early stage; additional complexity; documentation may lag behind features |
| 📝 | VibeKit CLI | [GitHub](https://github.com/superagent-ai/vibekit) | Secure sandbox wrapper for coding agents | Supports Claude/Gemini/Codex; sensitive data redaction; Docker isolation; fully offline | Requires Docker; additional abstraction layer; sandbox overhead |
| 📝 | Task Master AI | [GitHub](https://github.com/brandongalang/task-master-ai) | Task extraction & automation | Auto-creates to-docs; calendar/Asana integration | Over-automation risk; setup complexity |
| ⭐⭐ | Goose | [GitHub](https://github.com/block/goose) | Open-source AI development agent by Block | Beyond code suggestions; executes & tests code; works with any LLM; MCP support | Requires LLM API keys; resource intensive; newer project |
| ⭐⭐ | Codex CLI | [GitHub](https://github.com/openai/codex) | Lightweight coding agent from OpenAI that runs in terminal | Local execution; multimodal inputs; approval modes; ChatGPT integration; open-source | Experimental Windows support; requires ChatGPT Plus/Pro or API key |
| ⭐⭐ | Qwen Code | [GitHub](https://github.com/QwenLM/qwen-code) | Command-line AI workflow tool adapted from Gemini CLI | 256K-1M token context; architecture analysis; test generation; git automation; open-source Apache 2.0 | Sometimes use for experimentation or simple agentic tasks (organizing files, scripts) |

## Speech & Audio

Voice-to-text transcription and audio processing tools for AI-powered dictation and transcription.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | MacWhisper | [Gumroad](https://goodsnooze.gumroad.com/l/macwhisper) | Privacy-focused transcription app for macOS | On-device processing; meeting recording; speaker recognition; 100+ languages | macOS only; $39.99 one-time; requires 8GB+ RAM |
| ⭐⭐ | SuperWhisper | [SuperWhisper](https://superwhisper.com) | AI-powered voice-to-text for macOS | Worked great when it worked; system-wide dictation; context-aware; translation; works offline | Crashing was really bad - couldn't stop it; macOS only; freemium model |
| 📝 | Wispr Flow | [Wispr Flow](https://wisprflow.ai/) | AI-powered voice dictation tool | 4x faster than typing; multi-language support; context-aware; works in any app | iOS/mobile focus; subscription model; requires internet |

## Productivity & Knowledge

Note-taking, knowledge management, and productivity platforms with AI integration.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| 📝 | Notion AI | [Notion AI](https://notion.so/ai) | Note-taking + summarization | Seamless in-doc drafting; meeting roadmap help | Proprietary format; export limitations |
| 📝 | Graphiti | [GitHub](https://github.com/graphiti-ai/graphiti) | Personal knowledge graph with memory | Vector-search notes; knowledge embedding; persistent memory | Early-stage; integration gaps |
| ⭐⭐ | Mem0 | [GitHub](https://github.com/mem0ai/mem0) | Memory layer for AI applications | Persistent memory; easy integration | Early-stage; limited enterprise features |
| 📝 | Claude Code Requirements Builder | [GitHub](https://github.com/brandongalang/claude-code-requirements-builder) | Generates structured requirements from prompts | Automates early spec writing; reduces ambiguity | Requires Claude API key; prompt quality sensitive |
| 📝 | Vibe Kanban | [Vibe](https://vibe.us) | Interactive whiteboard with Kanban features | Real-time collaboration; visual workflow; integrates with Jira/Trello | Hardware-dependent; enterprise pricing; primarily for teams |
| 📝 | Glass | [GitHub](https://github.com/pickle-com/glass) | Ambient AI assistant to explore | Real-time assistance; exploration-focused; ambient computing | Early experimental stage; limited documentation; requires setup |

## Experimental & Research

Cutting-edge tools and research projects that are still in active development or experimental phases.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ❌ | SuperClaude | [GitHub](https://github.com/jjohare/SuperClaude) | Extended Claude fork with massive context | Huge system prompt; extensive capabilities | Unclear usage; complex setup; huge system prompt makes it hard to use immediately |

## Asynchronous Agent Workspaces

Tools and workflows for managing multiple AI coding agents in parallel, enabling asynchronous development and orchestration.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | Terragon Labs | [Terragon Labs](https://www.terragonlabs.com/) | Background agents for Claude Code with parallel execution | Great option for async Claude Code; systems across mobile, browser, and sandbox; run multiple agents in parallel | Beta stage; requires Claude Max subscription; cloud dependency |
| 📝 | VibeTunnel Terminal | [steipete.me](https://steipete.me/posts/command-your-claude-code-army-reloaded) | Terminal tool for managing multiple Claude Code sessions | Automatic/manual title updates; clear session tracking; "Claude Code Army" workflow | Requires terminal management; limited to title tracking |
| ⭐⭐ | Conductor (Chorus) | [Chorus](https://chorus.sh/) | Multi-model AI chat aggregator by Charlie Holtz | Chat with multiple AI models; MCP support; compare outputs in real-time | Haven't used much - it's local so not as obviously useful; usually just use terminal (Ghostty) |
| 📝 | Vibe Kanban | [Vibe Kanban](https://www.vibekanban.com/) | Kanban board for AI coding agent management | Git worktree integration; parallel task processing; prevents file conflicts | Early stage; open-source only; setup complexity |
| 📝 | TestSprite MCP | [Cursor Directory](https://cursor.directory/mcp/testsprite-mcp) | AI testing agent with MCP server for IDE integration | Autonomous test generation; parallel cloud execution; 42% → 93% code accuracy boost | Requires TestSprite account; testing-focused; early stage |
| 📝 | Magnet | [Magnet](https://www.magnet.run/) | AI-native workspace for building software | Integrated development workspace; AI-first design | Limited public information; early stage |

## Developer Libraries & Frameworks

APIs, SDKs, and underlying technologies for building AI-powered applications and workflows.

| Rating | Name | Link | Description | Pros | Cons |
|--------|------|------|-------------|------|------|
| ⭐⭐⭐ | DSPy | [GitHub](https://github.com/stanfordnlp/dspy) | Data-science pipelines & feature engineering | Clean API; easy to integrate; accelerates ML | Small community; minimal maintenance |
| 📝 | BAML | [GitHub](https://github.com/BoundaryML/baml) | Bayesian ML / AML framework | Strong uncertainty quantification; modern design | Steep learning curve; niche use-cases |
| 📝 | Prompt-Kit Primitives | [Prompt-Kit](https://www.prompt-kit.com/primitives) | Fullstack building blocks for AI applications | Pre-built UI components; Vercel AI SDK integration; easy installation via shadcn registry | Requires Vercel AI SDK; limited primitive selection currently |
| ⭐ | TensorZero | [GitHub](https://github.com/tensorzero/tensorzero) | Open-source LLM infrastructure stack with data flywheel | Complete LLM lifecycle management; dynamic in-context learning; self-hosted; built-in A/B testing; ClickHouse analytics | Requires infrastructure setup; ClickHouse dependency; complex for simple use cases |
| ⭐⭐ | LangGraph/LangChain | [LangChain](https://www.langchain.com/langgraph) | Graph-based agent framework with state management | Low-level orchestration; multi-agent workflows; human-in-the-loop; built-in persistence; flexible control flows | Complex for simple use cases; learning curve; typically just use Claude Code instead |
| ⭐⭐⭐ | PydanticAI | [Pydantic AI](https://ai.pydantic.dev/) | Python agent framework built by Pydantic team | Type-safe responses; Python-centric design; model-agnostic; dependency injection; streaming support | New framework; typically just use Claude Code instead |
| ⭐⭐⭐ | Google ADK | [Google ADK](https://google.github.io/adk-docs/) | Google's Agent Development Kit for multi-agent systems | Code-first development; multi-agent orchestration; Google Cloud integration; model flexibility; streaming support | Google ecosystem focus; typically just use Claude Code instead |
| ⭐ | Mastra | [Mastra](https://mastra.ai/) | TypeScript AI framework from Gatsby team | Batteries-included TypeScript; workflows, agents, RAG; type-safe integrations; local playground | TypeScript-only; relatively new; typically just use Claude Code instead |
| ⭐⭐ | PocketFlow | [GitHub](https://github.com/The-Pocket/PocketFlow) | Minimalist 100-line LLM framework | Zero dependencies; zero bloat; graph + shared store architecture; agentic coding | Very minimal; limited features; typically just use Claude Code instead |

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