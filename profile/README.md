# LienDeadline

Mechanics lien and preliminary notice deadlines for US construction suppliers.

[Website](https://liendeadline.com) · [Deadline calculator](https://liendeadline.com/calculator) · [State lien guides](https://liendeadline.com/state-lien-guides) · [Help center](https://liendeadline.com/help) · [Contact](https://liendeadline.com/contact)

## Open source

| Repository | What it is |
| --- | --- |
| [liendeadline-mcp](https://github.com/LienDeadline/liendeadline-mcp) | MCP server for AI agents. Returns supplier notice and lien filing deadlines with their statute sources, or flags a deadline for legal review instead of guessing, and serves lien guides for all 50 states and DC. Runs locally from [npm](https://www.npmjs.com/package/liendeadline-mcp) or hosted at `https://mcp.liendeadline.com/mcp`. |
| [skills](https://github.com/LienDeadline/skills) | Agent skill and plugins for Claude Code, Codex, Cursor, Gemini CLI and GitHub Copilot. |

## Try it

In Claude on the web, desktop or mobile, connect [LienDeadline from the Connectors directory](https://claude.ai/directory/connectors/liendeadline).

Add the hosted MCP server to Claude Code, with nothing to install and no key:

```bash
claude mcp add --transport http liendeadline https://mcp.liendeadline.com/mcp
```

Add the agent skill to any agent that reads [Agent Skills](https://agentskills.io):

```bash
npx skills add LienDeadline/skills
```

Results are calculated baselines from published state rules, not legal advice.

[Privacy policy](https://liendeadline.com/privacy) · [Terms of service](https://liendeadline.com/terms) · [Security](https://liendeadline.com/security)
