# AI-Powered Development Workshop
## Building Mining Operations Applications with Warp Terminal

**Duration**: 4 hours
**Participants**: Developers & Technical Architects (Max 8)
**Presented by**: Interfuze

---

## Workshop Overview

Learn to build intelligent applications using AI-assisted development tools. You'll build a Mining Equipment Maintenance Tracker with realistic Rio Tinto data while mastering Warp terminal's AI capabilities and the Model Context Protocol (MCP).

Unlike traditional training, this workshop emphasizes **learning by doing**. You'll receive business requirements and figure out the implementation using AI assistance—learning to prompt effectively, debug intelligently, and solve real problems.

**Key Outcomes**:
- Build a complete web application using AI assistance
- Understand MCP architecture and remote server integration
- Master effective AI prompting and debugging techniques
- Take home production-ready code and reusable patterns

---

## Workshop Agenda

### Module 0: Setup & Validation (30 min)
**Format**: Guided Installation & Configuration

**What We'll Do Together**:
- Install/verify Warp Terminal with AI enabled
- Install/verify Node.js v18+, Git, VS Code (or alternative editor)
- Clone workshop repository and install dependencies
- Configure Warp to connect to workshop MCP server
- Validate everything works before we start coding

**Your Preparation** (Optional - we'll help if needed):
- Attempt to install Warp from https://warp.dev
- Attempt to install Node.js v18+ from https://nodejs.org

**Don't worry if you hit issues** - we'll resolve them together during Module 0.

**Outcome**: Everyone has a working development environment ready to code

---

### Module 1: AI Architecture Fundamentals (15 min)
**Format**: Condensed Theory + Quick Demo

**Core Concepts**:
- **AI Systems Evolution**: Chat → Agents → Agentic systems
- **MCP Architecture**: Client → Server → Tools → Context
- **Quick Demo**: Warp connecting to MCP servers in action

**Outcome**: Essential mental model for AI-assisted development

---

### Module 2: Build the Application (90 min)
**Format**: Hands-On Challenge

**The Challenge**: Build a Mining Equipment Maintenance Tracker

**Requirements**:
- Equipment dashboard (Tom Price, Paraburdoo sites)
- Maintenance record tracking
- AI-powered predictive maintenance
- Multi-site filtering and health scoring

**Stack**: React + Express + TypeScript (scaffolding provided)

**What You'll Learn**:
- Effective AI prompting with Warp
- Multi-file development workflows
- Debugging with AI assistance
- Using `.warp/standards.md` to guide code generation
- Recovering when AI gets it wrong

**Your Starting Point**:
- Pre-configured TypeScript project
- Development standards in `.warp/`
- Realistic mining equipment data (Komatsu 930E, CAT 797F)
- Business requirements

**Note**: No step-by-step instructions—you figure it out with AI help. This is where real learning happens.

---

### Module 3: Understanding & Using MCP Servers (30 min)
**Format**: Rapid Configuration + Exploration

**What You'll Do**:

**Connect to Remote MCP Server (10 min)**
- Configure Warp to connect to workshop MCP server
- Test connection and available tools
- Understand SSE transport basics

**Explore & Use MCP Tools (20 min)**
- Query mining equipment data via MCP using natural language
- Understand how AI selects appropriate tools
- Quick code walkthrough of MCP server architecture
- Use MCP server during feature development

**MCP Server Details**:
- **URL**: `https://workshop-mcp.azurecontainerapps.io/sse`
- **Health Check**: `https://workshop-mcp.azurecontainerapps.io/health`
- **Tools**: Equipment retrieval, maintenance search, service calculations, site summaries
- **Data**: Realistic Rio Tinto equipment dataset

**Outcome**: Practical understanding of remote MCP server integration

---

### Module 4: Integration & Advanced Workflows (30 min)
**Format**: Demo + Discussion

**Topics**:
- **Warp Workflows**: Automate common dev tasks
- **Agentic Patterns**: Multi-step AI reasoning with MCP
- **Real-World MCP**: When to build vs use existing servers
- **Rio Tinto Application**: Fork MCP server for internal use

**Monday Morning Plan**:
- Week 1: Use Warp AI daily
- Week 2: Fork workshop MCP server, add Rio Tinto tools
- Week 3: Deploy internal MCP server
- Week 4: Build additional MCP servers

---

### Wrap-Up & Next Steps (30 min)

**Key Takeaways**:
- AI-assisted development workflows
- MCP architecture and integration
- Effective prompting and debugging
- Agentic AI patterns

**What You Take Home**:
- Complete application source code
- MCP server source (forkable)
- Warp configuration files
- Synthetic mining equipment data
- 30-day support access

**Q&A and Buffer Time**:
- Open questions about any module
- Troubleshoot any lingering issues
- Discuss Rio Tinto-specific applications
- Extra time if workshop runs behind schedule

---

## Pre-Workshop Setup (Recommended, Not Required)

**We'll handle setup together in Module 0, but if you want to get a head start:**

### Recommended Pre-Installation (Optional):
- **Warp Terminal** (latest version from warp.dev)
  - Enable Warp AI (subscription or free trial)
- **Node.js** (v18+) + npm from nodejs.org
- **Git** (v2.x+)
- **Code editor** (VS Code recommended, but any editor works)

### If You Encounter Issues:
**Don't worry!** We have a 30-minute setup module at the start where we'll help everyone get configured. Just bring your laptop.

### No Validation Required:
Unlike typical workshops, we don't require pre-workshop validation. We'll do it together live with instructor support.

---

## What to Bring

**Required**:
- Laptop (macOS, Windows, or Linux)
- Power adapter
- Willingness to learn and experiment

**NOT Required**:
- Pre-configured environment
- Prior AI tooling experience
- Specific operating system
- Warp AI subscription (free trial available)

---

## What You'll Learn

**Skills**:
- AI-assisted development with Warp terminal
- Effective prompting for code generation
- MCP server configuration and usage
- Context management with `.warp/`
- Agentic AI patterns
- Debugging when AI fails

**Deliverables**:
- Working Mining Equipment Tracker app
- Production MCP server source code
- Warp workflows and standards
- Rio Tinto equipment dataset
- Workshop recording + documentation

---

## Participant Profile

**Ideal For**:
- Mid to senior developers
- Technical architects
- Team leads

**Required Skills**:
- JavaScript/TypeScript proficiency
- React/Express experience
- Git and command-line comfort
- Willingness to learn through experimentation

**NOT Required**:
- AI tooling experience
- MCP knowledge
- Warp experience
- Cloud expertise

---

## Logistics

**Duration**: 4 hours
**Where**: [Location]
**Bring**: Laptop with power adapter

**Schedule**:
- **Start - Start +30 min**: Module 0 - Setup & Validation
- **Start +30 min - Start +45 min**: Module 1 - AI Architecture
- **Start +45 min - Start +2:15**: Module 2 - Build the Application
- **Start +2:15 - Start +2:30**: Break (15 min)
- **Start +2:30 - Start +3:00**: Module 3 - MCP Servers
- **Start +3:00 - Start +3:30**: Module 4 - Advanced Workflows
- **Start +3:30 - Start +4:00**: Wrap-up, Q&A, Next Steps

---

## Contact

**Workshop Lead**: [Your Name]
**Email**: [workshop-email]@interfuze.com.au
**Company**: Interfuze

**Questions?** Contact us or schedule a pre-workshop call.

---

## Quick Reference

### MCP Server Info
```
URL: https://workshop-mcp.azurecontainerapps.io/sse
Health: https://workshop-mcp.azurecontainerapps.io/health

Tools:
- get_equipment: Retrieve by ID or site
- search_maintenance: Query records
- calculate_service_due: Predict service dates
- get_site_summary: Aggregate by site
```

### Warp Configuration
```json
{
  "mcpServers": {
    "mining-equipment": {
      "url": "https://workshop-mcp.azurecontainerapps.io/sse"
    }
  }
}
```

---

**Ready to transform your development workflow?**

This workshop provides practical skills you can apply immediately. You'll leave with working code, production-ready patterns, and the confidence to leverage AI tools effectively.
