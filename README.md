# 🤖 Claude Automation Cheat Sheets - Comprehensive Resource List

The Ultimate Collection of Claude Desktop/Code Automation Resources  
Everything you need to automate projects with Claude - curated, organized, and ready to use

[![Stars](https://img.shields.io/github/stars/cavemanguy/claude-automation-cheatsheets?style=social)](https://github.com/cavemanguy/claude-automation-cheatsheets)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-January%202025-green.svg)](https://github.com/cavemanguy/claude-automation-cheatsheets)
[![MCP Servers](https://img.shields.io/badge/MCP%20Servers-80+-blue.svg)](https://github.com/cavemanguy/claude-automation-cheatsheets#-mcp-servers)
[![Configurations](https://img.shields.io/badge/Ready--to--Use%20Configs-15+-green.svg)](https://github.com/cavemanguy/claude-automation-cheatsheets#️-configuration-templates)

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

| Server | Description | Install Command | Links |
|--------|-------------|----------------|-------|
| **[Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** | Secure file operations with configurable access | `npx -y @modelcontextprotocol/server-filesystem` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-filesystem) |
| **[GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)** | Repository management and GitHub API integration | `npx -y @modelcontextprotocol/server-github` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/github) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-github) |
| **[Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)** | Browser automation and web scraping | `npx -y @modelcontextprotocol/server-puppeteer` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-puppeteer) |
| **[Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** | Web search using Brave's API | `npx -y @modelcontextprotocol/server-brave-search` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-brave-search) |
| **[Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git)** | Git repository tools and operations | `npx -y @modelcontextprotocol/server-git` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/git) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-git) |
| **[Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** | Web content fetching optimized for LLMs | `npx -y @modelcontextprotocol/server-fetch` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-fetch) |
| **[Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** | Persistent knowledge graph memory system | `npx -y @modelcontextprotocol/server-memory` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-memory) |
| **[Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequential-thinking)** | Dynamic problem-solving through thought sequences | `npx -y @modelcontextprotocol/server-sequential-thinking` | [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/sequential-thinking) • [📦 NPM](https://www.npmjs.com/package/@modelcontextprotocol/server-sequential-thinking) |

### Popular Community Servers

#### 📊 Databases & Data
- **[MongoDB](https://github.com/stumpylog/mcp-mongo)** - Query and analyze MongoDB collections • [📦 Install](https://www.npmjs.com/package/mcp-mongo)
- **[PostgreSQL](https://github.com/punkpeye/mcp-postgres)** - Advanced PostgreSQL database integration • [📦 Install](https://www.npmjs.com/package/mcp-postgres)
- **[MySQL](https://github.com/designcompanyllc/mysql_mcp_server)** - MySQL database with schema inspection • [📦 Install](https://www.npmjs.com/package/mysql_mcp_server)
- **[SQLite](https://github.com/designcompanyllc/sqlite_mcp_server)** - Lightweight database operations • [📦 Install](https://www.npmjs.com/package/sqlite_mcp_server)
- **[Supabase](https://github.com/supabase-community/mcp-supabase)** - Supabase platform integration • [📦 Install](https://www.npmjs.com/package/mcp-supabase)
- **[Airtable](https://github.com/domdomegg/mcp-airtable)** - Read/write access to Airtable databases • [📦 Install](https://www.npmjs.com/package/mcp-airtable)
- **[Snowflake](https://github.com/adrianwedd/mcp-snowflake)** - Data warehouse integration • [📦 Install](https://www.npmjs.com/package/mcp-snowflake)

#### ☁️ Cloud & DevOps
- **[AWS](https://github.com/ianatha/mcp-aws)** - Comprehensive AWS services integration • [📦 Install](https://www.npmjs.com/package/mcp-aws)
- **[Google Cloud](https://github.com/firebase/mcp-gcp)** - GCP services and APIs • [📦 Install](https://www.npmjs.com/package/mcp-gcp)
- **[Docker](https://github.com/lspillane/mcp-docker)** - Container management and operations • [📦 Install](https://www.npmjs.com/package/mcp-docker)
- **[Kubernetes](https://github.com/Flux159/mcp-k8s)** - Cluster management and deployments • [📦 Install](https://www.npmjs.com/package/mcp-k8s)
- **[GitHub Actions](https://github.com/anthropics/claude-code-action)** - Workflow automation • [📖 Docs](https://docs.anthropic.com/claude/docs/claude-code/github-action)

#### 🔍 Search & Web
- **[Tavily Search](https://github.com/tavily-ai/mcp-tavily)** - AI-optimized search engine • [📦 Install](https://www.npmjs.com/package/mcp-tavily)
- **[Perplexity](https://github.com/perplexity-ai/mcp-perplexity)** - Real-time web research capabilities • [📦 Install](https://www.npmjs.com/package/mcp-perplexity)
- **[Kagi Search](https://github.com/kagi-search/mcp-kagi)** - Privacy-focused search integration • [📦 Install](https://www.npmjs.com/package/mcp-kagi)
- **[Exa Search](https://github.com/exa-labs/mcp-exa)** - AI-powered web information retrieval • [📦 Install](https://www.npmjs.com/package/mcp-exa)

#### 💬 Communication & Productivity
- **[Slack](https://github.com/slack-mcp/mcp-slack)** - Channel management and messaging • [📦 Install](https://www.npmjs.com/package/mcp-slack)
- **[Discord](https://github.com/discord-mcp/mcp-discord)** - Server and channel automation • [📦 Install](https://www.npmjs.com/package/mcp-discord)
- **[Notion](https://github.com/notion/mcp-notion)** - Document and database management • [📦 Install](https://www.npmjs.com/package/mcp-notion)
- **[Obsidian](https://github.com/obsidian-mcp/mcp-obsidian)** - Knowledge management integration • [📦 Install](https://www.npmjs.com/package/mcp-obsidian)
- **[Jira](https://github.com/atlassian/mcp-jira)** - Project management and issue tracking • [📦 Install](https://www.npmjs.com/package/mcp-jira)
- **[Linear](https://github.com/linear/mcp-linear)** - Modern issue tracking integration • [📦 Install](https://www.npmjs.com/package/mcp-linear)

#### 🛡️ Security & Monitoring
- **[Sentry](https://github.com/getsentry/mcp-sentry)** - Error tracking and performance monitoring • [📦 Install](https://www.npmjs.com/package/mcp-sentry)
- **[Datadog](https://github.com/datadog/mcp-datadog)** - Infrastructure monitoring • [📦 Install](https://www.npmjs.com/package/mcp-datadog)
- **[Grafana](https://github.com/grafana/mcp-grafana)** - Metrics and alerting • [📦 Install](https://www.npmjs.com/package/mcp-grafana)

#### 🎨 Creative & Media
- **[EverArt](https://github.com/everart/mcp-everart)** - AI image generation • [📦 Install](https://www.npmjs.com/package/mcp-everart)
- **[Whisper](https://github.com/openai/mcp-whisper)** - Speech-to-text conversion • [📦 Install](https://www.npmjs.com/package/mcp-whisper)
- **[FFmpeg](https://github.com/ffmpeg/mcp-ffmpeg)** - Media processing and conversion • [📦 Install](https://www.npmjs.com/package/mcp-ffmpeg)

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
- **[mcp-get](https://github.com/mcp-get/mcp-get)** - Command line tool for installing MCP servers • [📦 Install](https://www.npmjs.com/package/mcp-get)
- **[MCPHub](https://mcphub.io)** - GUI app for discovering and managing MCP servers • [🌐 Web App](https://mcphub.io)
- **[mcp-manager](https://github.com/mcp-manager/mcp-manager)** - Web UI for installing and managing MCP servers • [📦 Install](https://www.npmjs.com/package/mcp-manager)

### Configuration Management
- **[mcp-guardian](https://github.com/mcp-guardian/mcp-guardian)** - GUI for proxying and managing MCP servers • [📦 Install](https://www.npmjs.com/package/mcp-guardian)
- **[dxt](https://github.com/dxt-tools/dxt)** - Desktop Extension toolkit for packaging MCP servers • [📖 Docs](https://dxt.tools)

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
- **[claude-code.nvim](https://github.com/nvim-claude/claude-code.nvim)** - Neovim integration • [📦 Install](https://github.com/nvim-claude/claude-code.nvim#installation)
- **[VS Code MCP Extension](https://marketplace.visualstudio.com/items?itemName=anthropic.mcp)** - Visual Studio Code support • [🛒 Marketplace](https://marketplace.visualstudio.com/items?itemName=anthropic.mcp)
- **[Cursor Integration](https://cursor.sh/mcp)** - Cursor IDE MCP support • [📖 Docs](https://cursor.sh/docs/mcp)

### Management & Monitoring Tools
- **[CC Usage](https://github.com/cc-usage/cc-usage)** - Claude Code usage analytics and cost tracking • [📦 Install](https://www.npmjs.com/package/cc-usage)
- **[Claude Squad](https://github.com/claude-squad/claude-squad)** - Multi-agent workspace management • [🌐 Web App](https://claudesquad.io)
- **[Claude Task Master](https://github.com/claude-task/task-master)** - AI-driven task management • [📦 Install](https://www.npmjs.com/package/claude-task-master)

### Utility Tools
- **[mcp-cli](https://github.com/mcp-cli/mcp-cli)** - CLI inspector for MCP • [📦 Install](https://www.npmjs.com/package/mcp-cli)
- **[MCP Inspector](https://github.com/mcp-inspector/inspector)** - Debug and test MCP servers • [🌐 Web App](https://mcp-inspector.dev)
- **[Claude Composer](https://github.com/claude-composer/composer)** - Enhanced Claude Code experience • [📖 Docs](https://claude-composer.dev)

### Browser Extensions & Automation
- **[Desktop Commander MCP](https://github.com/desktop-commander/mcp-server)** - Desktop automation server • [📦 Install](https://www.npmjs.com/package/mcp-desktop-commander)
- **[Browser Control MCP](https://github.com/browser-control/mcp-browser)** - Browser automation with extension • [🌐 Chrome Store](https://chrome.google.com/webstore/detail/mcp-browser-control)
- **[Auto-Approve Tools](https://github.com/mcp-tools/auto-approve)** - Auto-approve trusted MCP tools • [📦 Install](https://www.npmjs.com/package/mcp-auto-approve)

---

## 📚 Documentation & Guides

### Official Documentation
- **[Claude Code Overview](https://docs.anthropic.com/claude/docs/claude-code)** - Official getting started guide
- **[Claude Code Best Practices](https://docs.anthropic.com/claude/docs/claude-code/cli-usage)** - Anthropic's best practices
- **[MCP Specification](https://spec.modelcontextprotocol.io/)** - Model Context Protocol documentation
- **[Claude Desktop User Guide](https://docs.anthropic.com/claude/docs/claude-desktop/mcp)** - Setting up MCP with Claude Desktop

### Community Guides & Tutorials
- **[Ultimate Claude MCP Guide](https://claudemcp.com/guide)** - Comprehensive setup and usage guide
- **[MCP Tutorial - Build Your First Server](https://github.com/modelcontextprotocol/servers/blob/main/docs/tutorial.md)** - Step-by-step MCP development
- **[Claude Code CLI Commands](https://claudecode.io/commands)** - 20 essential commands for productivity
- **[Configuring MCP Tools](https://claudecode.io/configuration)** - Better configuration methods

### Video Tutorials & Demos
- **[Claude Computer Use Demo](https://www.youtube.com/watch?v=ODaHJzOyVCQ)** - Official Anthropic demo
- **[Setting up MCP with Docker](https://www.youtube.com/results?search_query=claude+mcp+docker+setup)** - Docker-based setup guide
- **[GitHub Actions with Claude](https://github.com/anthropics/claude-code-action)** - Automating GitHub workflows

### Cheat Sheets & Quick References
- **[MCP Commands Reference](https://spec.modelcontextprotocol.io/specification/basic/)** - Complete CLI command reference
- **[Slash Commands Quick Reference](https://claudecode.io/commands)** - Community command library
- **[Troubleshooting Guide](https://docs.anthropic.com/claude/docs/claude-code/troubleshooting)** - Common issues and solutions

---

## 🌟 Community Resources

### Awesome Lists & Collections
- **[Awesome Claude Code](https://github.com/anthropics/awesome-claude-code)** - Curated commands and workflows
- **[Awesome MCP Servers (wong2)](https://github.com/wong2/awesome-mcp-servers)** - Comprehensive server list
- **[Awesome MCP Servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers)** - Alternative curated list
- **[Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers)** - Another community collection

### Official Repositories
- **[Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers)** - Official MCP server implementations
- **[MCP Registry](https://github.com/modelcontextprotocol/registry)** - Community-driven server registry
- **[Claude Code Action](https://github.com/anthropics/claude-code-action)** - GitHub Actions integration

### Community Platforms
- **[Claude MCP Community](https://claudemcp.com)** - Dedicated MCP community website
- **[MCP Discord Server](https://discord.gg/mcp)** - Official MCP community Discord
- **[r/modelcontextprotocol](https://reddit.com/r/modelcontextprotocol)** - Reddit community
- **[MCP GitHub Discussions](https://github.com/modelcontextprotocol/servers/discussions)** - Official discussions

### Tools & Utilities Directories
- **[MCP Servers Hub](https://mcphub.io)** - Searchable MCP server directory
- **[Smithery](https://smithery.ai)** - MCP server registry and marketplace
- **[mcp.run](https://mcp.run)** - Hosted MCP server registry
- **[Toolbase](https://toolbase.ai)** - Desktop MCP management application

### Learning Resources
- **[MCP Tutorial by DataCamp](https://app.datacamp.com/learn/courses/model-context-protocol)** - Building MCP servers
- **[Claude AI Hub](https://claude.ai/learn)** - Claude tutorials and guides
- **[How I Use Claude Code](https://blog.anthropic.com/claude-code-examples)** - Real-world usage examples

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
| **Commands** | [Awesome Claude Code](https://github.com/anthropics/awesome-claude-code) • [Community Commands](https://claudecode.io/commands) |
| **Community** | [Discord](https://discord.gg/mcp) • [Reddit](https://reddit.com/r/modelcontextprotocol) • [Claude MCP](https://claudemcp.com) |
| **Tools** | [MCPHub](https://mcphub.io) • [Smithery](https://smithery.ai) • [Toolbase](https://toolbase.ai) |

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