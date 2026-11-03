# ChronoTab for Cursor

Log time on GitHub issues in [ChronoTab](https://chronotab.com) without leaving Cursor.

This plugin connects Cursor to the ChronoTab MCP server at `https://api.chronotab.com/v1/mcp`. It contains configuration only; no code runs on your machine.

## What it can do

- Show, start and stop your timer
- Log time against a GitHub issue
- List your entries
- Search issues in your organisation's tracked repositories
- Find days with missing time
- List clients and show hours per client

Entries it creates are marked "AI assistant" in ChronoTab. It cannot edit or delete entries, discard timers, or submit, approve or void timesheets. Do those in ChronoTab.

## Setup

1. Sign in to ChronoTab at [app.chronotab.com](https://app.chronotab.com).
2. Open **Profile**, then **AI assistant**, and create an API key. Copy it; it is shown once.
3. Install this plugin in Cursor and set **ChronoTab API key** (`CHRONOTAB_API_KEY`) to the key you copied.
4. Ask Cursor "what's my timer?" to check the connection.

The key acts as you, in the organisation it was created for. Revoke it on your Profile if you stop using Cursor or think it has leaked.

## Try

- "Start a timer on api#123"
- "Log 1h30m on web#88 for yesterday, code review"
- "Which days am I missing time for this week?"
- "How many hours have we logged for Acme this month?"

## Help

- Guide: [Use ChronoTab from your AI assistant](https://chronotab.com/docs/your-account/use-chronotab-from-your-ai-assistant/)
- Support: support@chronotab.com

## License

MIT
