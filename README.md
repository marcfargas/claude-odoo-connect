# claude-odoo-connect

Claude Code plugin — connect Claude to your Odoo instance. Works with Claude Code and Claude Cowork.

## What you get

- **MCP tools** — search, read, create, and write Odoo records through natural language
- **Odoo knowledge modules** — 5,200+ lines of battle-tested patterns for working with Odoo (CRUD, domains, field types, modules, accounting, attendance, timesheets, and more)

## Install

```bash
# From the marketplace
/install claude-odoo-connect

# Or local
claude --plugin-dir /path/to/claude-odoo-connect
```

## Setup

Set environment variables for your Odoo instance:

```bash
export ODOO_URL=https://your-odoo.example.com
export ODOO_DB=your-database
export ODOO_USER=admin
export ODOO_PASSWORD=your-password
```

Start a Claude session — the MCP server connects automatically.

## MCP Tools

| Tool | Description |
|------|-------------|
| `odoo_discover` | Semantic model search |
| `odoo_model_info` | Full field schema for a model |
| `odoo_search` | Search records with domain filters |
| `odoo_get` | Fetch specific records by ID |
| `odoo_create` | Create new records |
| `odoo_write` | Update existing records |
| `odoo_get_related` | Follow relational fields |

## For developers

See [claude-odoo-dev](https://github.com/marcfargas/claude-odoo-dev) for the developer plugin with state management, test environments, and dev workflow agents.

## Part of odoo-toolbox

This plugin is powered by [@marcfargas/odoo-toolbox](https://github.com/marcfargas/odoo-toolbox). Skills are synced automatically when the underlying packages are updated.

## License

LGPL-3.0 (code), CC0-1.0 (knowledge modules)
