# 📁 Configuration Examples

A collection of real-world, tested configurations for different use cases and workflows.

## 📋 Table of Contents

- [🎯 Development Workflows](#-development-workflows)
- [🏢 Team & Enterprise](#-team--enterprise)
- [🔍 Research & Analysis](#-research--analysis)
- [🎨 Creative & Content](#-creative--content)
- [📊 Data & Analytics](#-data--analytics)
- [🛡️ Security & DevOps](#️-security--devops)

---

## 🎯 Development Workflows

### Full-Stack Developer Setup

**Use Case**: Complete development environment with code, git, GitHub, and browser automation.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/Projects", "~/Documents"]
    },
    "git": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-git"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_your_token_here"
      }
    },
    "puppeteer": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-puppeteer"]
    },
    "fetch": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-fetch"]
    }
  }
}
```

**What you can do**:
- Manage files and directories
- Perform git operations (commit, branch, merge)
- Create GitHub issues and PRs
- Automate browser testing
- Fetch and analyze web content

### Database Developer Setup

**Use Case**: Working with multiple database systems and data analysis.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/workspace"]
    },
    "postgresql": {
      "command": "npx",
      "args": ["-y", "mcp-postgresql"],
      "env": {
        "DATABASE_URL": "postgresql://user:password@localhost:5432/dbname"
      }
    },
    "mongodb": {
      "command": "npx",
      "args": ["-y", "mcp-mongodb"],
      "env": {
        "MONGODB_URI": "mongodb://localhost:27017/mydb"
      }
    },
    "sqlite": {
      "command": "npx",
      "args": ["-y", "mcp-sqlite", "~/databases"]
    }
  }
}
```

### Mobile Developer Setup

**Use Case**: React Native and mobile app development.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/mobile-projects"]
    },
    "git": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-git"]
    },
    "android-adb": {
      "command": "npx",
      "args": ["-y", "mcp-android-adb"]
    },
    "ios-simulator": {
      "command": "npx",
      "args": ["-y", "mcp-ios-simulator"]
    },
    "expo": {
      "command": "npx",
      "args": ["-y", "mcp-expo"]
    }
  }
}
```

---

## 🏢 Team & Enterprise

### Team Collaboration Setup

**Use Case**: Integrated team tools for project management and communication.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/team-workspace"],
      "env": {
        "ALLOWED_OPERATIONS": "read,write"
      }
    },
    "slack": {
      "command": "npx",
      "args": ["-y", "mcp-slack"],
      "env": {
        "SLACK_BOT_TOKEN": "xoxb-your-bot-token",
        "SLACK_SIGNING_SECRET": "your-signing-secret"
      }
    },
    "jira": {
      "command": "npx",
      "args": ["-y", "mcp-jira"],
      "env": {
        "JIRA_HOST": "your-domain.atlassian.net",
        "JIRA_USERNAME": "your-email@company.com",
        "JIRA_API_TOKEN": "your-api-token"
      }
    },
    "notion": {
      "command": "npx",
      "args": ["-y", "mcp-notion"],
      "env": {
        "NOTION_API_KEY": "secret_your_notion_key"
      }
    }
  }
}
```

### Enterprise Security Setup

**Use Case**: High-security environment with monitoring and compliance.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/secure-workspace"],
      "env": {
        "ALLOWED_OPERATIONS": "read",
        "AUDIT_LOG": "true"
      }
    },
    "vault": {
      "command": "npx",
      "args": ["-y", "mcp-hashicorp-vault"],
      "env": {
        "VAULT_ADDR": "https://vault.company.com",
        "VAULT_TOKEN": "your-vault-token"
      }
    },
    "sentry": {
      "command": "npx",
      "args": ["-y", "mcp-sentry"],
      "env": {
        "SENTRY_AUTH_TOKEN": "your-sentry-token",
        "SENTRY_ORG": "your-org"
      }
    },
    "datadog": {
      "command": "npx",
      "args": ["-y", "mcp-datadog"],
      "env": {
        "DATADOG_API_KEY": "your-api-key",
        "DATADOG_APP_KEY": "your-app-key"
      }
    }
  }
}
```

---

## 🔍 Research & Analysis

### Academic Research Setup

**Use Case**: Research workflows with web search, document analysis, and citation management.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/Research", "~/Papers", "~/Documents"]
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "your-brave-api-key"
      }
    },
    "tavily": {
      "command": "npx",
      "args": ["-y", "mcp-tavily"],
      "env": {
        "TAVILY_API_KEY": "your-tavily-key"
      }
    },
    "fetch": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-fetch"]
    },
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```

### Market Research Setup

**Use Case**: Business intelligence and market analysis.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/market-research"]
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "your-brave-api-key"
      }
    },
    "puppeteer": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-puppeteer"]
    },
    "google-analytics": {
      "command": "npx",
      "args": ["-y", "mcp-google-analytics"],
      "env": {
        "GOOGLE_ANALYTICS_CREDENTIALS": "path/to/credentials.json"
      }
    },
    "airtable": {
      "command": "npx",
      "args": ["-y", "mcp-airtable"],
      "env": {
        "AIRTABLE_API_KEY": "your-airtable-key"
      }
    }
  }
}
```

---

## 🎨 Creative & Content

### Content Creator Setup

**Use Case**: Blog writing, social media management, and creative projects.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/content", "~/blog", "~/assets"]
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "your-brave-api-key"
      }
    },
    "everart": {
      "command": "npx",
      "args": ["-y", "mcp-everart"],
      "env": {
        "EVERART_API_KEY": "your-everart-key"
      }
    },
    "notion": {
      "command": "npx",
      "args": ["-y", "mcp-notion"],
      "env": {
        "NOTION_API_KEY": "secret_your_notion_key"
      }
    }
  }
}
```

