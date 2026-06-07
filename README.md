# UX PgM Skills Collection

Agentic skills, commands, and plugins for UX program management — from planning and stakeholders to delivery, alignment, and measurement. **30 skills** and **12 commands** across **6 plugins** for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Plugins

| Plugin | Skills | Commands | Description |
| --- | --- | --- | --- |
| [program-planning](./program-planning) | 5 | 2 | Plan and scope UX programs: roadmaps, dependency maps, scoping, capacity planning, and transparent prioritisation. |
| [stakeholder-comms](./stakeholder-comms) | 5 | 2 | Communicate with stakeholders: mapping, status reporting, executive updates, alignment workshops, and escalation. |
| [delivery-execution](./delivery-execution) | 5 | 2 | Drive delivery: cycle orchestration, risk registers, blocker triage, launch readiness, and retrospectives. |
| [cross-functional-alignment](./cross-functional-alignment) | 5 | 2 | Keep design, product, and engineering aligned: intake, decision logs, working agreements, RACI, and OKR linkage. |
| [measurement-ops](./measurement-ops) | 5 | 2 | Measure program health: KPIs, health dashboards, research ops coordination, design ops metrics, and impact reporting. |
| [process-design](./process-design) | 5 | 2 | Design how the team works: workflows, governance, rituals, scaling playbooks, and process retrospectives. |

## Quick Start

### Claude Code

**Step 1: Add the marketplace**

```
/plugin marketplace add Owl-Listener/ux-pgm-skills
```

**Step 2: Install plugins**

```
/plugin
```

Open the **Discover** tab to see all 6 plugins, then install the ones you want.

### Gemini CLI

Install individual plugins as workspace-scoped extensions:

```
git clone https://github.com/Owl-Listener/ux-pgm-skills /tmp/ux-pgm-skills
mkdir -p .gemini/extensions
cp -r /tmp/ux-pgm-skills/.gemini/extensions/. .gemini/extensions/
```

## What Are Skills and Commands?

- **Skills** are domain knowledge units (nouns). They teach the model about one topic.
- **Commands** are workflows (verbs). They chain skills together to do a job.

## All Commands

| Command | Plugin | Description |
| --- | --- | --- |
| `/program-planning:plan-program` | program-planning | Stand up a new UX program end to end. |
| `/program-planning:reprioritise` | program-planning | Re-prioritise the program backlog after a change. |
| `/stakeholder-comms:report-status` | stakeholder-comms | Generate a full status update for the program. |
| `/stakeholder-comms:align-stakeholders` | stakeholder-comms | Plan and run a stakeholder alignment session. |
| `/delivery-execution:run-cycle` | delivery-execution | Orchestrate a delivery cycle from plan to retro. |
| `/delivery-execution:readiness-review` | delivery-execution | Run a launch readiness review. |
| `/cross-functional-alignment:set-up-intake` | cross-functional-alignment | Stand up an intake and triage system. |
| `/cross-functional-alignment:clarify-roles` | cross-functional-alignment | Produce a RACI and working agreement for a program. |
| `/measurement-ops:define-metrics` | measurement-ops | Define a measurement framework for the program. |
| `/measurement-ops:report-impact` | measurement-ops | Compile an impact report for leadership. |
| `/process-design:design-workflow` | process-design | Design or redesign a team workflow. |
| `/process-design:scale-program` | process-design | Build a scaling playbook for a proven approach. |

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

MIT — see [LICENSE](./LICENSE).
