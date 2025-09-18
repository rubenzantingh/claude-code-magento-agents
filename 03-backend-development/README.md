# Backend Development Agents

Backend specialists focused on server-side development, API design, and data management. These agents handle the core business logic and data processing layers of Magento 2 applications.

## Agents Overview

### 🔌 [api-developer](./api-developer.md)
**API architecture specialist** - REST and GraphQL API design and implementation
- **When to use**: API development, headless commerce, third-party integrations
- **Delegates to**: php-specialist, security-analyst, performance-analyst, xml-specialist
- **Best for**: Service contracts, data transfer objects, authentication systems

### ⏰ [cronjob-developer](./cronjob-developer.md)
**Scheduled task specialist** - Background processing and automation
- **When to use**: Automated tasks, data synchronization, scheduled operations
- **Delegates to**: php-specialist, performance-analyst, xml-specialist
- **Best for**: Data imports/exports, cleanup tasks, notification systems

### 🗄️ [model-developer](./model-developer.md)
**Data layer specialist** - Entity design and database optimization
- **When to use**: Custom entities, database design, data management
- **Delegates to**: php-specialist, index-analyst, performance-analyst, xml-specialist
- **Best for**: EAV models, repository patterns, collections, data migration

## Core Backend Technologies

### API Development
**Service-oriented architecture**
- **REST APIs**: RESTful endpoints with proper HTTP methods
- **GraphQL**: Flexible query language for efficient data fetching
- **Service Contracts**: Interface-based development for modularity
- **Authentication**: OAuth, JWT, and custom authentication systems

### Data Management
**Enterprise data patterns**
- **EAV Models**: Entity-Attribute-Value for flexible data structures
- **Repository Pattern**: Data access abstraction layer
- **Collection Framework**: Efficient data querying and manipulation
- **Database Optimization**: Indexing, query optimization, performance tuning

### Background Processing
**Automated system operations**
- **Cron Jobs**: Scheduled task execution and management
- **Message Queues**: Asynchronous processing for scalability
- **Event System**: Event-driven architecture and observers
- **Data Synchronization**: Real-time and batch data processing
