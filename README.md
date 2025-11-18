# Useful Agents Collection

A curated collection of 20 specialized AI agent definitions designed to work with GitHub Copilot and similar AI coding assistants. Each agent is an expert in a specific domain, providing focused knowledge, best practices, and implementation guidance.

## 🎯 Overview

This repository contains pre-configured AI agents that act as specialized consultants for various software development tasks. From backend architecture to security auditing, each agent brings domain-specific expertise to your development workflow.

## 📚 Available Agents

### Backend Development
- **[backend-typescript-architect](./backend-typescript-architect.agent.md)** - Bun runtime, TypeScript backend architecture, database schema design, and scalable server patterns
- **[python-backend-engineer](./python-backend-engineer.agent.md)** - FastAPI, Django development, async programming, API development, and database integration
- **[api-designer](./api-designer.agent.md)** - Clean RESTful APIs, OpenAPI specifications, endpoint documentation, and API versioning strategies

### Frontend Development
- **[ui-engineer](./ui-engineer.agent.md)** - Modern JavaScript/TypeScript frontend development, responsive design systems, React/Vue/Angular components, and performance optimization
- **[interface-designer](./interface-designer.agent.md)** - UI/UX design principles, API specification design, user experience optimization, and design system creation

### AI & Machine Learning
- **[ai-engineer](./ai-engineer.agent.md)** - LLM applications, RAG systems, prompt pipelines, and vector database management
- **[ml-engineer](./ml-engineer.agent.md)** - MLOps pipelines, model serving, feature engineering, model monitoring, and production ML systems
- **[data-scientist](./data-scientist.agent.md)** - Statistical analysis, data visualization, SQL optimization, BigQuery operations, and data insights

### DevOps & Infrastructure
- **[terraform-specialist](./terraform-specialist.agent.md)** - Infrastructure as Code design, Terraform module development, state management, and multi-cloud deployment strategies
- **[network-engineer](./network-engineer.agent.md)** - Network troubleshooting, load balancer configuration, traffic analysis, and security group management
- **[incident-responder](./incident-responder.agent.md)** - Production incidents, triage, root cause analysis, recovery procedures, and post-incident documentation

### Architecture & Design
- **[system-architect](./system-architect.agent.md)** - Comprehensive system architecture design, technology stack selection, scalability planning, and architectural documentation

### Code Quality & Optimization
- **[code-reviewer](./code-reviewer.agent.md)** - Comprehensive code quality assessments, security vulnerability detection, performance analysis, and best practices enforcement
- **[code-refactoring-specialist](./code-refactoring-specialist.agent.md)** - Safe code refactoring, technical debt reduction, code structure improvement, and design pattern implementation
- **[performance-optimizer](./performance-optimizer.agent.md)** - Analyzing and optimizing code performance, identifying bottlenecks, resource usage analysis, and scalability improvements
- **[test-suite-generator](./test-suite-generator.agent.md)** - Generating comprehensive test coverage, test case generation, coverage analysis, and test automation setup

### Security & Compliance
- **[security-auditor](./security-auditor.agent.md)** - Vulnerability assessment, security framework analysis, compliance checking, and penetration testing guidance

### Specialized Domains
- **[fintech-specialist](./fintech-specialist.agent.md)** - Financial models, backtesting trading strategies, market data analysis, and regulatory compliance (SOX, GDPR)
- **[payment-integration](./payment-integration.agent.md)** - Integrating Stripe, PayPal, and payment processors with PCI DSS compliance, webhook handling, and multi-currency support

### Research & Information
- **[gemini-researcher](./gemini-researcher.agent.md)** - External information research, up-to-date data gathering, factual queries, and concept explanations

## 🚀 Usage

### With GitHub Copilot

1. Copy the agent definition file you need to your project's `.github/agents/` directory
2. GitHub Copilot will automatically recognize and use the agent based on your context
3. Reference the agent in your prompts when you need specialized assistance

### General Usage

Each agent file contains:
- **Name**: The agent's identifier
- **Description**: What the agent specializes in
- **Tools**: Available tools the agent can use
- **Detailed guidance**: Domain-specific best practices, patterns, and examples

Simply read through the agent files to understand their capabilities and use them as reference documentation or system prompts for your AI assistant.

## 📖 Agent Structure

Each agent definition follows this format:

```markdown
---
name: agent-name
description: Brief description of the agent's capabilities
tools: [list, of, available, tools]
---

# Detailed implementation guidance
# Best practices
# Code examples
# Domain-specific patterns
```

## 🤝 Contributing

Contributions are welcome! If you have ideas for new agents or improvements to existing ones:

1. Fork the repository
2. Create a new agent file following the naming convention: `agent-name.agent.md`
3. Follow the existing structure and format
4. Include comprehensive domain knowledge and practical examples
5. Submit a pull request

### Agent Creation Guidelines

- Focus on a specific, well-defined domain
- Include practical code examples
- Provide clear best practices
- List relevant tools and frameworks
- Add common patterns and anti-patterns
- Keep the content actionable and implementation-focused

## 📄 License

This project is open source and available for use in your projects. Please check individual files for any specific licensing information.

## 🌟 Popular Use Cases

- **Starting a new project**: Use system-architect and relevant tech-specific agents
- **Code review**: Use code-reviewer and security-auditor
- **Performance issues**: Use performance-optimizer and backend-specific agents
- **Learning**: Read agent files as comprehensive guides to best practices
- **Production incidents**: Use incident-responder for structured troubleshooting

## 💡 Tips

- Combine multiple agents for complex tasks (e.g., system-architect + security-auditor + performance-optimizer)
- Use agents as learning resources - each contains condensed domain expertise
- Customize agents for your specific tech stack and requirements
- Keep agents updated with latest best practices in their domains

---

**Made with ❤️ for developers who want specialized AI assistance**