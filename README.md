# DETRAN MG: IPVA

### DETRAN MG: IPVA for Claude, ChatGPT and AI agents

DETRAN MG: IPVA, official-source lookup. Platform-hosted, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Versão em português](README.pt.md) · [Full docs (PT-BR)](docs/) · [Agent skill](skills/)

---

## One-click install

### Claude (Web and Desktop)

Anthropic unified MCP installation at `claude.ai/customize/connectors`. **The same link works for Claude Web and Claude Desktop** (just be logged in):

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (if the deeplink does not open): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → paste **Name** `DETRAN MG: IPVA` and **URL** `https://api.mcp.ai/p_detran_mg_ipva`.

### Cursor

[➕ Install DETRAN MG: IPVA in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=detran_mg_ipva&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9kZXRyYW5fbWdfaXB2YSJ9)

### VS Code (Copilot Chat)

[➕ Install DETRAN MG: IPVA in VS Code](vscode:mcp/install?name=detran_mg_ipva&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_detran_mg_ipva%22%7D)

### ChatGPT, Manus, OpenClaw and 40+ other clients

Works with any MCP client that speaks **MCP over HTTP**. The server URL is always:

```
https://api.mcp.ai/p_detran_mg_ipva
```

Per-client details: [INSTALL.md](INSTALL.md).

---

## Example prompts

```
Look up DETRAN MG: IPVA
```

---

## 1 tool available

| Tool | Description |
|---|---|
| `detran_mg_ipva_consultar` | DETRAN MG: IPVA, consulta em fonte oficial. |

Details for each tool: [docs/ferramentas.md](docs/ferramentas.md) (PT-BR)

---

## Pricing

Prepaid credit wallet, pay per use. See [docs/precos.md](docs/precos.md) (PT-BR).

---

## Privacy & data protection

- **Read-only**, no tool changes data at the source.
- **Sub-processors**: the LLM host you choose (Claude, ChatGPT, Cursor, your own agent). Full list in [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Data returned by the tools is sent to **the LLM host you choose**, a sub-processor outside our control. We recommend plans with training opt-out.

---

## FAQ

**Is the server open source?**
The server is proprietary (hosted). This repository is the public wrapper with manifests, docs and skills, all MIT.

**Can I use it with my own agent (not Claude/Cursor)?**
Yes, any client that speaks MCP over HTTP. URL: `https://api.mcp.ai/p_detran_mg_ipva`.


---

## Support

- 📧 [detran_mg_ipva@mcp.ai](mailto:detran_mg_ipva@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/detran_mg_ipva-mcp/issues)
- 📄 [docs/](docs/)

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_detran_mg_ipva` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
