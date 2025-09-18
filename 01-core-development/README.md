# Core Development Agents

Essential development specialists that form the foundation of Magento 2 development workflows. These agents handle the most common development tasks and serve as orchestrators for complex projects.

## Agents Overview

### 🔍 [code-reviewer](./code-reviewer.md)
**Elite code review expert** - Proactive code quality assurance specialist
- **When to use**: Automatically after significant code changes, or manually for code audits
- **Capabilities**: Security analysis, performance optimization, static analysis, modern best practices
- **Tools**: Read, Grep, Glob (focused on analysis)
- **Auto-invoked**: Use PROACTIVELY for quality assurance

### 🚀 [feature-developer](./feature-developer.md)
**Feature implementation specialist** - Translates business requirements into technical solutions
- **When to use**: New feature development, business logic implementation
- **Delegates to**: php-specialist, code-reviewer, performance-analyst, security-analyst
- **Best for**: Complex features requiring multiple technologies

### 🎨 [theme-developer](./theme-developer.md)
**Theme development specialist** - Custom theme creation and modifications
- **When to use**: Theme creation, custom styling, responsive design
- **Delegates to**: hyva-specialist, luma-specialist, css-specialist, frontend-developer
- **Best for**: Complete theme projects or major theme modifications

### 🐛 [issue-debugger](./issue-debugger.md)
**Issue investigation specialist** - Systematic problem diagnosis and resolution
- **When to use**: Production issues, performance problems, mysterious bugs
- **Delegates to**: performance-analyst, security-analyst, php-specialist, cache-analyst
- **Best for**: Complex debugging requiring multiple analysis approaches

### 📦 [module-developer](./module-developer.md)
**Module development specialist** - Enterprise-grade module architecture
- **When to use**: Custom module development, complex integrations
- **Delegates to**: php-specialist, api-developer, xml-specialist, code-reviewer
- **Best for**: Standalone modules, service contracts, complex business logic

### 🔄 [upgrade-specialist](./upgrade-specialist.md)
**Version upgrade specialist** - Seamless Magento version migrations
- **When to use**: Magento version upgrades, migration planning
- **Delegates to**: code-reviewer, performance-analyst, security-analyst, deployment-engineer
- **Best for**: Major version upgrades, compatibility assessments