### Video Production Setup

**Use Case**: Video editing, processing, and media management.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/video-projects", "~/assets", "~/exports"]
    },
    "ffmpeg": {
      "command": "npx",
      "args": ["-y", "mcp-ffmpeg"]
    },
    "whisper": {
      "command": "npx",
      "args": ["-y", "mcp-whisper"],
      "env": {
        "OPENAI_API_KEY": "your-openai-key"
      }
    },
    "youtube": {
      "command": "npx",
      "args": ["-y", "mcp-youtube"],
      "env": {
        "YOUTUBE_API_KEY": "your-youtube-key"
      }
    }
  }
}
```

---

## 📊 Data & Analytics

### Data Science Setup

**Use Case**: Data analysis, machine learning, and statistical computing.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/data-science", "~/datasets", "~/models"]
    },
    "postgresql": {
      "command": "npx",
      "args": ["-y", "mcp-postgresql"],
      "env": {
        "DATABASE_URL": "postgresql://localhost:5432/analytics"
      }
    },
    "snowflake": {
      "command": "npx",
      "args": ["-y", "mcp-snowflake"],
      "env": {
        "SNOWFLAKE_ACCOUNT": "your-account",
        "SNOWFLAKE_USERNAME": "your-username",
        "SNOWFLAKE_PASSWORD": "your-password"
      }
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_your_token"
      }
    }
  }
}
```

### Business Intelligence Setup

**Use Case**: Dashboard creation, reporting, and business metrics.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/bi-reports"]
    },
    "google-analytics": {
      "command": "npx",
      "args": ["-y", "mcp-google-analytics"],
      "env": {
        "GOOGLE_ANALYTICS_CREDENTIALS": "path/to/ga-credentials.json"
      }
    },
    "mixpanel": {
      "command": "npx",
      "args": ["-y", "mcp-mixpanel"],
      "env": {
        "MIXPANEL_TOKEN": "your-mixpanel-token"
      }
    },
    "stripe": {
      "command": "npx",
      "args": ["-y", "mcp-stripe"],
      "env": {
        "STRIPE_SECRET_KEY": "sk_your_stripe_key"
      }
    },
    "airtable": {
      "command": "npx",
      "args": ["-y", "mcp-airtable"],
      "env": {
        "AIRTABLE_API_KEY": "your-airtable-key"
      }
    }
  }
}
```

---

## 🛡️ Security & DevOps

### DevOps Engineer Setup

**Use Case**: Infrastructure management, deployment, and monitoring.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", 
               "~/infrastructure", "~/deployments"]
    },
    "aws": {
      "command": "npx",
      "args": ["-y", "mcp-aws"],
      "env": {
        "AWS_ACCESS_KEY_ID": "your-access-key",
        "AWS_SECRET_ACCESS_KEY": "your-secret-key",
        "AWS_DEFAULT_REGION": "us-east-1"
      }
    },
    "kubernetes": {
      "command": "npx",
      "args": ["-y", "mcp-kubernetes"],
      "env": {
        "KUBECONFIG": "~/.kube/config"
      }
    },
    "terraform": {
      "command": "npx",
      "args": ["-y", "mcp-terraform"]
    },
    "docker": {
      "command": "npx",
      "args": ["-y", "mcp-docker"]
    },
    "grafana": {
      "command": "npx",
      "args": ["-y", "mcp-grafana"],
      "env": {
        "GRAFANA_URL": "https://grafana.company.com",
        "GRAFANA_API_KEY": "your-grafana-key"
      }
    }
  }
}
```

### Security Analyst Setup

**Use Case**: Security monitoring, incident response, and compliance.

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "~/security-logs"],
      "env": {
        "AUDIT_ALL_OPERATIONS": "true"
      }
    },
    "sentry": {
      "command": "npx",
      "args": ["-y", "mcp-sentry"],
      "env": {
        "SENTRY_AUTH_TOKEN": "your-sentry-token",
        "SENTRY_ORG": "your-security-org"
      }
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_your_token"
      }
    },
    "slack": {
      "command": "npx",
      "args": ["-y", "mcp-slack"],
      "env": {
        "SLACK_BOT_TOKEN": "xoxb-security-bot-token",
        "SLACK_SIGNING_SECRET": "security-signing-secret"
      }
    }
  }
}
```

---

## 💡 Configuration Tips

### Environment Variables
- Store sensitive data in environment variables
- Use `.env` files for local development
- Never commit API keys to version control

### Security Best Practices
- Limit filesystem access to necessary directories
- Use read-only access when possible
- Enable audit logging for sensitive operations
- Regularly rotate API keys and tokens

### Performance Optimization
- Only include servers you actively use
- Consider resource usage of heavy servers (Puppeteer, etc.)
- Use local databases when possible for faster access

### Troubleshooting
- Test each server individually first
- Check server logs for error messages
- Verify all environment variables are set
- Restart Claude after configuration changes

---

**Need Help?**
- Check the [main README](../../README.md) for more servers
- Read the [troubleshooting guide](../troubleshooting/README.md)
- Join the [community Discord](https://discord.gg/mcp) for support

**⭐ Found a configuration useful?** Star the repository and share with others!