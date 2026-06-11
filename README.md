# skills-for-open-code: OpenCode Skills, AI Agents, and Developer Workflows

SkillsForOpenCode is a curated collection of OpenCode skills, specialized AI coding agents, reusable commands, and development workflows for planning, reviewing, testing, securing, and maintaining software projects.

Use it to add practical AI-assisted development workflows to OpenCode for frontend, backend, mobile, database, DevOps, security, testing, and documentation work.

## What Is SkillsForOpenCode?

SkillsForOpenCode extends OpenCode with a ready-to-use `.opencode` workspace. It includes domain-specific skills, task-focused agents, command shortcuts, prompts, tools, and project instructions that help developers move from idea to implementation with more structure and consistency.

This repository is useful for developers who want:

- OpenCode skills for everyday software engineering tasks
- AI coding agents for planning, architecture, code review, testing, and security
- Reusable slash commands for common development workflows
- Project-ready prompts and instructions for better AI-assisted coding
- A modular OpenCode setup that can be copied into existing projects

## Key Features

### Specialized AI Coding Agents

Task-focused agents help with common engineering responsibilities:

- **Planner**: Breaks complex features into actionable implementation steps
- **Architect**: Designs scalable system architecture and technical approaches
- **Code Reviewer**: Reviews code quality, maintainability, and best practices
- **Security Reviewer**: Identifies vulnerabilities and security risks
- **TDD Guide**: Supports test-driven development workflows
- **Build Error Resolver**: Diagnoses and fixes build failures
- **E2E Runner**: Helps create and run Playwright end-to-end tests
- **Database Reviewer**: Reviews database schemas, indexes, and queries
- **Refactor Cleaner**: Finds dead code, duplication, and simplification opportunities
- **Performance Optimizer**: Locates and improves performance bottlenecks

### OpenCode Slash Commands

Quick commands provide repeatable workflows inside OpenCode:

- `/plan`: Create implementation plans for features and fixes
- `/tdd`: Follow a test-driven development workflow
- `/code-review`: Review changed code for correctness and maintainability
- `/security`: Run security-focused reviews and audits
- `/build-fix`: Diagnose and fix build errors
- `/e2e`: Generate and run end-to-end tests
- `/refactor-clean`: Clean up unused, duplicated, or overly complex code
- `/orchestrate`: Coordinate multi-agent workflows

### Skills Library

The included OpenCode skills cover practical engineering domains:

**Frontend development**

- React, Next.js, and Vue patterns
- State management with Redux, Zustand, and Context API
- Component architecture and design systems
- Frontend performance optimization

**Backend development**

- Node.js, Express, and API design
- REST and GraphQL API development
- Authentication and authorization patterns
- Caching, reliability, and service optimization

**Mobile development**

- React Native workflows
- iOS and Android development practices
- Cross-platform mobile architecture

**Database engineering**

- PostgreSQL and MySQL optimization
- ORM patterns for Prisma, TypeORM, and Sequelize
- Migration planning and schema review
- Query optimization and indexing

**Testing and quality**

- Unit, integration, and end-to-end testing
- Test-driven development
- Test fixtures, mocks, and coverage review
- Quality gates and verification workflows

**DevOps and deployment**

- Docker and containerization
- CI/CD pipeline patterns
- Deployment strategies
- Infrastructure-as-code guidance

**Security**

- OWASP Top 10 prevention
- Secure authentication and authorization
- Secret management
- Security review workflows

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tusharkrbarman/SkillsForOpenCode.git
   ```

2. Copy the `.opencode` folder into the root of your project:

   ```text
   your-project/
   |-- .opencode/
   |-- src/
   |-- package.json
   `-- ...
   ```

3. Start OpenCode from your project root:

   ```bash
   opencode
   ```

The included skills, agents, commands, prompts, and tools will be available from your OpenCode session.

## Usage Examples

### Plan a New Feature

```text
opencode
> /plan
I need to add user authentication with OAuth support.
```

### Review Code Changes

```text
opencode
> /code-review
Review the changes in my latest commit.
```

### Run a Security Review

```text
opencode
> /security
Run a security audit on my API endpoints.
```

### Use Test-Driven Development

```text
opencode
> /tdd
I need to implement a payment processing feature.
```

## Repository Structure

The `.opencode` workspace is organized into modular components:

- **Skills**: Domain-specific knowledge, patterns, and workflows
- **Agents**: Specialized AI assistants for focused development tasks
- **Commands**: Slash-command workflows for repeatable actions
- **Prompts**: Reusable prompt templates
- **Tools**: Helper scripts and OpenCode integrations
- **Instructions**: Project-level guidance for consistent behavior

## Documentation

Explore the included documentation and source folders:

- [Skills documentation](.opencode/skills/)
- [Agents guide](.opencode/agents/)
- [Commands reference](.opencode/commands/)
- [OpenCode workspace README](.opencode/README.md)
- [Migration guide](.opencode/MIGRATION.md)

## SEO Keywords

OpenCode skills, OpenCode agents, AI coding agents, AI-assisted development, developer workflows, code review agent, security review agent, test-driven development AI, software engineering skills, OpenCode commands, AI developer tools.

## Contributing

Contributions are welcome. See the [contribution guide](.opencode/CONTRIBUTING.md) for setup notes, workflow expectations, and project guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For issues, questions, or suggestions, open an issue in the [GitHub repository](https://github.com/tusharkrbarman/SkillsForOpenCode/issues).
