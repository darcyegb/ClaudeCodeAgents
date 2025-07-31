# Claude Code Agents Collection

This repository contains a collection of specialized agent definitions for [Claude Code](https://claude.ai/code), Anthropic's AI-powered coding assistant. These agents extend Claude Code's capabilities with specialized behaviors for common development tasks.

## What are Claude Code Agents?

Claude Code agents are specialized configurations that give Claude Code specific expertise and behaviors for particular tasks. When invoked, these agents help with focused areas like code review, testing, verification, and quality assessment.

## Available Agents

### 🔍 Jenny - Implementation Verification Agent
**File:** [`Jenny.md`](./Jenny.md)

Jenny verifies that implemented code actually matches project specifications. Use this agent when you need to:
- Verify authentication systems match security requirements
- Ensure database schemas implement multi-tenant specifications correctly
- Validate that implementations fulfill stated requirements
- Get independent assessment of feature completeness

### ✅ Claude MD Compliance Checker
**File:** [`claude-md-compliance-checker.md`](./claude-md-compliance-checker.md)

This agent ensures code changes adhere to project-specific guidelines defined in CLAUDE.md files. Use it to:
- Verify new implementations follow project standards
- Check that modifications comply with coding guidelines
- Ensure consistency with documented project principles
- Validate adherence to team conventions

### 🎯 Code Quality Pragmatist
**File:** [`code-quality-pragmatist.md`](./code-quality-pragmatist.md)

Reviews code for over-engineering, unnecessary complexity, and poor developer experience. Use this agent to:
- Identify over-engineered solutions
- Find unnecessary abstractions
- Spot premature optimizations
- Ensure code remains simple and maintainable

### 📊 Karen - Reality Check Agent
**File:** [`karen.md`](./karen.md)

Karen provides realistic assessment of project completion and creates actionable plans. Use when you need to:
- Assess actual vs claimed project completion
- Cut through incomplete implementations
- Create realistic plans to finish work
- Validate functional completeness without over-engineering

### 🔧 Task Completion Validator
**File:** [`task-completion-validator.md`](./task-completion-validator.md)

Verifies that claimed task completions are actually functional. Use this agent to:
- Validate authentication systems work end-to-end
- Ensure database integrations are functional
- Verify features work as intended, not just stubbed
- Confirm implementations meet underlying goals

### 🖥️ UI Comprehensive Tester
**File:** [`ui-comprehensive-tester.md`](./ui-comprehensive-tester.md)

Performs thorough UI testing across web and mobile platforms. This agent:
- Automatically selects appropriate testing tools (Puppeteer, Playwright, Mobile MCP)
- Tests user flows and edge cases
- Validates functionality across different platforms
- Performs systematic UI validation

## How to Use These Agents

These agent definitions are designed to be used with Claude Code. To use an agent:

1. Have Claude Code installed and configured
2. Reference the specific agent when you need its specialized capabilities
3. The agent will provide focused assistance based on its defined expertise

## Example Usage Scenarios

- **After implementing a feature:** Use `task-completion-validator` to ensure it's truly complete
- **Before committing code:** Run `code-quality-pragmatist` to check for over-engineering
- **When requirements seem met:** Use `Jenny` to verify implementation matches specifications
- **For UI changes:** Deploy `ui-comprehensive-tester` for thorough validation
- **To assess project status:** Use `Karen` for realistic completion assessment
- **After making changes:** Run `claude-md-compliance-checker` to ensure guideline compliance

## Contributing

These agents are maintained as part of a Claude Code workflow. Each agent definition follows a specific format that Claude Code can interpret and use.

## License

These agent definitions are provided as-is for use with Claude Code.

---

*These agents help ensure code quality, completeness, and adherence to best practices in software development projects.*