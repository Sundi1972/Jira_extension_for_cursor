# Jira MCP for Cursor

Seamless Jira integration for Cursor IDE via Model Context Protocol (MCP).

## Features

- 🎯 List and search Jira tickets
- 📖 Read ticket details
- ✏️ Update ticket status
- 💬 Add comments
- 🔐 Secure one-time configuration

## Quick Start

```bash
# Install
pip install jira-mcp-cursor

# Configure
jira-mcp configure

# Install to Cursor
jira-mcp install
```

## Development

```bash
# Setup
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -e ".[dev]"

# Run
python -m jira_mcp_cursor
```

## Documentation

See `/docs` folder for complete design documentation.

## License

MIT

