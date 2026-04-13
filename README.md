# SkillsForOpenCode

This repository contains a comprehensive plugin for OpenCode, providing a set of agents, commands, hooks, and skills to enhance your coding experience with AI assistance.

## What is this plugin?

This plugin brings powerful AI-driven development tools to OpenCode, including:

- **12 Specialized Agents**: For planning, architecture, code review, security analysis, testing, and more
- **31 Commands**: Quick access to common development workflows like TDD, code review, build fixes, etc.
- **Custom Hooks and Skills**: Automated integrations and advanced capabilities

## Installation and Usage

Download this repository (e.g., as a ZIP from GitHub) and place it inside your project directory. Then, call `opencode` from the root level of your project. It will pick up all the skills and instructions. This works for all free models in OpenCode.

## Features Overview

### Agents
- planner: Implementation planning
- architect: System design
- code-reviewer: Code review
- security-reviewer: Security analysis
- tdd-guide: Test-driven development
- build-error-resolver: Build error fixes
- e2e-runner: E2E testing
- doc-updater: Documentation updates
- refactor-cleaner: Dead code cleanup
- go-reviewer: Go code review
- go-build-resolver: Go build errors
- database-reviewer: Database optimization

### Commands
- `/plan`: Create implementation plan
- `/tdd`: TDD workflow
- `/code-review`: Review code changes
- `/security`: Security review
- `/build-fix`: Fix build errors
- `/e2e`: E2E tests
- `/refactor-clean`: Remove dead code
- `/orchestrate`: Multi-agent workflow
- And many more...

For detailed documentation, see [.opencode/README.md](.opencode/README.md).

## Contributing

See [CONTRIBUTING.md](.opencode/CONTRIBUTING.md) for contribution guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.