# ESPN MCP Server

> Connect AI assistants to live ESPN sports data via MCP — scores, standings, stats, odds, news, and schedules across 25+ leagues and sports.

[![Run on Apify](https://img.shields.io/badge/Run%20on-Apify-blue)](https://apify.com/scrapmania/espn-mcp-server?fpr=ebrunet001)

## Features

- **12 MCP tools** for comprehensive sports data access
- Live scores and scoreboards — real-time game updates
- Standings — current league tables and rankings
- Team info and rosters — complete team data
- Schedules — upcoming games and fixtures
- Game summaries — detailed post-game breakdowns
- Betting odds — pre-game odds from major sportsbooks
- Athlete profiles — player bios and career stats
- Rankings — AP, coaches polls, and power rankings
- News — latest headlines by sport or league
- Search — find any team, player, or league
- **25+ sports & leagues**: NFL, NBA, MLB, NHL, WNBA, College Football, College Basketball, Premier League, La Liga, Bundesliga, Serie A, Champions League, MLS, UFC, PGA, F1, NASCAR, ATP, WTA, and more
- **No ESPN account or API key required**
- Works with **Claude Desktop, Claude Code, ChatGPT** and any MCP-compatible client

## Quick Start

Connect to the MCP server using the Streamable HTTP endpoint:

```
https://scrapmania--espn-mcp-server.apify.actor/mcp?token=YOUR_APIFY_TOKEN
```

1. [Get your free Apify API token](https://console.apify.com/account/integrations?fpr=ebrunet001)
2. Add the URL above as a custom MCP connector in your AI client
3. Start asking about any sport, team, player, or game

### Claude Desktop Setup

Go to **Settings → MCP Servers → Add Custom Connector** and paste the URL above (replace `YOUR_APIFY_TOKEN` with your actual token).

## Example Prompts

Once connected, your AI assistant can handle prompts like:

- *"What are today's NBA scores?"*
- *"Show me the current Premier League standings"*
- *"Who's leading the F1 championship this year?"*
- *"Give me the odds for tonight's NFL games"*
- *"Summarize yesterday's Champions League matches"*
- *"What's the latest news about the Lakers?"*

## Data Freshness

| Data Type | Cache Duration |
|---|---|
| Live game scores | 60 seconds |
| Standings & rosters | 5 minutes |
| Historical data | Instant |

## Pricing

Pay-per-event — you only pay for the tools you actually use. The free tier gives you **$5 free credits every month**, enough for hundreds of tool calls.

## Links

- **Apify Store**: [ESPN MCP Server](https://apify.com/scrapmania/espn-mcp-server?fpr=ebrunet001)
- **Author**: [mrbridge on Apify](https://apify.com/mrbridge?fpr=ebrunet001)

## Related MCP Servers

- [League of Legends MCP Server](https://apify.com/scrapmania/lol-mcp-server?fpr=ebrunet001) — 13 tools for LoL player data, match history, and AI coaching
- [Teamfight Tactics MCP Server](https://apify.com/scrapmania/teamfight-tactics-mcp-server---ai-game-analysis?fpr=ebrunet001) — 10 tools for TFT compositions, augments, and AI coaching
- [Todoist MCP Server](https://apify.com/scrapmania/todoist-ai-assistant?fpr=ebrunet001) — 35 tools for AI-powered task management

---

*Built by [mrbridge](https://apify.com/mrbridge?fpr=ebrunet001)*
