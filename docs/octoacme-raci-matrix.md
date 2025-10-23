# OctoAcme — RACI Matrix Template

## Purpose
Define clear accountability and responsibility for project activities using the RACI framework (Responsible, Accountable, Consulted, Informed).

## RACI Definitions

- **R (Responsible)**: Person(s) who do the work to complete the task
- **A (Accountable)**: Person ultimately answerable for the task (only one A per task)
- **C (Consulted)**: People whose input is sought (two-way communication)
- **I (Informed)**: People kept up-to-date on progress (one-way communication)

---

## Project Initiation Phase

| Activity | Product Manager | Project Manager | Technical Lead | Scrum Master | UX Designer | QA Lead | Developer |
|----------|----------------|-----------------|----------------|--------------|-------------|---------|-----------|
| Define problem statement | A/R | C | C | I | C | I | I |
| Identify stakeholders | C | A/R | I | I | I | I | I |
| Create project one-pager | R | R | C | I | C | C | I |
| Set success metrics | A/R | C | C | I | C | I | I |
| Initial timeline estimation | C | A/R | R | C | I | I | R |
| Resource allocation | C | A/R | C | C | I | I | I |
| Risk identification | C | R | R | C | C | R | C |
| Approval to proceed | A | C | I | I | I | I | I |

---

## Planning Phase

| Activity | Product Manager | Project Manager | Technical Lead | Scrum Master | UX Designer | QA Lead | Developer |
|----------|----------------|-----------------|----------------|--------------|-------------|---------|-----------|
| Project kickoff facilitation | C | R | C | A/R | C | C | C |
| Backlog creation | A/R | C | C | C | C | C | C |
| Define acceptance criteria | A/R | C | C | C | R | R | C |
| Technical architecture design | C | I | A/R | I | C | C | C |
| UX research and design | C | I | C | I | A/R | C | I |
| Test strategy definition | C | I | C | I | C | A/R | C |
| Sprint planning | R | C | C | A/R | R | R | R |
| Story estimation | C | C | C | R | C | C | A/R |
| Definition of Done | R | C | R | A/R | C | R | R |
| Release planning | R | A/R | C | C | C | C | C |
| Dependency mapping | C | A/R | R | C | C | C | R |

---

## Execution & Tracking Phase

| Activity | Product Manager | Project Manager | Technical Lead | Scrum Master | UX Designer | QA Lead | Developer |
|----------|----------------|-----------------|----------------|--------------|-------------|---------|-----------|
| Daily standup facilitation | I | C | C | A/R | C | C | C |
| Feature development | C | I | C | I | C | I | A/R |
| Code reviews | I | I | A/R | I | I | C | R |
| Design implementation | C | I | C | I | A/R | I | R |
| Test case creation | I | I | C | I | C | A/R | C |
| Test execution | I | I | I | I | I | A/R | C |
| Bug triage | C | C | C | C | C | A/R | R |
| Impediment removal | C | C | R | A/R | C | C | C |
| Progress tracking | C | A/R | C | R | C | C | C |
| Risk management | C | A/R | R | C | C | C | C |
| Stakeholder updates | R | A/R | C | C | C | C | I |
| Sprint review | R | R | R | A/R | R | R | R |
| Sprint retrospective | C | C | C | A/R | C | C | C |

---

## Release & Deployment Phase

| Activity | Product Manager | Project Manager | Technical Lead | Scrum Master | UX Designer | QA Lead | Developer |
|----------|----------------|-----------------|----------------|--------------|-------------|---------|-----------|
| Release notes creation | A/R | C | C | I | C | C | C |
| Pre-release testing | C | C | C | I | C | A/R | R |
| Deployment approval | A | R | C | I | I | C | I |
| Deployment execution | I | C | R | I | I | C | A/R |
| Post-deploy verification | C | C | C | I | C | A/R | R |
| Rollback decision | A | R | R | I | I | R | R |
| Release communication | R | A/R | C | I | C | C | I |
| Production monitoring | C | C | R | I | I | R | A/R |

---

## Retrospective & Continuous Improvement

| Activity | Product Manager | Project Manager | Technical Lead | Scrum Master | UX Designer | QA Lead | Developer |
|----------|----------------|-----------------|----------------|--------------|-------------|---------|-----------|
| Retrospective facilitation | C | C | C | A/R | C | C | C |
| Action item identification | R | R | R | R | R | R | R |
| Action item tracking | C | A/R | C | R | C | C | C |
| Process improvements | C | C | C | A/R | C | C | C |
| Metrics review | R | R | R | C | C | R | C |
| Lessons learned documentation | C | A/R | C | R | C | C | C |

---

## Using This Matrix

1. **Review quarterly**: Update the RACI matrix based on team structure changes or process improvements
2. **Customize per project**: Adjust role assignments based on project size and complexity
3. **Resolve conflicts**: If multiple people are Accountable (A) for one task, clarify ownership
4. **Fill gaps**: If no one is Responsible (R) or Accountable (A), assign ownership
5. **Communicate clearly**: Share the matrix with all team members during project kickoff
6. **Use in onboarding**: Reference this matrix when onboarding new team members

---

## Notes

- For small teams, one person may fill multiple roles (e.g., Project Manager and Scrum Master)
- Not all roles need to be involved in every activity - blank cells indicate no involvement
- Adjust this template based on your organization's structure and project needs
- This matrix works best when combined with clear role definitions in [Roles & Personas](octoacme-roles-and-personas.md)

---

*Related: Closes #4*
