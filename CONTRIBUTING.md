<!-- root/CONTRIBUTING.md -->
# Contributing to NorthFi projects

## Scope and expectations

Please open an issue before proposing a large redesign. Keep pull requests focused, with an explanation of the behavior change and the associated risk.

## Validation

- Include regression tests for bug fixes whenever practical.
- Run the project's available CI checks and document manual validation.
- For network, firewall, RouterOS, backup, or automation changes, include a rollback plan and identify destructive operations.
- Never commit live credentials, private keys, production configuration exports, or customer data.

## Releases

Use semantic version tags (for example, `v1.2.3`) where a project has stable release support. Record user-visible changes in release notes. Do not assume that an automated build artifact has been verified on a production system.

## Pull request checklist

- [ ] Scope and compatibility changes are documented.
- [ ] Tests were added or a reason is given for their absence.
- [ ] CI passed or failures are explained.
- [ ] Security and operational risks were reviewed.
- [ ] Rollback and deployment considerations are described when applicable.
