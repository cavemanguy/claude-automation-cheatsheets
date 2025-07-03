# 🤖 Claude Automation Cheat Sheets - Comprehensive Resource List

The Ultimate Collection of Claude Desktop/Code Automation Resources  
Everything you need to automate projects with Claude - curated, organized, and ready to use

[![Stars](https://img.shields.io/github/stars/yourusername/claude-automation-cheatsheets?style=social)](https://github.com/yourusername/claude-automation-cheatsheets)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-January%202025-green.svg)](https://github.com/yourusername/claude-automation-cheatsheets)

---

## 📋 Table of Contents

- [🔧 MCP Servers](#-mcp-servers)
- [⚙️ Configuration Templates](#️-configuration-templates)
- [🚀 Automation Tools & Workflows](#-automation-tools--workflows)
- [📝 Slash Commands Collections](#-slash-commands-collections)
- [🪝 Hooks & Scripts](#-hooks--scripts)
- [🛠️ Development Tools](#️-development-tools)
- [📚 Documentation & Guides](#-documentation--guides)
- [🌟 Community Resources](#-community-resources)
- [🎯 Quick Start Recommendations](#-quick-start-recommendations)

---

## 🔧 MCP Servers

### Official Anthropic Servers

| Server | Description | Install Command |
|--------|-------------|----------------|
| **Filesystem** | Secure file operations with configurable access | `npx -y @modelcontextprotocol/server-filesystem` |
| **GitHub** | Repository management and GitHub API integration | `npx -y @modelcontextprotocol/server-github` |
| **Puppeteer** | Browser automation and web scraping | `npx -y @modelcontextprotocol/server-puppeteer` |
| **Brave Search** | Web search using Brave's API | `npx -y @modelcontextprotocol/server-brave-search` |
| **Git** | Git repository tools and operations | `npx -y @modelcontextprotocol/server-git` |
| **Fetch** | Web content fetching optimized for LLMs | `npx -y @modelcontextprotocol/server-fetch` |
| **Memory** | Persistent knowledge graph memory system | `npx -y @modelcontextprotocol/server-memory` |
| **Sequential Thinking** | Dynamic problem-solving through thought sequences | `npx -y @modelcontextprotocol/server-sequential-thinking` |

### Popular Community Servers

#### 📊 Databases & Data
- **MongoDB** - Query and analyze MongoDB collections
- **PostgreSQL** - Advanced PostgreSQL database integration
- **MySQL** - MySQL database with schema inspection
- **SQLite** - Lightweight database operations
- **Supabase** - Supabase platform integration
- **Airtable** - Read/write access to Airtable databases
- **Snowflake** - Data warehouse integration
- **ClickHouse** - High-performance analytics database

#### ☁️ Cloud & DevOps
- **AWS** - Comprehensive AWS services integration
- **Google Cloud** - GCP services and APIs
- **Docker** - Container management and operations
- **Kubernetes** - Cluster management and deployments
- **Terraform** - Infrastructure as code operations
- **Ansible** - Configuration management
- **CircleCI** - CI/CD pipeline integration
- **GitHub Actions** - Workflow automation

#### 🔍 Search & Web
- **Tavily Search** - AI-optimized search engine
- **Perplexity** - Real-time web research capabilities
- **Kagi Search** - Privacy-focused search integration
- **Exa Search** - AI-powered web information retrieval
- **SearXNG** - Self-hosted search aggregation

#### 💬 Communication & Productivity
- **Slack** - Channel management and messaging
- **Discord** - Server and channel automation
- **Notion** - Document and database management
- **Obsidian** - Knowledge management integration
- **Jira** - Project management and issue tracking
- **Linear** - Modern issue tracking integration

#### 🛡️ Security & Monitoring
- **Sentry** - Error tracking and performance monitoring
- **Datadog** - Infrastructure monitoring
- **Grafana** - Metrics and alerting
- **Vault** - Secrets management
- **Auth0** - Identity and access management

#### 🎨 Creative & Media
- **EverArt** - AI image generation
- **DALL-E** - OpenAI image generation
- **Whisper** - Speech-to-text conversion
- **FFmpeg** - Media processing and conversion

### Specialized MCP Servers

#### 📱 Mobile Development
- **iOS Simulator** - iOS development and testing
- **Android ADB** - Android device control
- **React Native** - Mobile app development tools
- **Expo** - React Native development platform

#### 🧪 Testing & QA
- **Playwright** - Cross-browser testing automation
- **Selenium** - Web application testing
- **Jest** - JavaScript testing framework
- **Cypress** - End-to-end testing platform

#### 📈 Analytics & Business
- **Google Analytics** - Web analytics integration
- **Mixpanel** - Product analytics platform
- **Stripe** - Payment processing integration
- **PayPal** - Payment system integration
- **Shopify** - E-commerce platform tools

---

## ⚙️ Configuration Templates

### Claude Desktop Configurations

#### Basic Setup (`claude_desktop_config.json`)
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/directory"]
    }
  }
}
```

#### Developer Power User Setup
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/Projects", "~/Documents", "~/Desktop"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "your_token_here"
      }
    },
    "puppeteer": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-puppeteer"]
    },
    "brave-search": {
      "command": "npx", 
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "your_api_key_here"
      }
    }
  }
}
```

#### Team/Enterprise Setup
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/workspace"],
      "env": {
        "ALLOWED_OPERATIONS": "read,write"
      }
    },
    "slack": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-slack"],
      "env": {
        "SLACK_BOT_TOKEN": "xoxb-your-token",
        "SLACK_SIGNING_SECRET": "your-secret"
      }
    },
    "jira": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-jira"],
      "env": {
        "JIRA_HOST": "your-domain.atlassian.net",
        "JIRA_USERNAME": "email@company.com",
        "JIRA_API_TOKEN": "your-api-token"
      }
    }
  }
}
```

### Claude Code Configurations

#### Basic `.claude.json`
```json
{
  "mcpServers": {
    "filesystem": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "."]
    }
  }
}
```

#### Advanced Developer `.claude.json`
```json
{
  "mcpServers": {
    "omnisearch": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "mcp-omnisearch"],
      "env": {
        "TAVILY_API_KEY": "",
        "BRAVE_API_KEY": "",
        "KAGI_API_KEY": "",
        "PERPLEXITY_API_KEY": ""
      }
    },
    "sequential-thinking": {
      "type": "stdio", 
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]
    }
  }
}
```

---

## 🚀 Automation Tools & Workflows

### Installation & Setup Tools
- **claude-code-mcpinstall** - Easy MCP server installation guide
- **mcp-get** - Command line tool for installing MCP servers
- **MCPHub** - GUI app for discovering and managing MCP servers
- **mcp-manager** - Web UI for installing and managing MCP servers

### Configuration Management
- **mcp-guardian** - GUI for proxying and managing MCP servers
- **dxt** - Desktop Extension toolkit for packaging MCP servers

### Workflow Automation Examples

#### Code Review Automation
```bash
# Headless mode for PR reviews
claude -p "Review this PR for code quality, security issues, and best practices" --output-format stream-json
```

#### Issue Triage & Resolution
```bash
# Auto-assign GitHub issue labels
claude -p "Analyze issue #123 and suggest appropriate labels and priority" --headless
```

#### Documentation Generation
```bash
# Generate docs from codebase
claude -p "Generate comprehensive API documentation for this project" --output docs/
```

### CI/CD Integration Examples

#### GitHub Actions with Claude
```yaml
name: Claude PR Assistant
on:
  issue_comment:
    types: [created]
  pull_request_review_comment:
    types: [created]

