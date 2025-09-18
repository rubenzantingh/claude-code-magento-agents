# Language & Technology Specialists

Focused specialists for specific programming languages and technologies used in Magento 2 development. These agents provide deep expertise in particular technologies and are typically used by orchestrator agents or for targeted technical challenges.

## Agents Overview

### 🐘 [php-specialist](./php-specialist.md)
**PHP development expert** - Advanced PHP techniques and modern practices
- **When to use**: Complex PHP logic, performance optimization, modern PHP patterns
- **Focus**: Object-oriented programming, design patterns, PHP ecosystem integration
- **Best for**: Algorithm optimization, complex business logic, PHP-specific issues
- **Used by**: Most backend and core development agents

### 🔄 [knockout-specialist](./knockout-specialist.md)
**KnockoutJS expert** - MVVM pattern implementation and data binding
- **When to use**: Traditional Magento frontend, complex UI components, admin interfaces
- **Focus**: Observable patterns, custom bindings, performance optimization
- **Best for**: Interactive UIs, real-time data updates, component development
- **Used by**: luma-specialist, ui-component-developer, frontend-developer

### 🏔️ [alpine-specialist](./alpine-specialist.md)
**Alpine.js expert** - Modern reactive components and declarative programming
- **When to use**: Hyvä theme development, modern JavaScript patterns, lightweight solutions
- **Focus**: Reactive components, declarative programming, performance
- **Best for**: Interactive components without build steps, progressive enhancement
- **Used by**: hyva-specialist, magewire-specialist, frontend-developer

### 🎨 [css-specialist](./css-specialist.md)
**CSS/LESS expert** - Advanced styling and responsive design
- **When to use**: Complex styling, responsive design, CSS architecture, performance optimization
- **Focus**: Modern CSS techniques, preprocessor workflows, cross-browser compatibility
- **Best for**: Design systems, responsive layouts, CSS performance, maintainable stylesheets
- **Used by**: Most frontend agents

### 📋 [xml-specialist](./xml-specialist.md)
**XML configuration expert** - Magento configuration and schema design
- **When to use**: Layout XML, dependency injection, system configuration, module definition
- **Focus**: XML schema design, validation, configuration management
- **Best for**: Module configuration, layout management, system setup
- **Used by**: Most backend and module development agents

### 📦 [requirejs-specialist](./requirejs-specialist.md)
**RequireJS module expert** - AMD module development and dependency management
- **When to use**: Traditional Magento frontend, JavaScript architecture, module loading
- **Focus**: Module loading, build optimization, dependency management
- **Best for**: JavaScript architecture, module organization, build processes
- **Used by**: luma-specialist, frontend-developer

### ⚡ [magewire-specialist](./magewire-specialist.md)
**Magewire expert** - Reactive components and real-time interfaces
- **When to use**: Laravel Livewire-inspired development, reactive UIs, real-time updates
- **Delegates to**: php-specialist, alpine-specialist
- **Focus**: Component lifecycle, state management, interactive development
- **Best for**: Dynamic interfaces, real-time interactions, progressive enhancement

## Technology Categories

### Frontend JavaScript Frameworks

#### Modern Approach (Hyvä)
**Alpine.js** - Lightweight reactivity
- Declarative syntax
- No build step required
- Perfect for progressive enhancement
- Excellent performance characteristics

**Magewire** - Server-side rendering with client-side reactivity
- PHP-driven components
- Real-time updates
- Minimal JavaScript footprint
- Laravel Livewire inspired

#### Traditional Approach (Luma)
**KnockoutJS** - MVVM pattern
- Two-way data binding
- Observable patterns
- Mature and stable
- Extensive Magento integration

**RequireJS** - AMD module loading
- Dependency management
- Modular architecture
- Build optimization
- Legacy compatibility

### Styling Technologies

**CSS/LESS** - Styling and design
- Responsive design patterns
- CSS preprocessing
- Modern CSS features
- Performance optimization

### Configuration Languages

**XML** - Magento configuration
- Layout definitions
- Dependency injection
- System configuration
- Module definitions

### Server-Side Languages

**PHP** - Backend development
- Modern PHP practices
- Object-oriented patterns
- Performance optimization
- Ecosystem integration

## Usage Patterns

### When to Use Specialists Directly

**Deep technical issues:**
```
php-specialist → Complex algorithm optimization
knockout-specialist → Advanced MVVM patterns
alpine-specialist → Custom Alpine.js directives
xml-specialist → Complex layout inheritance
```

**Technology-specific learning:**
```
css-specialist → Modern CSS grid/flexbox patterns
requirejs-specialist → AMD module architecture
magewire-specialist → Reactive component patterns
```

### How Orchestrators Use Specialists

**Frontend Development:**
```
frontend-developer
├── alpine-specialist (for Hyvä components)
├── knockout-specialist (for Luma components)
├── css-specialist (for styling)
└── requirejs-specialist (for module loading)
```

**Module Development:**
```
module-developer
├── php-specialist (for business logic)
├── xml-specialist (for configuration)
└── api-developer → php-specialist (for implementation)
```

## Best Practices by Technology

### PHP Development
**Modern PHP practices:**
- Use type declarations and return types
- Implement proper error handling
- Follow PSR standards
- Leverage composer packages
- Use modern PHP features (8.0+)

**Magento-specific patterns:**
- Implement service contracts
- Use dependency injection
- Follow repository patterns
- Implement proper interfaces
- Use Magento's event system

### JavaScript Development

#### Alpine.js Best Practices
- Use `x-data` for component state
- Implement `x-init` for setup logic
- Leverage `x-show`/`x-if` for conditional rendering
- Use `Alpine.store()` for global state
- Keep components focused and small

#### KnockoutJS Best Practices
- Use computed observables for derived data
- Implement custom bindings for reusability
- Manage subscriptions properly
- Use mapping plugin for complex data
- Optimize for performance with throttling

### CSS Development
**Modern techniques:**
- Use CSS Grid and Flexbox for layouts
- Implement CSS custom properties
- Use modern selectors and pseudo-classes
- Optimize for performance with critical CSS
- Implement responsive design patterns

**Maintainable architecture:**
- Follow BEM or similar methodology
- Use LESS/SASS effectively
- Implement design tokens
- Create reusable components
- Document CSS architecture

### XML Configuration
**Best practices:**
- Follow Magento XML schemas
- Use proper inheritance patterns
- Implement validation
- Document complex configurations
- Use meaningful naming conventions
