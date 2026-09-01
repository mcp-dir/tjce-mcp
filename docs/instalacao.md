# Instalação detalhada

Jurisprudência TJCE é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjce`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjce` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjce` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjce` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjce` (ou `servers.tjce` no VS Code) do config do cliente e reinicie.