jobs:
  claude-code-action:
    if: contains(github.event.comment.body, '@claude')
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: anthropics/claude-code-action@beta
        with:
          claude_access_token: ${{ secrets.CLAUDE_ACCESS_TOKEN }}
```

#### Pre-commit Hooks with Claude
```bash
#!/bin/bash
# .git/hooks/pre-commit
claude -p "Review these staged changes for potential issues" --headless --output-format json
```

---

## 📝 Slash Commands Collections

### Official Collections
- **Anthropic Best Practices** - Official slash command examples
- **Claude Code Commands** - 60+ community slash commands

### Community Command Libraries

#### Version Control & Git
- `/commit` - Generate conventional commit messages
- `/create-pr` - Create pull requests with proper formatting
- `/fix-pr` - Address PR review comments automatically
- `/update-branch-name` - Standardize branch naming conventions
- `/husky` - Setup Git hooks with Husky

#### Code Analysis & Testing
- `/review` - Comprehensive code review
- `/test` - Generate and run tests
- `/lint` - Run linting and fix issues
- `/security-check` - Security vulnerability scanning
- `/performance-audit` - Performance analysis

#### Documentation & Content
- `/docs` - Generate documentation
- `/changelog` - Update changelog files
- `/readme` - Create/update README files
- `/api-docs` - Generate API documentation

#### Project Management
- `/standup` - Generate standup reports
- `/sprint-plan` - Create sprint planning documents
- `/issue-analysis` - Analyze and categorize issues
- `/roadmap` - Generate project roadmaps

### Custom Command Templates

#### Basic Template Structure
```markdown
<!-- .claude/commands/your-command.md -->
# Your Command Description

