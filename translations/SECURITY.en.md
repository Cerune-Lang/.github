# Security Policy

[日本語](https://github.com/Cerune-Lang/.github/blob/main/SECURITY.md) | English

This is the shared policy for Cerune-Lang repositories without their own SECURITY.md. If the affected repository has its own policy, refer to it instead.

Cerune-Lang projects are experimental software developed as personal projects. They are not intended for security-critical or production use. Security and specific response times cannot be guaranteed.

## Supported versions

Reports reproducible on the affected repository's default branch or latest published release (if any) are prioritized. Individual fixes or backports for older versions are not guaranteed.

## Usage assumptions and trust boundaries

Input checks and runtime limits, where provided, are not substitutes for operating-system-level isolation. Do not treat language implementations or generated code as sandboxes for safely running untrusted programs.

- When handling untrusted source, inputs, or generated artifacts, use a dedicated environment with appropriate isolation and restricted privileges, including during builds. Avoid access to sensitive data and use external mechanisms to limit resource usage.
- Connections to files, subprocesses, external tools, runtimes, hosts, and dependencies, and their privileges, should be selected by a trusted user or host and limited to what is necessary.
- Check distribution sources and versions, and compare SHA-256 hashes where provided. A matching hash alone does not establish the trustworthiness of the source or the safety of a program.
- Tests, differential testing, formal verification, and successful CI runs establish results under the conditions tested; they do not guarantee the security of the entire project.

## What to report

Reports of suspected security impact are welcome, including bypasses of intended access or defined resource limits, invalid memory access, unintended disclosure of sensitive information, and security issues affecting generated artifacts, external integrations, build or release processes, or dependencies.

## Reporting a vulnerability

1. If Private Vulnerability Reporting is enabled, use **Security → Advisories → Report a vulnerability** in the affected repository to submit a private report.
2. If private reporting is unavailable, use a private contact channel documented by that repository. If none is listed, ask only for a private contact method in a public issue, without describing the vulnerability.

Do not post vulnerability details or reproduction code in public issues, pull requests, or discussions.

Where possible, include the version or commit, OS and architecture, minimal reproduction steps, actual behavior, and suspected impact in the private report. Test only in environments you control or have explicit permission to test, and avoid affecting third-party environments or data. Do not include credentials, unrelated personal information, or secrets in reproductions, logs, configurations, or observation artifacts.

Crashes or incorrect output are not necessarily vulnerabilities. If in doubt, ask privately. For ordinary bugs and feature requests, use the affected repository's issues.

## Handling and disclosure

The private report is used to investigate reproduction conditions, affected scope, and potential fixes or mitigations. When making a fix, update regression tests and relevant documentation where possible, and consider affected versions and user guidance. Work is handled on a best-effort basis; response and fix deadlines and action on every report are not guaranteed. Avoid publishing exploit details before investigation, and discuss disclosure content and timing privately.
