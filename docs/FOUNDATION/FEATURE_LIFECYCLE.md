# Feature Lifecycle

Purpose: Define the governance stages for features and the responsibilities expected at each stage. This document is governance-only: it does not prescribe implementation workflows.

Stages and responsibilities

1) Feature Proposal
- Purpose: Capture the idea, motivation, target user outcome, and a minimal acceptance hypothesis.
- Owner: [PLACEHOLDER: proposer / product role]
- Artifacts: proposal document or issue, high-level problem statement, initial success hypothesis.

2) Evaluation
- Purpose: Assess desirability, feasibility, and viability; surface risks and major unknowns.
- Owner: [PLACEHOLDER: product + stakeholders]
- Artifacts: evaluation notes, user research links, expected ROI / metrics.

3) Architecture Validation
- Purpose: Confirm architectural fit and identify required changes or constraints; validate feasibility with architecture owner.

This stage verifies architectural consistency. It never changes product philosophy. Changes to philosophy require a formal Architecture Decision Record (ADR).

- Owner: [PLACEHOLDER: architecture owner / tech lead]
- Artifacts: architecture notes, constraints, required integrations, non-functional requirements.

4) Milestone
- Purpose: Decide scope, milestone definition, acceptance criteria, and schedule (the milestone this feature belongs to).

Milestones implement architecture. They never redefine it.

- Owner: [PLACEHOLDER: product manager]
- Artifacts: milestone ticket, scoped requirements, acceptance criteria.

5) Implementation
- Purpose: Deliver the scoped work according to the milestone; development and integration happen here.
- Owner: [PLACEHOLDER: engineering team]
- Artifacts: implementation tasks, code, documentation updates.

6) Testing
- Purpose: Verify the feature meets acceptance criteria, performs reliably, and respects constraints (privacy, security).
- Owner: [PLACEHOLDER: QA / engineering]
- Artifacts: test plans, test results, bug reports, regression test coverage.

7) Release
- Purpose: Deploy the feature to users according to release policy and observe initial telemetry.
- Owner: [PLACEHOLDER: release manager / engineering]
- Artifacts: release notes, rollout plan, monitoring dashboards.

8) Maintenance
- Purpose: Support, monitor and iterate on the feature after release; address production issues and small improvements.
- Owner: [PLACEHOLDER: support / engineering]
- Artifacts: issue backlog, incident reports, maintenance schedule.

9) Retirement
- Purpose: Remove the feature when it no longer serves product goals; plan removal with data migration and communication as needed.

Product history should remain understandable after retirement. Retirement must never rewrite historical documentation.

- Owner: [PLACEHOLDER: product + engineering]
- Artifacts: retirement plan, data migration notes, communication plan.

Notes:
- Each stage should link to any ADR that materially changes product or architecture decisions.
- Owners are placeholders — the product team must assign concrete roles.
- This document avoids implementation-level CI/CD or sprint procedures; those live in development runbooks if needed.
