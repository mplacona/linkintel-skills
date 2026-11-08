# LinkIntel agent skill

An agent skill for [LinkIntel](https://www.getlinkintel.com). It lets Claude, ChatGPT or whatever agent harness you use draft X posts from evidence: your own stored X post results, the ranking weights from X's open-source recommendation code, and optional public X posts you save as references.

## Install

```bash
npx skills add mplacona/linkintel-skills
```

The skill shows your agent how to connect the LinkIntel MCP server (`https://www.getlinkintel.com/api/mcp`, OAuth in the browser), check that your data is ready, and turn a cited evidence brief into a draft in your voice.

## What's inside

- [`skills/linkintel-content-evidence/SKILL.md`](skills/linkintel-content-evidence/SKILL.md): setup, the tools to call and in what order, and the limits the evidence can and can't support.

The same skill is served at https://www.getlinkintel.com/SKILL.md. This repo is synced from it automatically, so open issues or suggestions here and we'll pick them up.

## Links

- Website: https://www.getlinkintel.com
- MCP docs: https://www.getlinkintel.com/docs/mcp
- Support: support@getlinkintel.com
