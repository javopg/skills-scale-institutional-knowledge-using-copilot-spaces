# OctoAcme Operational Checklists

Short, actionable checklists to reduce handoff friction and speed decision-making.

## PR Checklist (owner: author)
- [ ] Link the issue and include clear acceptance criteria in the PR description
- [ ] Keep PRs small and focused (prefer <400 lines)
- [ ] Ensure CI passes (unit/integration tests + lint)
- [ ] Add testing notes / how reviewers can validate changes
- [ ] Request at least one reviewer and reference necessary approvers
- Ownership: Author prepares PR; Reviewer verifies tests and acceptance.

## Release Checklist (owner: PM / Release Manager)
- [ ] All acceptance criteria met and PRs merged into release branch
- [ ] CI and security scans pass on release branch
- [ ] Release notes drafted and reviewed by PdM / Tech Writer
- [ ] Rollback & mitigation plan documented
- [ ] Smoke tests ready and executed after deploy
- [ ] Announce release to stakeholders and support
- Ownership: PM/Release Manager coordinates; Developers and QA validate.

## Risk Escalation Checklist (owner: anyone who discovers blocker)
- [ ] Triage in next standup (Level 1: team-level)
- [ ] If unresolved, PM escalates to Product Lead & dependent teams (Level 2)
- [ ] If business-impacting, notify Sponsor and follow incident playbook (Level 3)
- [ ] Update Risk Register with owner and mitigation
- [ ] Log decisions and next steps in project README / issue
- Ownership: Discoverer triages; PM drives escalation and updates register.
