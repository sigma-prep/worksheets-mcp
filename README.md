# Sigma Prep Worksheets MCP

Free printable math worksheets with answer keys, Pre-Algebra through Calculus, for any MCP client: Cursor, Claude, ChatGPT and others.

Ask for "a medium factoring trinomials worksheet with 20 problems" and get two PDF links: a student copy and a copy with the full answer key. About 480 topics across Pre-Algebra, Algebra 1, Geometry, Algebra 2, Precalculus, Calculus and Statistics. Free, with no account or API key.

## Connect

Remote MCP server (Streamable HTTP):

```
https://www.sigmaprep.io/api/mcp
```

**Cursor:** add this to `.cursor/mcp.json` (or use the file in this repo):

```json
{
  "mcpServers": {
    "sigma-prep-worksheets": { "url": "https://www.sigmaprep.io/api/mcp" }
  }
}
```

**Claude:** Settings → Connectors → Add custom connector → paste the URL above.
**ChatGPT:** available as the Sigma Prep Worksheets app.

## Tools

| Tool | What it does |
|---|---|
| `search_worksheets` | Finds worksheet topics that match a request in plain words. Returns each topic's id, difficulty levels, question types and page. |
| `create_worksheet` | Makes a printable worksheet for one topic as a PDF, plus a copy with the answer key. Options: difficulty (easy, medium, hard), number of problems (up to 40), question types, version. |

Both tools are read-only and store no personal data.

## Links

- Docs: https://www.sigmaprep.io/mcp
- Worksheets on the web: https://www.sigmaprep.io/worksheets
- Privacy: https://www.sigmaprep.io/privacy
- Support: support@sigmaprep.io
