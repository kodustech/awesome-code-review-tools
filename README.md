# Awesome Code Review Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of the best code review tools, platforms, and automation for modern development teams — from AI-powered agents to static analysis and linters.

> **Maintainer Note:** This list is curated and maintained by the engineering team at **[Kodus](https://kodus.io)**. We love open source and building better devtools.

## Contents

- [AI-Powered Code Review Tools](#ai-powered-code-review-tools)
- [Static Analysis & Linters](#static-analysis--linters)
- [Security-Focused Code Review](#security-focused-code-review)
- [IDE Assistants & Copilots](#ide-assistants--copilots)
- [CLI & Local Workflows](#cli--local-workflows)
- [Code Review Platforms](#code-review-platforms)
- [Benchmarks & Research](#benchmarks--research)

---

## AI-Powered Code Review Tools

_Tools that use AI/LLMs to review Pull Requests, comment on code, and suggest fixes automatically._

_Note: This list is not intended to compare tools; as maintainers of Kodus, we are biased._

- **[Kodus](https://kodus.io)** (⭐ _Maintainer_)
  An AI code review agent focusing on high-signal feedback. It allows teams to define custom review guidelines (using plain English) to enforce architectural patterns and best practices, reducing noise in the review process.

- **[CodeRabbit](https://coderabbit.ai)** — Provides line-by-line feedback on pull requests and generates summaries of changes. Features a chat interface within the PR to discuss the feedback with the AI.

- **[Greptile](https://greptile.com)** — An AI engine that indexes the entire codebase to understand context. It focuses on answering complex questions about the repo and reviewing code with full-repository awareness.

- **[Cursor Bugbot](https://cursor.com/bugbot)** — AI-powered PR review that runs automatically to catch real bugs and security issues with a low false-positive rate.

- **[PR Quality Analyzer](https://creativecodingsolutions.github.io/pr-quality-analyzer/)** — Free web tool to analyze any GitHub pull request for quality metrics. Paste a PR URL and get an A-F score with detailed breakdown. No sign-up required.

## Static Analysis & Linters

_Traditional and AI-enhanced tools for enforcing code quality, style, and correctness._

- **[ESLint](https://eslint.org)** — The standard pluggable linter for JavaScript and TypeScript.
- **[Pylint](https://pylint.org)** — Source code analyzer for Python that checks for errors, coding standards, and code smells.
- **[RuboCop](https://rubocop.org)** — Ruby static code analyzer and formatter based on the community Ruby style guide.
- **[SonarQube](https://www.sonarsource.com/products/sonarqube/)** — Continuous inspection platform for code quality and security across 30+ languages.
- **[PMD](https://pmd.github.io)** — Cross-language static analyzer that finds common programming flaws in Java, Apex, and more.
- **[Checkstyle](https://checkstyle.org)** — Development tool to help write Java code that adheres to a coding standard.

## Security-Focused Code Review

_Tools focusing specifically on vulnerabilities, SAST, and secure code review._

- **[Snyk DeepCode](https://snyk.io/platform/deepcode-ai/)** — AI-powered engine to find security flaws faster than traditional static analysis.
- **[Semgrep](https://semgrep.dev)** — Combines rule-based static analysis with AI to reduce false positives in security scanning.
- **[CodeQL](https://codeql.github.com)** — GitHub's semantic code analysis engine for finding vulnerabilities across codebases.
- **[Bandit](https://github.com/PyCQA/bandit)** — Security-focused static analyzer designed to find common issues in Python code.
- **[Brakeman](https://brakemanscanner.org)** — Static analysis security tool for Ruby on Rails applications.

## IDE Assistants & Copilots

_Tools that integrate with editors or local environments for autocomplete, chat, and agentic coding._

- **[GitHub Copilot](https://github.com/features/copilot)** — The standard AI pair programmer for autocomplete, chat, and inline edits.
- **[Cursor](https://cursor.com)** — AI-first code editor with built-in chat, autocomplete, and agent workflows.
- **[Claude Code](https://claude.com/product/claude-code)** — Claude's coding agent for terminal, IDE, and web workflows that can manage large codebases and implement changes.
- **[OpenAI Codex](https://developers.openai.com/codex/ide)** — OpenAI's coding agent that can read, modify, and run code, available as a VS Code extension with optional cloud delegation.
- **[Google Antigravity](https://antigravity.google)** — Agent-first IDE with tab autocomplete, natural language commands, and cross-surface agents across editor, terminal, and browser.
- **[Kilo Code](https://kilo.ai)** — Open-source agentic engineering platform with IDE/CLI support, tab autocomplete, and multi-agent orchestration.
- **[Cline](https://github.com/cline/cline)** — Autonomous IDE agent that can create/edit files, run commands, and use the browser with user approval.
- **[OpenCode](https://opencode.ai)** — Open-source coding agent for terminal, IDE, or desktop with multi-session workflows and broad model support.

## CLI & Local Workflows

_Command-line tools for local code review and developer workflows._

- **[Aider](https://github.com/paul-gauthier/aider)** — AI pair programming in your terminal.
- **[Mentat](https://github.com/biobootloader/mentat)** — Coordinate edits across multiple files using command line.
- **[OpenCommit](https://github.com/di-sukharev/opencommit)** — Generates semantic git commit messages automatically.
- **[Reviewdog](https://github.com/reviewdog/reviewdog)** — Automated code review tool that posts review comments from any linter output.
- **[danger](https://danger.systems)** — Automates common code review chores by running rules during CI.

## Code Review Platforms

_Platforms and services built specifically for the code review workflow._

- **[GitHub Pull Requests](https://github.com/features/code-review)** — Built-in code review with inline comments, suggestions, and review assignments.
- **[GitLab Merge Requests](https://docs.gitlab.com/ee/user/project/merge_requests/)** — Integrated review workflow with approvals, threads, and CI integration.
- **[Gerrit](https://www.gerritcodereview.com)** — Web-based code review tool for Git, used by large open-source projects like Android and Chromium.
- **[Phabricator](https://www.phacility.com/phabricator/)** — Suite of open-source tools for code review, project management, and repository hosting.
- **[Crucible](https://www.atlassian.com/software/crucible)** — Atlassian's code review tool for Git, SVN, and Perforce repositories.

## Benchmarks & Research

_Benchmarks and key papers on code review automation._

- **[Code Review Benchmark](https://codereviewbench.com/)** — Comprehensive evaluation of LLM performance in AI-powered code review tasks.
- **[SWE-bench](https://www.swebench.com/)** — Evaluation framework for language models on real-world software engineering issues.
- **[HumanEval](https://github.com/openai/human-eval)** — OpenAI's dataset for evaluating code generation capabilities.
- **[Lessons from Building Static Analysis Tools at Google](https://cacm.acm.org/magazines/2018/4/226371-lessons-from-building-static-analysis-tools-at-google/fulltext)** — Why low false-positive rates are crucial for adoption of automated review tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
If you are a founder or maintainer of a tool listed here and want to update your description, feel free to open a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
