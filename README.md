<p align="center">
  <img src="https://via.placeholder.com/200" alt="Sageoz" width="200" height="200" />
</p>

<h1 align="center">Sageoz</h1>

<p align="center">
  <strong>Open-Source AI Infrastructure & Agentic Systems</strong><br>
  Building the tools and systems that power the next generation of intelligent agents
</p>

<p align="center">
  <a href="https://github.com/sageoz"><img src="https://img.shields.io/badge/github-sageoz-black?style=flat-square&logo=github" alt="GitHub"></a>
  <a href="#contributing"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen?style=flat-square" alt="Contributions"></a>
</p>

<br>

## 🎯 Our Mission

Sageoz is an open-source organization dedicated to building **foundational infrastructure and tools for AI systems**. We believe that powerful, intelligent agents require robust, well-designed infrastructure. Our mission is to create tools that developers can use to build, understand, and optimize agentic systems at scale.

We're building a community where developers of all skill levels can contribute, learn, and shape the future of AI infrastructure.

---

## 🚀 What We Build

### **Code Intelligence & Context Management**
Tools that help AI systems understand and work with codebases at scale—compressing massive repositories into queryable, structured representations.

### **Agentic System Infrastructure**
Building blocks for creating intelligent agents that can reason about code, track changes, and enforce governance across complex systems.

### **Developer Experience**
Making it easy for developers to integrate AI infrastructure into their workflows without complexity or friction.

---

## ⭐ Featured Project: Batho

**[Batho](https://github.com/sageoz/batho)** — *Bidirectional AST Traversal & Hypergraph Orchestrator*

Batho is our flagship project: a code intelligence engine that transforms massive codebases into queryable, time-aware structured graphs. It's designed to be the memory layer for AI agents working with code.

### Key Capabilities

- **🔍 Intelligent Indexing**: Parse and index 40+ programming languages using AST-based extraction
- **📦 Context Compression**: Generate token-budgeted summaries for LLM context windows (no more AI amnesia)
- **⏱️ Change Tracking**: Track code changes over time with time-aware structured graph snapshots
- **🔗 Hypergraph Orchestration**: Extract relationships and dependencies across your entire codebase
- **🪝 Git Integration**: Automated hooks for governance and code quality enforcement

### Quick Start with Batho

```bash
# Install
uv add batho
# or
pip install batho

# Index your project
batho index --root . --verbose --snapshot

# Generate compressed context for LLM injection
batho bsg --root . --mode compressed --budget 12000

# Install Git hooks for automated checks
batho hooks install --all
```

👉 **[Explore Batho →](https://github.com/sageoz/batho)**

---

## 🛠️ How to Get Involved

### **Use Our Tools**
Start with Batho or any of our projects. Build something cool. Share your experience.

### **Contribute Code**
- Found a bug? [Open an issue](https://github.com/sageoz)
- Have a feature idea? [Start a discussion](https://github.com/sageoz)
- Ready to code? Check out `CONTRIBUTING.md` in any project repo

### **Improve Documentation**
Help us make our docs clearer, more comprehensive, and more accessible.

### **Share Ideas & Feedback**
Join our community discussions. Propose new projects. Help shape the roadmap.

### **Spread the Word**
Star our repos, write about us, and help other developers discover Sageoz.

---

## 📋 Projects & Roadmap

### Current Projects
- **[Batho](https://github.com/sageoz/batho)** — Code intelligence engine for AI systems

### Exploring
- Advanced agentic system frameworks
- Enterprise-grade governance and compliance tools
- Specialized infrastructure for AI model training on code

### Have an Idea?
We're always looking for new projects that advance AI infrastructure. [Start a discussion](https://github.com/sageoz) to propose your idea!

---

## 🤝 Community & Support

- **GitHub Issues**: [Report bugs and request features](https://github.com/sageoz)
- **Discussions**: [Share ideas and get help](https://github.com/sageoz)
- **Documentation**: [Learn more about our tools](https://github.com/sageoz/batho)

---

## 📜 License

All Sageoz projects are open-source. See individual project repositories for details.

---

## 🌟 Why Sageoz?

**For Developers**: Access powerful, production-ready tools for building intelligent systems without reinventing the wheel.

**For Researchers**: Contribute to cutting-edge infrastructure that powers the next generation of AI applications.

**For Organizations**: Build on a foundation of open-source tools designed for scale, reliability, and transparency.

---

<p align="center">
  <strong>Join us in building the future of AI infrastructure.</strong><br>
  <a href="https://github.com/sageoz">Explore Sageoz on GitHub →</a>
</p>
