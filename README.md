# AI Daily Workflow

A curated collection of opencode agents and skills for daily software development workflows.

## Agents

Specialized AI agents for different aspects of software development:

| Agent | Description |
|-------|-------------|
| `frontend-engineer` | UI/UX implementation, state management, component architecture |
| `backend-engineer` | Server-side logic, API development, database integration |
| `security-engineer` | Security audits, vulnerability scanning, secure coding |
| `team-leader` | Task coordination, sprint planning, team workflow management |
| `code-reviewer` | Code quality analysis, best practices enforcement |
| `architect` | System design, technology selection, technical specifications |
| `docs-generator` | Documentation creation, API docs, README files |
| `product-manager` | Feature planning, requirements gathering, prioritization |

### Creating Agents

Place agent definitions in `agents/<agent-name>.md`:

```bash
agents/<agent-name>.md
```

## Skills

Specialized knowledge packages that extend agent capabilities:

| Skill | Description |
|-------|-------------|
| `find-skills` | Discover and install new skills from the ecosystem |
| `fullstack-dev` | Full-stack development patterns and best practices |
| `sql-patterns` | SQL query optimization and patterns |
| `frontend-patterns` | Frontend architecture and UI patterns |
| `typescript` | TypeScript development guidelines |
| `javascript` | JavaScript best practices |
| `ruby` | Ruby/Rails development patterns |

### Installing Skills

Skills can be installed from:
- https://skills.sh/
- https://skillsmp.com/

```bash
npx skills add <owner/repo@skill>
```

## Configuration

The project uses `opencode.json` for configuration. See https://opencode.ai/config.json for schema details.
