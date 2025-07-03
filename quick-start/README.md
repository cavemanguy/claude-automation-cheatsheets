# 🚀 Quick Start Guide - Claude Automation

Get up and running with Claude automation in minutes! This guide covers the essential setup steps for Claude Desktop and Claude Code.

## 📋 Prerequisites

- **Claude Desktop** or **Claude Code** installed
- **Node.js 18+** for MCP servers
- **Git** for cloning repositories
- **Text Editor** for configuration files

## 🎯 5-Minute Setup

### Step 1: Basic Claude Desktop Setup

1. **Locate your config file**:
   - **macOS**: `~/Library/Application Support/Claude/claude_desktop_config.json`
   - **Windows**: `%APPDATA%\Claude\claude_desktop_config.json`

2. **Create basic configuration**:
   ```json
   {
     "mcpServers": {
       "filesystem": {
         "command": "npx",
         "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/Documents"]
       }
     }
   }
   ```

3. **Restart Claude Desktop**

4. **Test the setup**:
   - Open Claude Desktop
   - Ask: "What files are in my Documents folder?"
   - You should see filesystem tools available

### Step 2: Add Essential MCP Servers

1. **GitHub Integration**:
   ```json
   {
     "mcpServers": {
       "filesystem": {
         "command": "npx",
         "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/Documents"]
       },
       "github": {
         "command": "npx",
         "args": ["-y", "@modelcontextprotocol/server-github"],
         "env": {
           "GITHUB_PERSONAL_ACCESS_TOKEN": "your_token_here"
         }
       }
     }
   }
   ```

2. **Get GitHub Token**:
   - Go to GitHub Settings → Developer settings → Personal access tokens
   - Create token with `repo` scope
   - Replace `your_token_here` with your token

3. **Restart Claude Desktop**

### Step 3: Claude Code Setup

1. **Create `.claude.json` in your project**:
   ```json
   {
     "mcpServers": {
       "filesystem": {
         "type": "stdio",
         "command": "npx",
         "args": ["-y", "@modelcontextprotocol/server-filesystem", "."]
       },
       "git": {
         "type": "stdio",
         "command": "npx",
         "args": ["-y", "@modelcontextprotocol/server-git"]
       }
     }
   }
   ```

2. **Test Claude Code**:
   ```bash
   claude --version
   claude "What files are in this project?"
   ```

## 🎨 Essential Commands to Try

Once setup is complete, try these commands:

### File Operations
```
"Create a new README.md file for this project"
"Show me the contents of package.json"
"List all Python files in this directory"
```

### Git Operations (if Git MCP is configured)
```
"Show me the git status"
"Create a new branch called 'feature/new-functionality'"
"Show me the commit history"
```

### GitHub Operations (if GitHub MCP is configured)
```
"List my GitHub repositories"
"Show me open issues in this repository"
"Create a new GitHub issue for bug report"
```

## 🔧 Common Configurations

### Developer Power Setup
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
        "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_xxxxxxxxxxxx"
      }
    },
    "git": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-git"]
    },
    "puppeteer": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-puppeteer"]
    }
  }
}
```

### Web Research Setup
```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/Documents"]
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "your_brave_api_key"
      }
    },
    "fetch": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-fetch"]
    }
  }
}
```

## 🛠️ Troubleshooting

### MCP Server Not Found
```bash
# Install server manually
npm install -g @modelcontextprotocol/server-filesystem
```

### Permission Errors
- Ensure Claude has file system permissions
- Check folder permissions for specified directories
- Run Claude as administrator if needed (Windows)

### Configuration Not Loading
1. Check JSON syntax with a validator
2. Verify file paths exist
3. Restart Claude Desktop after changes
4. Check console for error messages

### GitHub Token Issues
- Verify token has correct permissions
- Check token hasn't expired
- Ensure no extra spaces in environment variable

## ⚡ Next Steps

### 1. Explore More Servers
- Browse the [main README](../README.md) for more MCP servers
- Try database integrations (PostgreSQL, MongoDB)
- Add productivity tools (Notion, Slack)

### 2. Create Custom Commands
- Set up slash commands for common tasks
- Create project-specific automation
- Build custom MCP servers

### 3. Advanced Configuration
- Set up hooks for automated formatting
- Configure CI/CD integration
- Add security validation

### 4. Join the Community
- [MCP Discord Server](https://discord.gg/mcp)
- [Reddit Community](https://reddit.com/r/modelcontextprotocol)
- [GitHub Discussions](https://github.com/modelcontextprotocol/servers/discussions)

## 📚 Additional Resources

- **[Complete Server List](../README.md#-mcp-servers)** - All available MCP servers
- **[Configuration Templates](../README.md#️-configuration-templates)** - Ready-to-use configs
- **[Automation Examples](../README.md#-automation-tools--workflows)** - Workflow automation
- **[Troubleshooting Guide](troubleshooting.md)** - Common issues and solutions

---

**Need Help?** 
- Check the [Contributing Guide](../CONTRIBUTING.md) to add your own resources
- Open an [issue](https://github.com/yourusername/claude-automation-cheatsheets/issues) if you find problems
- Join the community Discord for real-time support

**⭐ Star this repository** if this guide helped you get started!