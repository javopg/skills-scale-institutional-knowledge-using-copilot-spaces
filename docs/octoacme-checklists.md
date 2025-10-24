# OctoAcme Operational Checklists

This document provides actionable checklists to standardize common handoffs and reduce friction in the delivery process.

---

## PR Checklist

**Owner:** Developer (author) + Reviewer

- [ ] Keep PR small (< 400 lines changed where possible)
- [ ] Link to related issue or feature ticket in PR description
- [ ] Ensure all CI checks pass (build, lint, tests)
- [ ] Add or update tests to cover changes
- [ ] Write a clear description explaining what and why
- [ ] Request at least 1 reviewer (2 for complex or high-risk changes)
- [ ] Address review feedback before merging

---

## Release Checklist

**Owner:** Project Manager + QA Lead

### Pre-Release Requirements
- [ ] All CI checks passing on release branch
- [ ] Smoke tests completed for critical user flows
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and validated
- [ ] Stakeholders notified of release window

### Deployment Steps
- [ ] Deploy to staging and verify functionality
- [ ] Run final smoke tests in staging environment
- [ ] Deploy to production during agreed maintenance window
- [ ] Monitor logs and metrics for errors or anomalies

### Post-Deploy Verification
- [ ] Verify critical flows in production
- [ ] Check error rates, performance metrics, and logs
- [ ] Confirm with stakeholders that release is successful
- [ ] Update status page or changelog if applicable

---

## Risk Escalation Checklist

**Owner:** Project Manager + Risk Owner

### Level 1: Low Impact (Team can resolve)
- [ ] Document the issue in the project risk register
- [ ] Assign an owner and mitigation plan
- [ ] Track in team standup or weekly sync
- [ ] Notify: Team lead, Scrum Master

### Level 2: Medium Impact (May delay milestone)
- [ ] Escalate to Project Manager immediately
- [ ] Assess impact on timeline and scope
- [ ] Identify workarounds or mitigation options
- [ ] Update stakeholders within 24 hours
- [ ] Notify: PM, Product Manager, Engineering Lead

### Level 3: High Impact (Blocker or critical issue)
- [ ] Escalate to senior leadership immediately
- [ ] Convene emergency sync with key decision-makers
- [ ] Document impact, options, and recommendation
- [ ] Prepare communication for affected stakeholders and customers
- [ ] Notify: PM, PdM, Engineering Lead, VP/Director, Stakeholders

---

## How to Use These Checklists

- Reference these checklists during relevant ceremonies (PR reviews, release planning, risk reviews).
- Customize as needed for specific projects, but aim to keep them lightweight and actionable.
- Store project-specific adaptations in the `.copilot/` directory for Copilot Spaces to reference.
