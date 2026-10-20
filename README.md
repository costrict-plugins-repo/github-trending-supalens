# Supalens Plugin for Claude Code

Connect your database to Claude via [Supalens](https://supalens.ai). Ask questions in natural language, generate SQL, and create dashboards — all from Claude Code or Claude App.

## Install

```
/plugin install Streamize-llc/supalens-plugin
```

## What it does

This plugin connects Claude to the Supalens MCP server, giving Claude access to these tools:

| Tool | Description |
|------|-------------|
| `get_setup_status` | Check connection and setup status |
| `list_data_sources` | List connected databases |
| `get_schema` | Get database schema (tables, columns, types) |
| `execute_sql` | Run SQL queries against your database |
| `list_dashboards` | List analytics dashboards |
| `list_widgets` | List widgets on a dashboard |
| `create_dashboard` | Create a new dashboard |
| `add_widget` | Add a chart or table widget |
| `register_query` | Save a query as a reusable widget |

## Setup

1. Install the plugin
2. Claude will authenticate via OAuth — you'll be redirected to sign in at supalens.ai
3. Once authenticated, Claude can access your connected databases

You need a Supalens account with at least one data source connected. Sign up at [supalens.ai](https://supalens.ai).

## Supported databases

- Supabase (PostgreSQL)
- PostgreSQL
- MySQL
- MariaDB

## Links

- [Supalens](https://supalens.ai)
- [MCP Integration Guide](https://supalens.ai/mcp)