Please [describe what the command should do]:

1. Step one
2. Step two  
3. Step three

Use $ARGUMENTS for dynamic input.
```

#### Advanced Command Example
```markdown
<!-- .claude/commands/deploy-staging.md -->
# Deploy to Staging

Deploy the current branch to staging environment:

1. Run all tests: `npm test`
2. Build production bundle: `npm run build`
3. Deploy to staging: `npm run deploy:staging`
4. Run smoke tests: `npm run test:smoke`
5. Update deployment log

Arguments: $ARGUMENTS (optional: environment name)
```

---

## 🪝 Hooks & Scripts

### Claude Code Hooks System

#### Basic Hook Configuration
```json
{
  "hooks": {
    "PreToolUse": [{
      "matcher": "Write|Edit|MultiEdit",
      "hooks": [{
        "type": "command",
        "command": "echo 'About to modify files' >> ~/claude-activity.log"
      }]
    }],
    "PostToolUse": [{
      "matcher": "Write|Edit|MultiEdit", 
      "hooks": [{
        "type": "command",
        "command": "/home/user/scripts/format-code.sh"
      }]
    }]
  }
}
```

#### Advanced Security Hooks
```json
{
  "hooks": {
    "PreToolUse": [{
      "matcher": ".*",
      "hooks": [{
        "type": "command", 
        "command": "/usr/local/bin/security-check.py",
        "blocking": true
      }]
    }]
  }
}
```

### Automation Scripts Collection

#### File Formatting Automation
```bash
#!/bin/bash
# format-code.sh
find . -name "*.ts" -exec prettier --write {} \;
find . -name "*.go" -exec gofmt -w {} \;
find . -name "*.py" -exec black {} \;
```

#### Build Validation Hook
```bash
#!/bin/bash
# build-validator.sh
npm run build
if [ $? -eq 0 ]; then
  echo "Build successful"
  exit 0
else
  echo "Build failed - blocking operation"
  exit 2
fi
```

#### Security Validation Script
```python
#!/usr/bin/env python3
# security-check.py
import sys
import json

def check_security(tool_name, args):
    # Add your security checks here
    blocked_patterns = ['rm -rf', 'sudo', '> /dev/']
    
    for pattern in blocked_patterns:
        if pattern in str(args):
            return False, f"Blocked dangerous pattern: {pattern}"
    
    return True, "Security check passed"

if __name__ == "__main__":
    # Hook validation logic
    pass
