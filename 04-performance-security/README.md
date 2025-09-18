# Performance & Security Agents

Critical specialists focused on application performance optimization and security hardening. These agents ensure your Magento 2 application runs efficiently and securely in production environments.

## Agents Overview

### 🚀 [performance-analyst](./performance-analyst.md)
**Performance optimization orchestrator** - Comprehensive performance analysis and tuning
- **When to use**: Performance issues, optimization projects, scalability planning
- **Delegates to**: cache-analyst, index-analyst, php-specialist, environment-engineer
- **Best for**: System-wide performance optimization, bottleneck identification

### ⚡ [cache-analyst](./cache-analyst.md)
**Caching strategy specialist** - Cache optimization and infrastructure design
- **When to use**: Cache configuration, performance tuning, cache-related issues
- **Delegates to**: performance-analyst, environment-engineer, php-specialist
- **Best for**: Full-page cache, application cache, distributed caching solutions

### 🔍 [index-analyst](./index-analyst.md)
**Search and indexing specialist** - Database and Elasticsearch optimization
- **When to use**: Search performance issues, large catalog optimization, indexing problems
- **Delegates to**: performance-analyst, environment-engineer, catalog-specialist
- **Best for**: Elasticsearch tuning, database indexing, search optimization

### 🛡️ [security-analyst](./security-analyst.md)
**Security specialist** - Comprehensive security assessment and hardening
- **When to use**: Security audits, vulnerability assessment, compliance requirements
- **Delegates to**: code-reviewer, environment-engineer, php-specialist
- **Best for**: PCI compliance, penetration testing, security architecture

## Performance Optimization Areas

### Application Performance
**Code-level optimizations**
- **PHP Performance**: OPcache, memory management, algorithm optimization
- **Database Queries**: Query optimization, index design, connection pooling
- **Frontend Performance**: JavaScript optimization, CSS minification, image optimization
- **API Performance**: Response time optimization, payload optimization

### Infrastructure Performance
**System-level optimizations**
- **Caching Layers**: Full-page cache, application cache, database cache
- **Load Balancing**: Traffic distribution, session management
- **CDN Integration**: Static asset delivery, geographic distribution
- **Server Configuration**: Web server tuning, PHP-FPM optimization

### Search Performance
**Search and indexing optimizations**
- **Elasticsearch**: Cluster configuration, mapping optimization, query tuning
- **Database Indexing**: Index design, query optimization, maintenance
- **Catalog Performance**: Large catalog handling, attribute optimization
- **Faceted Search**: Filter performance, aggregation optimization

## Security Focus Areas

### Application Security
**Code and configuration security**
- **Input Validation**: XSS prevention, SQL injection protection
- **Authentication**: Multi-factor authentication, session security
- **Authorization**: Role-based access control, API security
- **Data Protection**: Encryption, secure storage, privacy compliance

### Infrastructure Security
**System and network security**
- **Server Hardening**: OS security, service configuration
- **Network Security**: Firewall configuration, SSL/TLS setup
- **Access Control**: SSH keys, user management, audit logging
- **Monitoring**: Intrusion detection, security event logging

### Compliance
**Regulatory and industry standards**
- **PCI DSS**: Payment card industry compliance
- **GDPR**: Data privacy and protection compliance
- **SOC 2**: Security and availability controls
- **ISO 27001**: Information security management
