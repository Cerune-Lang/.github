# Contributing

[日本語](https://github.com/Cerune-Lang/.github/blob/main/CONTRIBUTING.md) | English

Thank you for your interest in Cerune-Lang. Bug reports, tests, documentation fixes, and small improvements are welcome. These projects are under active development and experimentation; their specifications and implementations may change.

This is shared guidance. Follow the affected repository's own contribution guidelines if it has them. If it has no code of conduct, see the [shared Code of Conduct](https://github.com/Cerune-Lang/.github/blob/main/CODE_OF_CONDUCT.md).

## Before working

- Read the affected repository's README, design documents, and existing issues and pull requests.
- Discuss substantial features or design changes in an issue before implementing them.
- If you are unsure which repository is relevant, see the [project list](https://github.com/Cerune-Lang/.github/blob/main/docs/projects.en.md).

## Bug reports

Where possible, include the version or commit, OS and architecture, reproduction steps, expected behavior, and actual behavior. Mention relevant tools or execution routes if applicable. Do not include secrets or personal information.

Do not report security issues in public issues or pull requests. Follow the affected repository's security policy or the [shared policy](https://github.com/Cerune-Lang/.github/blob/main/SECURITY.md).

## Development and verification principles

You do not need to understand every internal component before contributing. Check the roadmap and milestones before starting, where available.

- Distinguish implemented features, design proposals, and the scope of verification.
- Add regression tests for bug fixes where possible. When comparing runs with external side effects, use equivalent inputs and environments and isolate output locations and other affected resources.
- Verification experiments are welcome. Record the target commit, OS and architecture, tools and versions, inputs and seeds (where used), reproduction steps, baselines, results, and verification scope. Do not generalize finite examples into a guarantee for the entire project; record results that contradict a hypothesis or cannot be reproduced as well.
- Logs and observation artifacts may contain source text or paths. Review them before sharing and share only what is necessary. Avoid committing unintended generated files, secrets, or non-public data.

## Pull requests

- Keep changes focused and explain what changed and why.
- Follow the project's development instructions and run relevant tests and checks.
- Record commands and results, checks you could not run, and known limitations.
- Update both Japanese and English documentation where applicable.

See [Support](https://github.com/Cerune-Lang/.github/blob/main/SUPPORT.md) for questions and other contact routes. As these are personal projects, response and acceptance timelines cannot be guaranteed.