```

---

## 🛠️ Development Tools

### IDE Integrations
- **claude-code.nvim** - Neovim integration
- **VS Code MCP Extension** - Visual Studio Code support
- **Cursor Integration** - Cursor IDE MCP support

### Management & Monitoring Tools
- **CC Usage** - Claude Code usage analytics and cost tracking
- **Claude Squad** - Multi-agent workspace management
- **Claude Task Master** - AI-driven task management

### Utility Tools
- **mcp-cli** - CLI inspector for MCP
- **MCP Inspector** - Debug and test MCP servers
- **Claude Composer** - Enhanced Claude Code experience

### Browser Extensions & Automation
- **Desktop Commander MCP** - Desktop automation server
- **Browser Control MCP** - Browser automation with extension
- **Auto-Approve Tools Script** - Auto-approve trusted MCP tools

---

## 📚 Documentation & Guides

### Official Documentation
- **Claude Code Overview** - Official getting started guide
- **Claude Code Best Practices** - Anthropic's best practices
- **MCP Specification** - Model Context Protocol documentation
- **Claude Desktop User Guide** - Setting up MCP with Claude Desktop

### Community Guides & Tutorials
- **Ultimate Claude MCP Guide** - Comprehensive setup and usage guide
- **MCP Tutorial - Build Your First Server** - Step-by-step MCP development
- **Claude Code CLI Commands** - 20 essential commands for productivity
- **Configuring MCP Tools in Claude Code** - Better configuration methods

### Video Tutorials & Demos
- **Claude Computer Use Demo** - Official Anthropic demo
- **Setting up MCP with Docker** - Docker-based setup guide
- **GitHub Actions with Claude** - Automating GitHub workflows

### Cheat Sheets & Quick References
- **MCP Commands Reference** - Complete CLI command reference
- **Slash Commands Quick Reference** - Community command library
- **Troubleshooting Guide** - Common issues and solutions

---

## 🌟 Community Resources

### Awesome Lists & Collections
- **Awesome Claude Code** - Curated commands and workflows
- **Awesome MCP Servers (wong2)** - Comprehensive server list
- **Awesome MCP Servers (appcypher)** - Alternative curated list
- **Awesome MCP Servers (punkpeye)** - Another community collection

### Official Repositories
- **Model Context Protocol Servers** - Official MCP server implementations
- **MCP Registry** - Community-driven server registry
- **Claude Code Action** - GitHub Actions integration

### Community Platforms
- **Claude MCP Community** - Dedicated MCP community website
- **MCP Discord Server** - Official MCP community Discord
- **r/modelcontextprotocol** - Reddit community
- **MCP GitHub Discussions** - Official discussions

### Tools & Utilities Directories
- **MCP Servers Hub** - Searchable MCP server directory
- **Smithery** - MCP server registry and marketplace
- **mcp.run** - Hosted MCP server registry
- **Toolbase** - Desktop MCP management application

### Learning Resources
- **MCP Tutorial by DataCamp** - Building MCP servers
- **Claude AI Hub** - Claude tutorials and guides
- **How I Use Claude Code** - Real-world usage examples

---

## 🎯 Quick Start Recommendations

### For Beginners
1. **Start with Basic Setup**: Use the filesystem MCP server
2. **Learn Slash Commands**: Try `/commit` and `/docs` commands
3. **Explore Official Servers**: GitHub, Puppeteer, Brave Search
4. **Join Community**: Discord and Reddit for help

### For Developers
1. **Multi-Server Setup**: Combine filesystem, GitHub, and search
2. **Custom Commands**: Create project-specific slash commands
3. **Hooks Integration**: Automate formatting and validation
4. **CI/CD Integration**: Add Claude to GitHub Actions

### For Teams
1. **Enterprise Configuration**: Slack, Jira, monitoring tools
2. **Security Policies**: Implement validation hooks
3. **Shared Commands**: Git-tracked command libraries
4. **Training Resources**: Team onboarding guides

---

## 🔗 Quick Links

| Resource Type | Primary Links |
|---------------|---------------|
| **Official Docs** | [Claude Code](https://docs.anthropic.com/claude/docs/claude-code) • [MCP Spec](https://spec.modelcontextprotocol.io/) |
| **Server Lists** | [Official](https://github.com/modelcontextprotocol/servers) • [wong2](https://github.com/wong2/awesome-mcp-servers) • [appcypher](https://github.com/appcypher/awesome-mcp-servers) |
| **Commands** | [claudecode.io](https://claudecode.io) • [awesome-claude-code](https://github.com/anthropics/awesome-claude-code) |
| **Community** | [Discord](https://discord.gg/mcp) • [Reddit](https://reddit.com/r/modelcontextprotocol) • [claudemcp.com](https://claudemcp.com) |
| **Tools** | [MCPHub](https://mcphub.io) • [mcp-get](https://github.com/mcp-get/mcp-get) • [Toolbase](https://toolbase.ai) |

---

## 🤝 Contributing

This list is maintained by the Claude automation community. Contribute by:

1. **Submit PRs** with new resources, tools, or corrections
2. **Report Issues** for broken links or outdated information
3. **Star the Repository** if this helps you!
4. **Share with Others** in the Claude/MCP community

### Contribution Guidelines
- Verify all links work before submitting
- Include brief descriptions for new resources
- Follow the existing format and structure
- Add resources to appropriate categories

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Last Updated**: January 2025  
**Maintainers**: Claude Automation Community  
**⭐ Give this repo a star if it helps you!**