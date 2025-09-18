# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Structure

This repository contains Claude Code agent definitions for Magento 2 development, organized into specialized categories:

### Agent Categories

1. **01-core-development/** - Core Magento development experts
   - `code-reviewer.md` - Elite code review expert for AI-powered analysis and security scanning
   - `feature-developer.md` - Feature development specialist
   - `theme-developer.md` - Theme development expert
   - `issue-debugger.md` - Bug investigation and resolution specialist
   - `module-developer.md` - Custom module development expert

2. **02-frontend-development/** - Frontend development specialists
   - `hyva-specialist.md` - Hyvä theme development expert
   - `luma-specialist.md` - Luma theme customization specialist
   - `layout-developer.md` - XML layout construction expert
   - `template-developer.md` - PHTML template development specialist

3. **03-backend-development/** - Backend development specialists
   - `api-developer.md` - REST/GraphQL API development expert
   - `cronjob-developer.md` - Scheduled task implementation specialist
   - `model-developer.md` - Data model and database expert

4. **04-performance-security/** - Performance and security analysts
   - `cache-analyst.md` - Caching optimization expert
   - `index-analyst.md` - Database index optimization specialist
   - `performance-analyst.md` - Performance profiling and optimization expert
   - `security-analyst.md` - Security audit and vulnerability assessment specialist

5. **05-language-specialists/** - Technology-specific specialists
   - `php-specialist.md` - Advanced PHP development expert
   - `alpine-specialist.md` - Alpine.js integration specialist
   - `knockout-specialist.md` - Knockout.js development expert
   - `less-specialist.md` - LESS preprocessing specialist
   - `sass-specialist.md` - SASS/SCSS development expert
   - `magewire-specialist.md` - Magewire (Livewire for Magento) specialist

6. **06-infrastructure/** - Infrastructure and deployment engineers
   - `deployment-engineer.md` - Deployment automation and CI/CD expert
   - `environment-engineer.md` - Environment setup and configuration specialist

## Naming Convention

The repository follows a standardized naming pattern for consistency:

- **Core Development**: `{function}-developer.md`, `{function}-reviewer.md`, or `{function}-debugger.md`
- **Frontend Development**: `{technology}-specialist.md` or `{function}-developer.md`
- **Backend Development**: `{function}-developer.md`
- **Performance/Security**: `{domain}-analyst.md`
- **Language Specialists**: `{technology}-specialist.md`
- **Infrastructure**: `{function}-engineer.md`

## Agent Definition Structure

Each agent file follows the standard Claude Code agent format:
```yaml
---
name: agent-name
description: Brief description of the agent's expertise and purpose
model: opus|sonnet (recommended model for the agent)
---

Agent instructions and specialized knowledge...
```

## Development Workflow

1. **Agent Creation**: Create new specialized agents by following the existing naming convention and structure
2. **Agent Organization**: Place agents in the appropriate category directory based on their primary function
3. **Agent Testing**: Use the `magento-code-reviewer` agent proactively for code quality assurance
4. **Version Control**: All agent definitions are tracked in Git for version control and collaboration

## Key Magento 2 Concepts

When working with these agents, they should be familiar with:
- Magento 2 module structure (`etc/`, `Model/`, `Block/`, `Controller/`, `view/`)
- Dependency injection and service contracts
- Plugin system and observers
- Layout XML and template hierarchy
- CLI commands and cron jobs
- API development (REST/GraphQL)
- Performance optimization (caching, indexing)
- Security best practices
- Theme development (Luma, Hyvä)
- Frontend technologies (RequireJS, KnockoutJS, Alpine.js)

## Agent Specialization

Each agent is designed to be highly specialized in their domain while maintaining awareness of Magento 2 best practices. The `code-reviewer` agent should be used proactively to ensure code quality across all development activities.