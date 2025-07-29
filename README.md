# Actor Registry Portfolio

A comprehensive collection of **WebAssembly actors** built for the Theater system, demonstrating advanced capabilities in distributed computing, AI integration, proxy services, and real-time applications.

## 🌟 Overview

This portfolio showcases expertise in building high-performance WebAssembly actors that leverage the Theater system for distributed computing. Each actor implements clean message-passing interfaces with robust error handling, security controls, and specialized functionality across diverse domains including AI services, development tooling, and web applications.

## 🎭 Featured Actors

### [Anthropic Proxy](./anthropic-proxy)
**🤖 AI Model Integration**

A production-ready WebAssembly actor that serves as a secure proxy for the Anthropic API, enabling Claude model interactions within the Theater system.

**Key Features:**
- 🔑 **Secure API Management**: Safe storage and handling of Anthropic API keys
- 💬 **Message Interface**: Clean request-response system for chat completions
- 🎯 **Model Selection**: Support for all Claude models with capability information
- ⚡ **Performance Optimized**: Configurable caching and timeout controls
- 🛡️ **Error Handling**: Comprehensive error reporting and recovery

**Tech Stack:** Rust, WebAssembly, Anthropic API, Theater messaging

---

### [Chat Interface](./chat-interface)
**🌐 Real-Time Web Frontend**

A sophisticated web server actor that manages user interactions, WebSocket connections, and coordinates chat conversations.

**Key Features:**
- 🌐 **HTTP/WebSocket Server**: Full-featured web server with real-time capabilities
- 👥 **Session Management**: Multi-user session tracking and conversation registry
- 🔄 **Real-Time Communication**: WebSocket-based live chat interface
- 📁 **Static Asset Serving**: Efficient frontend asset delivery
- 🎛️ **Conversation Orchestration**: Central hub for user-chat coordination

**Tech Stack:** Rust, WebAssembly, HTTP server, WebSocket, frontend integration

---

### [Task Manager](./task-manager)
**🎯 AI Task Orchestration**

A configuration-driven orchestrator that manages complex AI task execution with customizable models, prompts, and tool integration.

**Key Features:**
- ⚙️ **Configuration-Driven**: Fully customizable task execution through config
- 🔄 **Model Agnostic**: Support for any AI model or provider
- 🛠️ **Tool Integration**: Configurable MCP tool actor orchestration
- 📋 **Task Lifecycle**: Complete task creation, execution, and completion workflow
- 🎯 **General Purpose**: Adaptable to any task-oriented AI application

**Tech Stack:** Rust, WebAssembly, Theater orchestration, MCP integration

---

### [Chat State](./chat-state)
**💾 Conversation Management**

Manages individual conversation state with persistent message history, context management, and AI model interactions.

**Key Features:**
- 💬 **Message Persistence**: Reliable conversation history storage
- 🧠 **Context Management**: Intelligent context window and memory handling
- 🔄 **State Synchronization**: Real-time state updates across the system
- 🎭 **Actor Lifecycle**: Clean startup, operation, and shutdown patterns
- 📊 **Conversation Analytics**: Message counting and conversation metadata

**Tech Stack:** Rust, WebAssembly, persistent storage, state management

---

### [OpenAI Proxy](./openai-proxy)
**🚀 OpenAI Integration**

A robust proxy actor for OpenAI API services, providing seamless GPT model access within the Theater ecosystem.

**Key Features:**
- 🔌 **API Gateway**: Secure OpenAI API integration with rate limiting
- 🎨 **Multi-Modal Support**: Text, image, and code generation capabilities
- 🔧 **Configuration Flexibility**: Customizable model parameters and settings
- 🛡️ **Security Controls**: API key management and request validation
- ⚡ **Performance Tuning**: Optimized request handling and response caching

**Tech Stack:** Rust, WebAssembly, OpenAI API, async messaging

---

### [Git Command Actor](./git-command-actor)
**📝 Version Control Automation**

Provides comprehensive Git operations through the Theater messaging system, enabling version control automation for AI-powered development workflows.

**Key Features:**
- 🔄 **Complete Git Operations**: Full Git command suite integration
- 🛡️ **Security Controls**: Safe command execution with path validation
- 📊 **Repository Intelligence**: Status checking, diff analysis, and history tracking
- 🤖 **AI Integration**: Git operations optimized for AI development workflows
- 🔧 **Async Operations**: Non-blocking Git command execution

**Tech Stack:** Rust, WebAssembly, Git CLI integration, async execution

---

### [HTTP MCP Actor](./http-mcp-actor)
**🌐 External Service Integration**

Bridges HTTP services with the Theater system, enabling actors to interact with external APIs and web services.

