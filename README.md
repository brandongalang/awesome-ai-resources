# 📚 Awesome AI Resources

A curated, opinionated list of AI tools, platforms, and libraries I use or track. Categorized with pros/cons and confidence ratings so others can adopt, compare, or extend.

## Rating System
Two-dimensional rating system to separate objective functionality from personal workflow preferences:

- **Functional**: ⭐⭐⭐ (Excellent) | ⭐⭐ (Good) | ⭐ (Basic) | ❌ (Poor)
- **Would Use**: ⭐⭐⭐ (Actively use) | ⭐⭐ (Sometimes use) | ⭐ (Rarely use) | ❌ (Avoid) | 📝 (Untested)

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

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | ChatGPT | [OpenAI](https://openai.com/chatgpt) | General all-rounder with tremendous value; great UX; safe choice; access to Codex CLI, async web agent, Sora, VideoGen, Deep Research, Agent Code. Not best for setting up generalized agents. |
| ⭐⭐⭐ | ⭐⭐⭐ | Claude | [Anthropic](https://claude.ai) | Access to Claude Code on subscription; broader access to connectors and MCP tools (native web connectors, custom desktop ones). |
| ⭐⭐⭐ | ⭐⭐⭐ | Claude Desktop | [Anthropic](https://claude.ai/download) | Setting up agents in React loop is incredibly easy; broader MCP tool access; system integration. |
| ⭐⭐ | ⭐⭐ | Gemini | [Google Gemini](https://gemini.google.com) | Pretty good app experience; strong models; Canvas tool very effective; Deep Research works well; Veo 3 image generation excellent. Agent implementation quite bad outside of code generation, deep research, and chat. |
| ⭐⭐⭐ | ⭐⭐⭐ | AI Studio | [Google AI Studio](https://aistudio.google.com) | Better than mobile apps; access to all models and developer settings/API; build functionality like Vercel V0. |
| ⭐⭐⭐ | ⭐⭐⭐ | Granola AI | [Granola](https://granola.ai) | Enterprise-grade chat layer with web embeds, analytics, and fine-tuning capabilities. |
| ⭐⭐⭐ | ⭐⭐ | NotebookLM | [Google NotebookLM](https://notebooklm.google.com) | Useful product with cite-able snippets and doc-grounded answers. Doesn't fit into my workflow much, but it's a great product. |

## Code & Development

IDEs, coding assistants, and specialized development environments with AI integration.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | Claude Code | [Anthropic](https://docs.anthropic.com/en/docs/claude-code) | Handles complex code; good at step-by-step reasoning. My primary coding assistant. |
| ⭐⭐⭐ | ⭐⭐⭐ | Cursor | [Cursor](https://cursor.com) | Deep codebase understanding; multi-file edits; excellent autocomplete. AI-first code editor with great features. |
| ⭐⭐⭐ | ⭐⭐⭐ | Genspark | [Genspark](https://genspark.ai) | Most underrated general agent/chat offering right now. All-in-One AI Workspace with AI Slides, Sheets, Docs, and general-purpose AI agent capabilities. |
| 📝 | 📝 | Serena | [GitHub](https://github.com/oraios/serena) | Powerful coding agent MCP server with semantic retrieval and editing capabilities - haven't really used it yet. Works with any MCP client. |
| 📝 | 📝 | RepoPrompt | [GitHub](https://github.com/id-2/repoprompt) | Seen really great things about it for repository context generation. Don't code as much production code to fully test. |
| 📝 | 📝 | Claude Code Specs Generator | [GitHub](https://github.com/kellemar/claude-code-specs-generator) | AWS Kiro spec approach for Claude Code - haven't really used it. |
| 📝 | 📝 | Claude Code Proxy | [GitHub](https://github.com/fuergaosi233/claude-code-proxy) | Proxy server for Claude Code with OpenAI-compatible APIs - haven't really used it. |
| ⭐⭐⭐ | ⭐⭐⭐ | Vercel V0 | [V0](https://v0.app/) | Natural language to code; supports multiple frameworks; integrates with Vercel; agentic; one-click deployment. |
| ⭐⭐⭐ | ⭐⭐⭐ | Replit | [Replit](https://replit.com/) | No-setup development; 50+ languages; real-time collaboration; one-click deployment; AI agent builds full apps. |
| ⭐⭐⭐ | ⭐⭐⭐ | Lovable | [Lovable](https://lovable.dev/) | Natural language to full-stack apps; React/Tailwind/Vite; instant deployment; screenshot to code. |

## MCP Servers

Model Context Protocol (MCP) servers that extend AI capabilities with specialized tools and integrations.

### Browser & Testing

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| 📝 | 📝 | Puppeteer MCP | [GitHub](https://github.com/modelcontextprotocol/servers) | Browser automation through Puppeteer - haven't tested yet. |
| ⭐⭐ | ⭐⭐ | Playwright MCP | [GitHub](https://github.com/microsoft/playwright-mcp) | A lot of complex websites don't work well. Doesn't really handle JavaScript well or very well. |
| 📝 | 📝 | Octomind MCP | [GitHub](https://github.com/OctoMind-dev/octomind-mcp) | E2E testing platform integration - haven't tested yet. |
| 📝 | 📝 | Stagehand MCP | [GitHub](https://github.com/browserbase/mcp-server-browserbase) | AI browser automation with Browserbase - haven't tested yet. |

### Context & Documentation

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | Context7 | [GitHub](https://github.com/upstash/context7) | Excellent! Live documentation and API reference that prevents hallucination with version-specific docs. |
| 📝 | 📝 | Consult7 | [GitHub](https://github.com/szeider/consult7) | Large context analysis via external LLMs - haven't tested yet. |

### Mobile & Device Integration

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| 📝 | 📝 | Mobile MCP | [GitHub](https://github.com/mobile-next/mobile-mcp) | iOS/Android automation and testing - haven't tested yet. |
| 📝 | 📝 | React Native Debugger MCP | [GitHub](https://github.com/twodoorsdev/react-native-debugger-mcp) | React Native debugging integration - haven't tested yet. |

### Development & Project Management

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | Taskmaster MCP | [GitHub](https://github.com/eyaltoledano/claude-task-master) | AI-powered task management system with PRD parsing, intelligent task breakdown, and research mode. |
| 📝 | 📝 | Linear MCP | [Linear](https://mcp.linear.app/sse) | Linear project management integration - haven't tested yet. |
| 📝 | 📝 | mcp-use | [GitHub](https://github.com/mcp-use/mcp-use) | Universal MCP server connector and agent builder - haven't tested yet. |

### Memory & Search

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| 📝 | 📝 | Memory MCP | [GitHub](https://github.com/doobidoo/mcp-memory-service) | Long-term memory with semantic search - haven't really used. |
| 📝 | 📝 | ChunkHound | [GitHub](https://github.com/ofriw/chunkhound) | Semantic code search and RAG - haven't really used. |

### AI & Media

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| 📝 | 📝 | OpenAI Image MCP | [GitHub](https://github.com/SureScaleAI/openai-gpt-image-mcp) | Image generation and editing - haven't used. |
| 📝 | 📝 | Interactive Feedback MCP | [GitHub](https://github.com/noopstudios/interactive-feedback-mcp) | Human-in-the-loop workflows - haven't used. |

### Development Tools

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| 📝 | 📝 | Cursor-DB MCP | [GitHub](https://github.com/jbdamask/cursor-db-mcp) | Cursor chat history and project access - haven't used. |
| 📝 | 📝 | Octocode MCP | [Octocode](https://octocode.muvon.io/) | AI-powered code intelligence and repository analysis - haven't used. |

## Command Line & Automation

Terminal-based AI agents and CLI tools for development automation and task management.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐ | ⭐⭐ | Gemini CLI | [GitHub](https://github.com/google/generative-ai-cli) | Sometimes use for experimentation or simple agentic tasks (organizing files, scripts). Quirks with porting from Gemini CLI, search functionality doesn't work well. |
| ⭐⭐⭐ | ⭐⭐ | OpenHands | [GitHub](https://github.com/All-Hands-AI/OpenHands) | Good but don't really use it. Full development capabilities; open-source; no Docker required. |
| ⭐⭐⭐ | ⭐⭐ | OpenCode | [GitHub](https://github.com/opencode-ai/opencode) | Very good but don't really use - don't code with open source models much. Terminal-first design with multiple AI provider support. |
| ⭐⭐⭐ | ⭐⭐ | Crush CLI | [GitHub](https://github.com/crush-dev/crush) | Same as OpenCode - very good but don't really use. Enhanced OpenCode with sub-agent support. |
| 📝 | 📝 | VibeKit CLI | [GitHub](https://github.com/superagent-ai/vibekit) | Secure sandbox wrapper for coding agents - haven't tested. |
| ⭐⭐⭐ | ⭐⭐⭐ | Task Master AI | [GitHub](https://github.com/brandongalang/task-master-ai) | Task extraction & automation with calendar/Asana integration. |
| ⭐⭐ | ⭐⭐ | Goose | [GitHub](https://github.com/block/goose) | Open-source AI development agent by Block. Goes beyond code suggestions to execute & test code. |
| ⭐⭐ | ⭐⭐⭐ | Codex CLI | [GitHub](https://github.com/openai/codex) | Great value because it's on the ChatGPT subscription. Local execution with multimodal inputs. |
| ⭐⭐ | ⭐⭐ | Qwen Code | [GitHub](https://github.com/QwenLM/qwen-code) | Sometimes use for experimentation or simple agentic tasks. Very generous limits. Quirks with porting from Gemini CLI - search functionality doesn't work well. |

## Speech & Audio

Voice-to-text transcription and audio processing tools for AI-powered dictation and transcription.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | MacWhisper | [Gumroad](https://goodsnooze.gumroad.com/l/macwhisper) | Free mode works fairly well. Privacy-focused transcription with on-device processing, meeting recording, speaker recognition. |
| ⭐⭐⭐ | ❌ | SuperWhisper | [SuperWhisper](https://superwhisper.com) | Worked great when it worked, but crashing was really bad - couldn't stop it. System-wide dictation with context-aware features. |
| ⭐⭐⭐ | ⭐⭐⭐ | Wispr Flow | [Wispr Flow](https://wisprflow.ai/) | Very good. 4x faster than typing; multi-language support; context-aware; works in any app. |

## Productivity & Knowledge

Note-taking, knowledge management, and productivity platforms with AI integration.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐ | ⭐⭐⭐ | Notion AI | [Notion AI](https://notion.so/ai) | Nice to have it plugged in. Full tool calling agent coming soon which will be great. |
| 📝 | 📝 | Graphiti | [GitHub](https://github.com/graphiti-ai/graphiti) | Personal knowledge graph with memory - haven't really used too much. |
| ⭐⭐⭐ | ⭐ | Mem0 | [GitHub](https://github.com/mem0ai/mem0) | Works well but doesn't really work into my workflows. Memory layer for AI applications. |
| ❌ | ❌ | Claude Code Requirements Builder | [GitHub](https://github.com/brandongalang/claude-code-requirements-builder) | Did not like it. Something about it was just too way too bloated. |
| ⭐⭐⭐ | ⭐ | Vibe Kanban | [Vibe](https://vibe.us) | Very functional but don't really use it. Interactive whiteboard with Kanban features. |
| 📝 | 📝 | Glass | [GitHub](https://github.com/pickle-com/glass) | Ambient AI assistant to explore - haven't tested. |

## Experimental & Research

Cutting-edge tools and research projects that are still in active development or experimental phases.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ❌ | ❌ | SuperClaude | [GitHub](https://github.com/jjohare/SuperClaude) | Configuration framework with CLAUDE.md files and specialized commands for Claude Code - did not like it. Huge system prompt makes it hard to use immediately. |

## Asynchronous Agent Workspaces

Tools and workflows for managing multiple AI coding agents in parallel, enabling asynchronous development and orchestration.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | Terragon Labs | [Terragon Labs](https://www.terragonlabs.com/) | Great option for async Claude Code; systems across mobile, browser, and sandbox; run multiple agents in parallel. |
| 📝 | 📝 | VibeTunnel Terminal | [steipete.me](https://steipete.me/posts/command-your-claude-code-army-reloaded) | Terminal tool for managing multiple Claude Code sessions - haven't tested. |
| ⭐⭐⭐ | ⭐ | Conductor (Chorus) | [Chorus](https://chorus.sh/) | Haven't used much - it's local so not as obviously useful; usually just use terminal (Ghostty). Multi-model AI chat aggregator. |
| 📝 | 📝 | TestSprite MCP | [Cursor Directory](https://cursor.directory/mcp/testsprite-mcp) | AI testing agent with MCP server for IDE integration - haven't tested. |
| 📝 | 📝 | Magnet | [Magnet](https://www.magnet.run/) | AI-native workspace for building software - haven't tested. |

## Developer Libraries & Frameworks

APIs, SDKs, and underlying technologies for building AI-powered applications and workflows.

| Functional | Would Use | Name | Link | Commentary |
|------------|-----------|------|------|-----------|
| ⭐⭐⭐ | ⭐⭐⭐ | DSPy | [GitHub](https://github.com/stanfordnlp/dspy) | Data-science pipelines & feature engineering. Clean API; easy to integrate; accelerates ML. |
| 📝 | 📝 | BAML | [GitHub](https://github.com/BoundaryML/baml) | Bayesian ML / AML framework - haven't really tested. |
| 📝 | 📝 | Prompt-Kit Primitives | [Prompt-Kit](https://www.prompt-kit.com/primitives) | Fullstack building blocks for AI applications - haven't really tested. |
| ⭐ | ⭐ | TensorZero | [GitHub](https://github.com/tensorzero/tensorzero) | Open-source LLM infrastructure stack with data flywheel. Complete LLM lifecycle management but complex for simple use cases. |
| ⭐⭐ | ⭐⭐⭐ | LangGraph/LangChain | [LangChain](https://www.langchain.com/langgraph) | Documentation can be rough, abstractions are hard to understand, code is convoluted, but lots of cookbooks and examples. Pretty standard. Typically just use Claude Code instead. |
| ⭐⭐⭐ | ⭐⭐⭐ | PydanticAI | [Pydantic AI](https://ai.pydantic.dev/) | Python agent framework built by Pydantic team. Type-safe responses; Python-centric design; model-agnostic. Typically just use Claude Code instead. |
| ⭐⭐⭐ | ⭐⭐⭐ | Google ADK | [Google ADK](https://google.github.io/adk-docs/) | Google's Agent Development Kit for multi-agent systems. Code-first development with Google Cloud integration. Typically just use Claude Code instead. |
| 📝 | 📝 | Mastra | [Mastra](https://mastra.ai/) | TypeScript AI framework from Gatsby team - haven't really used it much. |
| ⭐⭐ | ⭐⭐⭐ | PocketFlow | [GitHub](https://github.com/The-Pocket/PocketFlow) | Very simple workflow but very fast and very simple to mock stuff up if you want just simple LLM workflows. |


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Last updated: $(date +%Y-%m-%d)*