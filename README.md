# AI-Skills

A curated collection of specialized AI assistant skills and prompt templates for enhancing AI-powered development workflows in tools like Cursor, GitHub Copilot, and other AI coding assistants.

## 📋 Overview

This repository contains reusable, modular skills that can be integrated into your AI development environment to handle specific tasks more effectively. Each skill is designed to provide consistent, high-quality results for common development scenarios.

## 🎯 Purpose

- **Standardize** AI interactions for repetitive tasks
- **Enhance** AI assistant capabilities with domain-specific knowledge
- **Share** proven prompt patterns and workflows
- **Accelerate** development with ready-to-use AI skills

## 📂 Repository Structure
```
AI-Skills/
├── README.md
└── skills/
    └── database-sql-designer/
        ├── README.md
        ├── prompt.md
        ├── .cursorrules
        └── examples/
```

## 🛠️ Available Skills

### 1. Database SQL Designer
**Path:** `skills/database-sql-designer/`

Generate normalized, production-ready SQL database schemas from natural language specifications.

**Features:**
- Supports PostgreSQL, MySQL, SQLite, SQL Server
- Automatic normalization (3NF by default)
- Index recommendations
- Foreign key constraints
- ER diagram generation (Mermaid syntax)
- Best practices enforcement

**Use Cases:**
- Rapid prototyping of database structures
- Converting business requirements to schemas
- Learning database design patterns
- Documenting existing database structures

[View Full Documentation →](skills/database-sql-designer/README.md)

---

## 🚀 How to Use

1. **Browse Skills:** Navigate to the `skills/` directory
2. **Choose a Skill:** Select the skill that matches your need
3. **Read Documentation:** Check the skill's README.md for details
4. **Copy Prompt:** Use the prompt.md template with your AI assistant
5. **Customize:** Adapt to your specific requirements

## 💡 Using with Cursor

1. Copy the `.cursorrules` file to your project root
2. Open Cursor Composer (Cmd+I / Ctrl+I)
3. Paste the prompt template from `prompt.md`
4. Replace placeholders with your specifications
5. Let the AI generate your solution

## 💡 Using with Other AI Tools

- **GitHub Copilot:** Use prompts in comments
- **ChatGPT/Claude:** Copy-paste prompt templates
- **CLI Tools:** Integrate prompts into your scripts

## 🤝 Contributing

We welcome contributions! To add a new skill:

1. Create a new directory under `skills/`
2. Include all required files (README.md, prompt.md, examples)
3. Follow the existing structure and documentation style
4. Test your skill thoroughly
5. Submit a pull request

### Skill Requirements

- **Well-documented** with clear examples
- **Tested** and proven effective
- **Modular** and reusable
- **Language/framework agnostic** when possible
- Includes both simple and complex examples

## 📝 License

MIT License - Feel free to use and modify these skills for your projects.

## 🔮 Coming Soon

- API Design Assistant
- Code Review Analyzer
- Documentation Generator
- Test Suite Creator
- Architecture Advisor

---

**Star this repo** ⭐ if you find these skills useful!

**Follow for updates** as we add more skills to accelerate your development workflow.
