# mcpcourse

This project uses the MCP FastMCP server in `server/weather.py`.

## Install dependencies

```powershell
python -m pip install --quiet -e .
```

## Run the MCP server

Correct usage:

```powershell
mcp run server/weather.py
```

Or, to use the MCP inspector:

```powershell
mcp dev server/weather.py
```

> Do not run `uv run mcp server/weather.py` directly. The `mcp` CLI requires a subcommand such as `run` or `dev`.
