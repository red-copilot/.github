# Contributing to Red Copilot

Thanks for helping improve Red Copilot projects.

## Before you start

- Read the target repository's README and any project-specific contribution guide.
- Check existing issues and pull requests before starting substantial work.
- For significant changes, open an issue or discussion first so the approach can be aligned.
- Work only with systems, datasets, and environments you own or are explicitly authorized to test.

## Pull requests

Please keep changes focused and make them easy to review.

Include, where relevant:

- **Problem:** what is wrong or missing?
- **Approach:** why is this the right change?
- **Validation:** commands run, tests added, and results observed.
- **Risk:** compatibility, security, migration, or operational impact.
- **Evidence:** logs or reproducible steps, with secrets and sensitive data removed.

## Engineering expectations

- Prefer explicit interfaces and small, reviewable changes.
- Treat tool output and model-generated claims as untrusted until validated.
- Add or update tests for behavior changes and regression fixes.
- Document configuration, permissions, failure modes, and breaking changes.
- Never commit credentials, tokens, private target data, or unredacted security findings.
- Do not claim a test passed unless it was actually run.

## Security-sensitive changes

Explain the authorization boundary and expected failure behavior. Use synthetic fixtures or a controlled lab whenever possible. Do not include instructions or payloads aimed at unauthorized real-world targets.

## License and review

By submitting a contribution, you agree that it may be distributed under the license stated in the relevant repository. Each repository's own license and contribution requirements take precedence.