**Key Features:**
- 🌍 **HTTP Client**: Full-featured HTTP client with method support
- 🔗 **MCP Integration**: Model Context Protocol service bridging
- 🛡️ **Security**: Request validation and safe external communication
- ⚡ **Performance**: Async HTTP operations with connection pooling
- 🔧 **Flexibility**: Configurable headers, timeouts, and retry logic

**Tech Stack:** Rust, WebAssembly, HTTP client, MCP protocol

---

### [Commit Actor](./commit-actor)
**📝 Intelligent Code Commits**

Automates Git commit operations with AI-generated commit messages and intelligent change analysis.

**Key Features:**
- 🤖 **AI-Generated Messages**: Intelligent commit message generation
- 📊 **Change Analysis**: Automated diff analysis and categorization
- 🔄 **Workflow Integration**: Seamless Git workflow automation
- 🎯 **Convention Compliance**: Configurable commit message conventions
- 🛡️ **Safety Checks**: Pre-commit validation and safety controls

**Tech Stack:** Rust, WebAssembly, Git integration, AI analysis

---

### [Coding Agent V0](./coding-agent-v0)
**👨‍💻 AI-Powered Development Assistant**

An advanced coding assistant actor that provides intelligent code generation, analysis, and development workflow automation.

**Key Features:**
- 🧠 **Code Intelligence**: Advanced code analysis and generation
- 🔄 **Workflow Automation**: End-to-end development task automation
- 🛠️ **Tool Integration**: Comprehensive development tool orchestration
- 📚 **Context Awareness**: Project-aware code suggestions and modifications
- 🎯 **Task Specialization**: Focused coding task execution and completion

**Tech Stack:** Rust, WebAssembly, AI integration, development tooling

---

## 🏗️ Architecture Highlights

### WebAssembly-First Design
- **Performance**: Near-native execution speed with WebAssembly compilation
- **Security**: Sandboxed execution with controlled system access
- **Portability**: Cross-platform compatibility with consistent behavior
- **Resource Efficiency**: Minimal memory footprint and fast startup times

### Theater System Integration
- **Message Passing**: Clean, typed message interfaces between actors
- **Actor Lifecycle**: Proper startup, operation, and shutdown patterns
- **Distributed Computing**: Scalable actor-based architecture
- **Fault Tolerance**: Isolated failure domains and recovery mechanisms

### AI-Native Architecture
- **Model Integration**: Seamless AI model integration across providers
- **Context Management**: Intelligent handling of conversation and task context
- **Tool Orchestration**: Dynamic tool discovery and execution coordination
- **Workflow Automation**: End-to-end AI-powered development workflows

## 🛠️ Technologies Used

**Core Technologies:**
- Rust - Systems programming with memory safety and performance
- WebAssembly - Portable, high-performance execution environment
- Theater - Actor system for distributed computing
- Component Model - WebAssembly component interfaces

**AI & ML Integration:**
- Anthropic API - Claude model integration
- OpenAI API - GPT model support
- Model Context Protocol (MCP) - Tool and service integration
- Multi-modal AI - Text, image, and code generation

**Web & Networking:**
- HTTP/WebSocket servers - Real-time web applications
- Async networking - Non-blocking I/O operations
- API proxying - Secure external service integration
- Frontend coordination - Dynamic web interface management

**Development Tools:**
- Git integration - Version control automation
- Code analysis - Intelligent code understanding
- Build automation - Development workflow optimization
- Testing frameworks - Comprehensive test coverage

## 🎯 Use Cases

**AI-Powered Development:**
- Automated code generation and review
- Intelligent commit message generation
- Development workflow orchestration
- Real-time coding assistance

**Distributed Web Applications:**
- Multi-user chat systems
- Real-time collaboration tools
- API gateway and proxy services
- Microservice orchestration

**AI Service Integration:**
- Model provider abstraction
- Multi-modal AI workflows
- Context-aware AI interactions
- Tool and service coordination

**Enterprise Automation:**
- Task orchestration and management
- External service integration
- Workflow automation
- System monitoring and control

## 📊 Portfolio Impact

This collection demonstrates:
- **WebAssembly Expertise**: Advanced WASM development with performance optimization
- **Distributed Systems**: Actor-based architecture and message passing patterns
- **AI Integration**: Multi-provider AI service integration and orchestration
- **Real-Time Applications**: WebSocket-based real-time communication systems
- **Security Engineering**: Secure API handling and sandboxed execution
- **Developer Tooling**: Automation tools that enhance development productivity

## 🚀 Getting Started

Each actor includes comprehensive documentation and configuration examples. To explore:

1. **Browse Individual Actors**: Click on any actor above for detailed documentation
2. **Review Manifests**: Each actor includes a `manifest.toml` for Theater deployment
3. **Build Instructions**: Comprehensive build and deployment guides included
4. **Integration Examples**: Working examples of actor communication patterns

## 📄 License

All projects are licensed under the MIT License - see individual repositories for details.

---

*Built with ❤️ for the Theater WebAssembly actor ecosystem*