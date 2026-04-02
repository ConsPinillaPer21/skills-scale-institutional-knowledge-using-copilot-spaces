# OctoAcme — Roles & Personas RACI Matrix

This matrix maps key project activities across the delivery lifecycle to the roles defined in [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md).

**RACI Key**
| Code | Meaning |
|------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; final decision-maker |
| **C** | Consulted — provides input before or during the activity |
| **I** | Informed — kept up to date on progress or decisions |

---

## Project Lifecycle Activities

| Activity | Developer | Product Manager | Project Manager | QA Lead | Scrum Master | UX/UI Designer | Business Analyst | Technical Writer | Stakeholder / Sponsor | Eng. Manager / Tech Lead |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation & Planning** |
| Define project goals & success metrics | I | A | C | I | I | C | C | I | A | C |
| Stakeholder identification | I | C | R | I | I | I | C | I | A | I |
| Create project plan & timeline | C | C | A/R | C | C | I | C | I | I | C |
| Define scope & backlog | C | A | C | C | C | C | R | I | C | C |
| Write user stories & acceptance criteria | C | A | I | C | C | C | R | I | C | C |
| Define Definition of Done (DoD) | C | C | C | A/R | C | C | C | I | I | C |
| **Design** |
| UX research & usability testing | I | C | I | I | I | A/R | C | I | C | I |
| Create wireframes & prototypes | I | C | I | I | I | A/R | C | I | C | I |
| Architecture & technical design | R | C | I | C | I | I | C | I | I | A |
| Design review & approval | C | C | I | I | I | A | C | I | C | R |
| **Execution & Tracking** |
| Sprint planning facilitation | C | C | C | C | A/R | I | C | I | I | C |
| Feature implementation | A/R | I | I | C | I | C | C | I | I | C |
| Code review | A/R | I | I | C | I | I | I | I | I | A |
| Daily standup | R | I | C | R | A | I | I | I | I | C |
| Test execution (automated & manual) | C | I | I | A/R | I | I | C | I | I | C |
| Defect triage & resolution | R | C | I | A | I | C | C | I | I | C |
| Track velocity & burndown | I | I | R | I | A | I | I | I | I | I |
| Update risk register | C | C | A/R | C | C | I | C | I | I | C |
| **Quality Gates & Release** |
| Feature acceptance / UAT sign-off | C | A | C | R | I | C | C | I | A | C |
| Release go/no-go decision | C | C | A | R | I | I | I | I | A | C |
| Release notes authoring | C | C | I | C | I | I | C | A/R | I | C |
| Deployment execution | A/R | I | C | C | I | I | I | I | I | A |
| Post-deploy verification | R | I | C | A/R | I | I | I | I | I | C |
| Rollback decision | R | C | C | C | I | I | I | I | A | A |
| **Communication & Stakeholder Mgmt** |
| Weekly status reporting | I | C | A/R | C | C | I | C | I | I | C |
| Escalation handling | C | C | A | C | C | I | C | I | A | C |
| Stakeholder milestone readout | I | C | R | C | I | C | C | C | A | C |
| Risk escalation to sponsor | I | C | R | C | I | I | C | I | A | C |
| **Retrospectives & Improvement** |
| Facilitate retrospective | C | C | C | C | A/R | I | I | I | I | I |
| Capture & track action items | C | C | R | C | A | I | C | I | I | C |
| Process documentation updates | C | C | C | C | C | I | C | A/R | I | C |
| Continuous improvement initiatives | C | C | R | C | C | C | C | C | A | C |

---

## Notes

- **A/R** in a single cell means one person is both Accountable and Responsible (common for small teams or where a single owner exists end-to-end).
- Where multiple roles share an **R**, the team should designate a primary owner to avoid ambiguity.
- Adjust this matrix to reflect actual team structure; not all roles may be staffed on every project.
- See [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) for full role definitions and interaction details.
