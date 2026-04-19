# .AIIgnore (aiignore)

The .aiignore file is a configuration specification that tells AI coding agents and LLM-powered developer tools which files, directories, and content should not be read, processed, or modified. Modeled after .gitignore syntax, .aiignore files protect sensitive data, proprietary code, and personal information from being exposed to AI models during development workflows. Supported by JetBrains AI Assistant, Cursor, GitHub Copilot, Claude Code, Gemini Code Assist, and other AI coding tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/aiignore/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI Agents, Configuration, Developer Workflow, Security, Privacy, Developer Tools, LLM, Secrets Management

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### AIIgnore CLI
Command-line tool that generates .aiignore configuration files to protect secrets from AI coding tools including JetBrains AI, Cursor, GitHub Copilot, Claude Code, Codeium, and Windsurf with a single command.

**Human URL:** [https://github.com/yjcho9317/aiignore-cli](https://github.com/yjcho9317/aiignore-cli)

#### Tags:

 - CLI, Security, Developer Tools, TypeScript, Node.js, Secrets Management

#### Properties

- [GitHubRepository](https://github.com/yjcho9317/aiignore-cli)
- [npm Package](https://www.npmjs.com/package/aiignore-cli)

## Common Properties

- [AIIgnore CLI GitHub](https://github.com/yjcho9317/aiignore-cli)
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/)
- [GitHub Topics: aiignore](https://github.com/topics/aiignore)
- [Cursor AI Rules](https://docs.cursor.com/context/rules)
- [Claude Code Ignore](https://docs.anthropic.com/en/claude-code/)

## Features

| Name | Description |
|------|-------------|
| .gitignore-Compatible Syntax | Uses familiar glob pattern syntax from .gitignore so developers can immediately define exclusion rules. |
| Secrets Protection | Prevents AI models from reading .env files, credential files, API keys, private keys, and other sensitive data. |
| Multi-Tool Support | Single .aiignore file works across JetBrains AI, Cursor, GitHub Copilot, Claude Code, Codeium, and Windsurf. |
| Directory-Level Exclusion | Exclude entire directories from AI context with simple pattern rules (e.g., vendor/, node_modules/). |
| File Pattern Matching | Match files by extension, name, or path pattern to control AI model access granularly. |
| Project-Root Placement | Single file in project root applies rules across the entire project tree. |
| Proprietary Code Protection | Prevent proprietary algorithms, business logic, or licensed code from being sent to external AI APIs. |
| CLI Generation Tool | aiignore-cli generates boilerplate .aiignore files with one command, covering common secrets patterns automatically. |

## Use Cases

| Name | Description |
|------|-------------|
| API Key Protection | Exclude .env and config files containing API keys, tokens, and credentials from AI coding tool context. |
| Proprietary Algorithm Protection | Protect trade secrets and proprietary algorithms from being processed by AI models hosted on third-party infrastructure. |
| Compliance and Data Privacy | Ensure regulated data (PII, healthcare records, financial data) is not sent to external AI APIs. |
| Large File Exclusion | Exclude large binary files, build artifacts, and generated files that would waste AI context window. |
| Third-Party Code Exclusion | Prevent licensed third-party code and vendor directories from being included in AI context. |

## Integrations

| Name | Description |
|------|-------------|
| JetBrains AI Assistant | JetBrains IDEs (IntelliJ, PyCharm, WebStorm, etc.) AI Assistant respects .aiignore in project root. |
| Cursor AI Editor | Cursor IDE supports .cursorignore (similar concept) for controlling AI context access. |
| GitHub Copilot | GitHub Copilot supports content exclusion via repository settings and .copilotignore patterns. |
| Claude Code | Anthropic Claude Code CLI supports .claudeignore file for excluding files from AI context. |
| Codeium | Codeium AI coding assistant with configurable file exclusion patterns. |
| Windsurf | Codeium Windsurf AI editor with .windsurfignore support for context control. |
| Gemini Code Assist | Google Gemini Code Assist with project-level context exclusion configuration. |

## Artifacts

Machine-readable schema specifications organized by format.

### JSON Schema

- [aiignore-ai-ignore-config-schema.json](json-schema/aiignore-ai-ignore-config-schema.json)
- [aiignore-ai-ignore-rule-schema.json](json-schema/aiignore-ai-ignore-rule-schema.json)
- [aiignore-ai-tool-compatibility-schema.json](json-schema/aiignore-ai-tool-compatibility-schema.json)
- [aiignore-exclusion-pattern-schema.json](json-schema/aiignore-exclusion-pattern-schema.json)

### JSON Structure

- [aiignore-ai-ignore-config-structure.json](json-structure/aiignore-ai-ignore-config-structure.json)
- [aiignore-ai-ignore-rule-structure.json](json-structure/aiignore-ai-ignore-rule-structure.json)
- [aiignore-ai-tool-compatibility-structure.json](json-structure/aiignore-ai-tool-compatibility-structure.json)
- [aiignore-exclusion-pattern-structure.json](json-structure/aiignore-exclusion-pattern-structure.json)

### JSON-LD

- [aiignore-context.jsonld](json-ld/aiignore-context.jsonld)

### Examples

- [aiignore-ai-ignore-config-example.json](examples/aiignore-ai-ignore-config-example.json)
- [aiignore-ai-ignore-rule-example.json](examples/aiignore-ai-ignore-rule-example.json)
- [aiignore-ai-tool-compatibility-example.json](examples/aiignore-ai-tool-compatibility-example.json)
- [aiignore-exclusion-pattern-example.json](examples/aiignore-exclusion-pattern-example.json)

## Vocabulary

- [.AIIgnore Vocabulary](vocabulary/aiignore-vocabulary.yaml) — Taxonomy mapping 4 resources, 5 actions, and 2 personas across AI coding tool privacy and configuration domains

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
