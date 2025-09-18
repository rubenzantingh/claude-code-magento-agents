# E-commerce Information Analysts

Specialized information retrieval and analysis agents that quickly extract insights from existing Magento 2 instances. These agents focus on rapid data analysis, system health assessment, and business intelligence rather than implementation.

## Agents Overview

### 🛍️ [catalog-specialist](./catalog-specialist.md)
**Catalog data analyst** - Rapid catalog information retrieval and analysis
- **When to use**: Catalog health checks, product data analysis, inventory assessment
- **Delegates to**: php-specialist, performance-analyst
- **Best for**: Catalog structure analysis, product performance insights, data quality assessment

### 📋 [order-specialist](./order-specialist.md)
**Order data analyst** - Transaction analysis and order processing assessment
- **When to use**: Order performance analysis, payment processing review, fulfillment assessment
- **Delegates to**: php-specialist, performance-analyst
- **Best for**: Order pattern analysis, revenue insights, customer behavior analysis

### ⚙️ [configuration-specialist](./configuration-specialist.md)
**Configuration analyst** - System settings analysis and health assessment
- **When to use**: Configuration audits, system health checks, multi-store analysis
- **Delegates to**: php-specialist, security-analyst, performance-analyst
- **Best for**: Configuration optimization, compliance assessment, system diagnostics

## Information Analysis Focus Areas

### Catalog Data Intelligence
**Product and inventory data analysis**
- **Product Structure Analysis**: Analyze product types, attributes, and catalog architecture
- **Inventory Assessment**: Real-time stock levels, allocation patterns, and availability trends
- **Category Performance**: Navigation effectiveness, conversion rates, and user behavior
- **Pricing Intelligence**: Price analysis, competitive positioning, and promotional effectiveness
- **Search & Discovery**: Search performance, relevance optimization, and user engagement

### Order & Transaction Analysis
**Revenue and customer behavior insights**
- **Order Pattern Analysis**: Volume trends, seasonal patterns, and growth indicators
- **Payment Performance**: Success rates, method preferences, and processing efficiency
- **Customer Behavior**: Purchase patterns, lifetime value, and retention analysis
- **Fulfillment Metrics**: Shipping performance, delivery times, and cost effectiveness
- **Revenue Intelligence**: Conversion analysis, average order value, and growth opportunities

### System Health & Configuration
**Infrastructure and configuration assessment**
- **Performance Monitoring**: System performance, bottlenecks, and optimization opportunities
- **Configuration Analysis**: Settings review, multi-store setup, and optimization assessment
- **Security Assessment**: Compliance status, access control effectiveness, and risk analysis
- **Integration Health**: Third-party connections, API performance, and data synchronization
- **Operational Efficiency**: Resource utilization, maintenance needs, and upgrade planning

## Business Scenarios

### High-Volume Catalogs
**Handling enterprise-scale product data**
```
catalog-specialist
├── index-analyst (search optimization)
├── performance-analyst (query optimization)
├── model-developer (data structure)
└── api-developer (data access)
```

### Complex Order Workflows
**Enterprise order processing**
```
order-specialist
├── api-developer (integration)
├── security-analyst (payment security)
├── performance-analyst (throughput)
└── model-developer (order data)
```

### Multi-Store Architecture
**Enterprise configuration management**
```
configuration-specialist
├── xml-specialist (configuration)
├── environment-engineer (infrastructure)
├── security-analyst (access control)
└── performance-analyst (optimization)
```

## Enterprise E-commerce Patterns

### Catalog Architecture
**Scalable product management**
- **Hierarchical Categories**: Deep category structures with inheritance
- **Attribute Strategy**: Efficient attribute design for search and filtering
- **Product Relationships**: Related products, upsells, cross-sells automation
- **Inventory Architecture**: Multi-location inventory with intelligent allocation
- **Price Management**: Dynamic pricing with complex rule engines

### Order Management
**Enterprise order processing**
- **Workflow Automation**: Status transitions, notification systems
- **Payment Integration**: Multiple gateways, payment method routing
- **Fulfillment Optimization**: Order routing, shipping optimization
- **Customer Communication**: Automated notifications, tracking integration
- **Analytics Integration**: Order data for business intelligence

### Configuration Management
**Multi-environment setup**
- **Environment Inheritance**: Configuration hierarchy across environments
- **Store Differentiation**: Store-specific settings and overrides
- **Performance Optimization**: Configuration for maximum performance
- **Security Configuration**: Role-based access and audit logging
- **Compliance Management**: GDPR, PCI DSS, regional compliance

## Best Practices by Domain

### Catalog Optimization
**Performance considerations:**
- Optimize attribute usage for search and filtering
- Implement efficient category structures
- Use flat tables for high-traffic product data
- Optimize image and media handling
- Implement effective caching strategies

**Data management:**
- Establish data quality standards
- Implement product data governance
- Plan for data migration and synchronization
- Design for international expansion
- Create efficient import/export processes

### Order Processing
**Workflow optimization:**
- Design efficient order status workflows
- Implement proper error handling and recovery
- Optimize payment processing flows
- Plan for high-volume order processing
- Implement proper audit trails

**Integration patterns:**
- Design robust API contracts for external systems
- Implement proper data synchronization
- Plan for system failover and recovery
- Create monitoring and alerting systems
- Document integration processes

### Configuration Management
**Architecture principles:**
- Design for configuration inheritance
- Implement proper security controls
- Plan for multi-environment deployment
- Create configuration documentation
- Implement change management processes

**Operational excellence:**
- Monitor configuration changes
- Implement backup and recovery
- Plan for disaster recovery
- Create operational runbooks
- Establish support procedures

## Prompt Strategies

### Catalog Management Prompts
**Be specific about:**
- Product types and complexity
- Catalog size and growth projections
- Performance requirements
- Search and filtering needs
- Integration requirements
