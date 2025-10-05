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

### Module 1: AI Architecture Fundamentals (30 min)
**Format**: Theory + Live Demo

Learn the foundational concepts before writing code:
- **AI Systems**: Chat vs Agents vs Agentic systems
- **MCP Architecture**: Client → Server → Tools → Context
- **Live Demo**: Warp connecting to multiple MCP servers (filesystem, git, mining equipment)
- **Context Management**: How AI understands your project

**Outcome**: Mental model for AI-assisted development

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

### Module 3: Understanding & Using MCP Servers (60 min)
**Format**: Configuration + Exploration + Integration

**What You'll Do**:

**Phase 1: Connect to Remote MCP Server (15 min)**
- Configure Warp to connect to workshop MCP server
- Test connection and available tools
- Understand SSE transport architecture

**Phase 2: Explore MCP Tools (20 min)**
- Query mining equipment data via MCP
- Use natural language to invoke specific tools
- Understand tool parameters and responses

**Phase 3: MCP Architecture (15 min)**
- Code walkthrough of the MCP server
- How tool schemas work
- How AI selects appropriate tools

**Phase 4: Development Integration (10 min)**
- Use MCP server during feature development
- See AI query MCP to inform code generation
- Agentic workflow demonstration

**MCP Server Details**:
- **URL**: `https://workshop-mcp.azurecontainerapps.io/sse`
- **Tools**: Equipment retrieval, maintenance search, service calculations, site summaries
- **Data**: Realistic Rio Tinto equipment dataset

**Outcome**: Understand how to use and integrate remote MCP servers

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

### Wrap-Up (10 min)

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

---

## Pre-Workshop Requirements (MANDATORY)

**⚠️ Setup must be completed 48 hours before workshop**

### Required Software:
- Warp Terminal (latest version from warp.dev)
- Warp AI enabled (subscription or trial)
- Git (v2.x+)
- Node.js (v18+) + npm
- TypeScript (`npm install -g typescript`)
- Code editor (VS Code, Cursor, etc.)

### Validation Process:

**Due 48 hours before workshop**:

1. Clone validation repo: `git clone [validation-repo-url]`
2. Install dependencies: `npm install`
3. Run validation: `npm run validate`
4. Screenshot successful output showing:
   - Warp terminal running validation
   - Warp AI responding to test query
   - MCP server connection successful
5. Email screenshots to: [workshop-email]@interfuze.com.au

**Incomplete setup = No workshop seat**

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

**When**: [Date/Time - Recommend 9:00 AM - 1:00 PM]
**Where**: [Location]
**Bring**: Laptop with validated setup

**Schedule**:
- 9:00-9:30: Module 1
- 9:30-9:40: Break
- 9:40-11:10: Module 2
- 11:10-11:25: Break
- 11:25-12:25: Module 3
- 12:25-12:30: Break
- 12:30-13:00: Module 4 + Wrap-up

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
