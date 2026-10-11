# boaring.agents
A Claude Code plugin marketplace for sharing skills, agents, commands and MCP servers.

## Usage

```
/plugin marketplace add lucasbozzo/boaring.agents
/plugin install example-plugin@boaring-agents
```

## Structure

```
.claude-plugin/marketplace.json   # marketplace catalog
plugins/<plugin-name>/
  .claude-plugin/plugin.json      # plugin manifest
  skills/<skill>/SKILL.md         # skills
  agents/*.md                     # agents
  commands/*.md                   # slash commands
  .mcp.json                       # MCP servers
```

To add a plugin, copy `plugins/example-plugin` and register it in `.claude-plugin/marketplace.json`.
