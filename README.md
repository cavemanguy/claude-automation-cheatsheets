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
- **[PostgreSQL MCP Servers](https://github.com/wong2/awesome-mcp-servers#database)** - Database integration servers • [📋 Community List](https://github.com/wong2/awesome-mcp-servers)
- **[SQLite MCP Servers](https://github.com/appcypher/awesome-mcp-servers#database)** - SQLite database tools • [📋 Alternative List](https://github.com/appcypher/awesome-mcp-servers)
- **[MongoDB](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** - Use Memory server for document storage • [📖 Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)
- **[MySQL](https://github.com/wong2/awesome-mcp-servers#database)** - See community list for MySQL servers • [📋 Community List](https://github.com/wong2/awesome-mcp-servers)
- **[Supabase](https://github.com/wong2/awesome-mcp-servers#database)** - Check community for Supabase implementations • [📋 Awesome List](https://github.com/wong2/awesome-mcp-servers)
- **Database Tools** - More database servers being developed by community • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20database)

#### ☁️ Cloud & DevOps
- **[AWS CLI](https://github.com/wong2/awesome-mcp-servers#cloud-platforms)** - Check community for AWS integrations • [📋 Awesome List](https://github.com/wong2/awesome-mcp-servers)
- **[Docker](https://github.com/wong2/awesome-mcp-servers#containers--orchestration)** - Container management tools in development • [📋 Community List](https://github.com/wong2/awesome-mcp-servers)
- **[Kubernetes](https://github.com/appcypher/awesome-mcp-servers#devops)** - K8s tools being developed • [📋 DevOps List](https://github.com/appcypher/awesome-mcp-servers)
- **[GitHub Actions](https://github.com/anthropics/claude-code-action)** - Official GitHub Actions integration • [📖 Docs](https://docs.anthropic.com/claude/docs/claude-code/github-action)
- **Cloud Tools** - More cloud integrations coming from community • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20cloud)

#### 🔍 Search & Web
- **[Exa (Metaphor)](https://github.com/exa-labs/exa-mcp-server)** - AI-powered web search and data retrieval • [📦 Install](https://www.npmjs.com/package/@exa-labs/mcp-server)
- **[Tavily Search](https://github.com/wong2/awesome-mcp-servers#search)** - Check community for Tavily implementations • [📋 Search Tools](https://github.com/wong2/awesome-mcp-servers)
- **Web Search Tools** - Multiple search MCP servers in development • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20search)
- **Browser Automation** - Use official Puppeteer server for web tasks • [📖 Puppeteer Docs](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)

#### 💬 Communication & Productivity
- **[Slack](https://github.com/wong2/awesome-mcp-servers#communication)** - Multiple Slack MCP servers available • [📋 Communication Tools](https://github.com/wong2/awesome-mcp-servers)
- **[Email](https://github.com/appcypher/awesome-mcp-servers#productivity)** - Email integration servers in development • [📋 Productivity List](https://github.com/appcypher/awesome-mcp-servers)
- **[Notion](https://github.com/wong2/awesome-mcp-servers#knowledge-management)** - Check community for Notion integrations • [📋 Knowledge Tools](https://github.com/wong2/awesome-mcp-servers)
- **[Calendar](https://github.com/appcypher/awesome-mcp-servers#productivity)** - Calendar and scheduling tools • [📋 Productivity Tools](https://github.com/appcypher/awesome-mcp-servers)
- **Productivity Tools** - Growing collection of productivity servers • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20productivity)

#### 🛡️ Security & Monitoring
- **[Security Tools](https://github.com/wong2/awesome-mcp-servers#security)** - Security-focused MCP servers in development • [📋 Security List](https://github.com/wong2/awesome-mcp-servers)
- **[Monitoring](https://github.com/appcypher/awesome-mcp-servers#monitoring)** - System monitoring tools • [📋 Monitoring Tools](https://github.com/appcypher/awesome-mcp-servers)
- **Infrastructure Tools** - DevOps and security servers growing • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20monitoring)

#### 🎨 Creative & Media
- **[Image Generation](https://github.com/wong2/awesome-mcp-servers#ai--ml)** - AI image tools in community list • [📋 AI Tools](https://github.com/wong2/awesome-mcp-servers)
- **[Media Processing](https://github.com/appcypher/awesome-mcp-servers#media)** - Audio/video processing servers • [📋 Media Tools](https://github.com/appcypher/awesome-mcp-servers)
- **Creative Tools** - Growing collection of creative automation • [🔍 Search NPM](https://www.npmjs.com/search?q=mcp%20media)

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
- **[NPM MCP Servers](https://www.npmjs.com/search?q=@modelcontextprotocol)** - Official MCP servers on NPM • [📦 Browse](https://www.npmjs.com/search?q=@modelcontextprotocol)
- **[Claude Desktop](https://claude.ai/desktop)** - Official desktop app with MCP support • [🌐 Download](https://claude.ai/desktop)
- **[MCP Server Registry](https://github.com/modelcontextprotocol/registry)** - Official registry of MCP servers • [📖 Browse](https://github.com/modelcontextprotocol/registry)

### Configuration Management
- **[MCP Configuration Guide](https://docs.anthropic.com/claude/docs/claude-desktop/mcp)** - Official configuration documentation • [📖 Guide](https://docs.anthropic.com/claude/docs/claude-desktop/mcp)
- **[MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** - Build custom MCP servers • [📦 Install](https://www.npmjs.com/package/@modelcontextprotocol/sdk)

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
- **[Claude Code CLI](https://docs.anthropic.com/claude/docs/claude-code)** - Official command-line interface • [📦 Install](https://docs.anthropic.com/claude/docs/claude-code#installation)
- **[VS Code Claude Extension](https://marketplace.visualstudio.com/search?term=claude&target=VSCode)** - Search for Claude extensions • [🛒 Marketplace](https://marketplace.visualstudio.com/vscode)
- **[Cursor with Claude](https://cursor.sh/)** - AI-powered code editor with Claude support • [📖 Docs](https://cursor.sh/docs)

### Management & Monitoring Tools
- **[Claude Desktop](https://claude.ai/desktop)** - Official desktop application • [📦 Download](https://claude.ai/desktop)
- **[MCP Server Development](https://github.com/modelcontextprotocol/servers)** - Build your own MCP servers • [📖 Docs](https://github.com/modelcontextprotocol/servers/blob/main/README.md)
- **[Claude API Usage](https://console.anthropic.com/usage)** - Monitor your API usage • [🌐 Console](https://console.anthropic.com)

### Utility Tools
- **[MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** - Official TypeScript SDK • [📦 Install](https://www.npmjs.com/package/@modelcontextprotocol/sdk)
- **[MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)** - Official Python SDK • [📦 Install](https://pypi.org/project/mcp/)
- **[MCP Server Examples](https://github.com/modelcontextprotocol/servers/tree/main/src)** - Reference implementations • [📖 Docs](https://github.com/modelcontextprotocol/servers/blob/main/README.md)

### Browser Extensions & Automation
- **[Puppeteer MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)** - Official browser automation • [📦 Install](https://www.npmjs.com/package/@modelcontextprotocol/server-puppeteer)
- **[Fetch MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** - Web content fetching • [📦 Install](https://www.npmjs.com/package/@modelcontextprotocol/server-fetch)
- **[Brave Search MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** - Web search integration • [📦 Install](https://www.npmjs.com/package/@modelcontextprotocol/server-brave-search)

---

## 📚 Documentation & Guides

### Official Documentation
- **[Claude Code Overview](https://docs.anthropic.com/claude/docs/claude-code)** - Official getting started guide
- **[Claude Code Best Practices](https://docs.anthropic.com/claude/docs/claude-code/cli-usage)** - Anthropic's best practices
- **[MCP Specification](https://spec.modelcontextprotocol.io/)** - Model Context Protocol documentation
- **[Claude Desktop User Guide](https://docs.anthropic.com/claude/docs/claude-desktop)** - Setting up MCP with Claude Desktop

### Community Guides & Tutorials
- **[MCP Developer Guide](https://github.com/modelcontextprotocol/servers/blob/main/README.md)** - Official developer documentation
- **[MCP Server Examples](https://github.com/modelcontextprotocol/servers/tree/main/src)** - Official server implementations and tutorials
- **[Claude Code CLI Reference](https://docs.anthropic.com/claude/docs/claude-code/cli-usage)** - Complete CLI command reference
- **[MCP Configuration Guide](https://docs.anthropic.com/claude/docs/claude-desktop/mcp)** - Official configuration guide

### Video Tutorials & Demos
- **[Claude Computer Use Demo](https://www.youtube.com/watch?v=ODaHJzOyVCQ)** - Official Anthropic demo
- **[Setting up MCP with Docker](https://www.youtube.com/results?search_query=claude+mcp+docker+setup)** - Docker-based setup guide
- **[GitHub Actions with Claude](https://github.com/anthropics/claude-code-action)** - Automating GitHub workflows

### Cheat Sheets & Quick References
- **[MCP Commands Reference](https://spec.modelcontextprotocol.io/specification/basic/)** - Complete CLI command reference
- **[Slash Commands Documentation](https://docs.anthropic.com/claude/docs/claude-code/cli-usage)** - Official command reference
- **[Troubleshooting Guide](https://docs.anthropic.com/claude/docs/claude-code/troubleshooting)** - Common issues and solutions

---

## 🌟 Community Resources

### Awesome Lists & Collections
- **[Claude Code Examples](https://docs.anthropic.com/claude/docs/claude-code/examples)** - Official examples and workflows
- **[Awesome MCP Servers (wong2)](https://github.com/wong2/awesome-mcp-servers)** - Comprehensive server list
- **[Awesome MCP Servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers)** - Alternative curated list
- **[Awesome MCP Servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers)** - Another community collection

### Official Repositories
- **[Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers)** - Official MCP server implementations
- **[MCP Registry](https://github.com/modelcontextprotocol/registry)** - Community-driven server registry
- **[Claude Code Action](https://github.com/anthropics/claude-code-action)** - GitHub Actions integration

### Community Platforms
- **[MCP GitHub Discussions](https://github.com/modelcontextprotocol/servers/discussions)** - Official community discussions
- **[Anthropic Discord](https://discord.com/invite/anthropic)** - Official Anthropic community Discord
- **[r/modelcontextprotocol](https://reddit.com/r/modelcontextprotocol)** - Reddit community
- **[Claude Documentation](https://docs.anthropic.com/claude)** - Official Claude documentation and guides

### Tools & Utilities Directories
- **[MCP Server Registry](https://github.com/modelcontextprotocol/registry)** - Official MCP server registry
- **[Awesome MCP Servers](https://github.com/wong2/awesome-mcp-servers)** - Community-curated MCP server list
- **[MCP Server Examples](https://github.com/modelcontextprotocol/servers/tree/main/src)** - Official server implementations
- **[MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)** - Official TypeScript SDK

### Learning Resources
- **[MCP Getting Started Guide](https://github.com/modelcontextprotocol/servers/blob/main/docs/getting-started.md)** - Official getting started documentation
- **[Claude Documentation](https://docs.anthropic.com/claude)** - Official Claude documentation
- **[Claude Code Examples](https://docs.anthropic.com/claude/docs/claude-code/examples)** - Official usage examples

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
| **Commands** | [Claude Code CLI](https://docs.anthropic.com/claude/docs/claude-code/cli-usage) • [MCP Commands](https://spec.modelcontextprotocol.io/specification/basic/) |
| **Community** | [Anthropic Discord](https://discord.com/invite/anthropic) • [Reddit](https://reddit.com/r/modelcontextprotocol) • [GitHub Discussions](https://github.com/modelcontextprotocol/servers/discussions) |
| **Tools** | [MCP Registry](https://github.com/modelcontextprotocol/registry) • [Awesome MCP](https://github.com/wong2/awesome-mcp-servers) • [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) |

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