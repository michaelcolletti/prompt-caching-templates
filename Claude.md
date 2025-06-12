# CLAUDE.md - Prompt Caching Configuration

## Prompt Caching Settings
- **Cache Optimization**: Enable aggressive prompt caching for development workflows
- **Context Persistence**: Maintain cached context across sessions for project continuity
- **Cache Invalidation**: Auto-refresh cache when project files change significantly
- **Performance Mode**: Prioritize response speed for iterative development tasks

## Cache-Optimized Project Context
<!-- CACHE_BOUNDARY_START -->
### Project Architecture
- **Framework**: TypeScript/Node.js microservices
- **Database**: PostgreSQL with Prisma ORM
- **Caching Layer**: Redis for sessions and data caching
- **Testing**: Jest + Supertest for comprehensive testing
- **Containerization**: Docker with multi-stage builds
- **Deployment**: Kubernetes with Helm charts

### Development Standards
- **Code Quality**: ESLint + Prettier with strict TypeScript configuration
- **Git Workflow**: Conventional commits with semantic versioning
- **Testing Strategy**: Test-driven development with 90%+ coverage requirement
- **Documentation**: Auto-generated API docs with OpenAPI/Swagger
- **Security**: OWASP compliance with automated security scanning

### Coding Conventions
- **Naming**: camelCase for variables/functions, PascalCase for classes/types
- **Error Handling**: Always use Result<T, E> pattern for error handling
- **Async Operations**: Prefer async/await over Promises.then()
- **Type Safety**: Strict mode enabled, no 'any' types allowed
- **File Organization**: Feature-based folder structure with barrel exports

### Workflow Automation
- **Pre-commit**: Lint, format, and run unit tests
- **CI/CD**: GitHub Actions with automated testing and deployment
- **Code Review**: Required PR reviews with automated checks
- **Performance**: Bundle analysis and performance regression testing
<!-- CACHE_BOUNDARY_END -->

## Cache Optimization Instructions
When processing requests:
1. **Reuse Context**: Leverage cached project context for consistency
2. **Incremental Updates**: Only update relevant cached sections when files change
3. **Pattern Recognition**: Use cached patterns for similar code generation tasks
4. **Performance Monitoring**: Track cache hit rates and optimize accordingly
