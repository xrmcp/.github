# xrMCP - Extended Reality of MCP

Install AI tools like browser extensions, without deploying hardcoded servers.

xrMCP is a JSON manifest format and runtime protocol that lets you describe any API as a real, named MCP tool. Instead of shipping a server, you share a `.xrmcp.json` file. Any xrMCP-compatible runtime imports it and exposes it as a proper MCP tool — with the right name, schema, and behaviour.

Today, sharing an MCP integration means sharing a server — code to deploy, infrastructure to run, credentials to manage. There is no standard way to share just a tool. xrMCP fills that gap: describe your tool once in JSON, install it anywhere.

| | |
|---|---|
| [xrmcp/xrmcp](https://github.com/xrmcp/xrmcp) | Specification and schema |
| [xrmcp/go-sdk](https://github.com/xrmcp/go-sdk) | Go SDK and runtime |
| [xrmcp/python-sdk](https://github.com/xrmcp/python-sdk) | Python SDK |
| [xrmcp/cli](https://github.com/xrmcp/cli) | CLI — `xrmcp server start`, `xrmcp tool install` |
| [xrmcp/registry](https://github.com/xrmcp/registry) | Public tool registry *(coming soon)* |
