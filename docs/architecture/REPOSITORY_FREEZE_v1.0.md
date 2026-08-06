# Repository Freeze v1.0

Status

Frozen

Purpose

The Repository Architecture is now considered the canonical documentation structure of SubWise.

From this point forward, the repository structure is considered stable.

Rules

• No documentation layer may be created outside the canonical repository structure.

• Every new document must be published directly inside its canonical location.

• Existing canonical folders must not be renamed.

• Existing canonical folders must not be removed.

• Repository Architecture modifications require an approved ADR.

Scope

This freeze applies only to the repository structure.

It does NOT freeze:

- Product evolution
- Product documentation
- Milestones
- Research
- Decisions
- Architecture documents

Those continue evolving inside their canonical locations.

Repository Guardian Responsibilities

From this moment onward the Repository Guardian becomes responsible for:

- protecting repository consistency;

- detecting duplicated concepts;

- detecting orphan documents;

- detecting broken references;

- detecting documentation outside the canonical structure;

- proposing improvements,

without modifying the repository unless an ADR explicitly authorises the change.
