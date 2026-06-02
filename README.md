# Daily Market Digest

An automated AI-powered workflow that delivers a personalized daily news briefing every morning at 7am via email.

## What it does
- Pulls the latest headlines across macro economy, financial markets, geopolitics, and AI/tech from NewsAPI
- Runs all four category feeds in parallel
- Passes the raw articles through Claude (Anthropic) to synthesize the 5-7 most important stories with specific data points and context
- Formats the output as clean HTML and delivers it via Gmail every morning automatically

## Tech Stack
- **n8n** — workflow automation
- **NewsAPI** — news aggregation
- **Claude API (Anthropic)** — AI summarization
- **Gmail** — delivery
- **JavaScript** — data formatting and HTML conversion

## Why I built it
I wanted a way to stay current on macroeconomic and market developments without manually checking multiple sources every morning. This workflow runs fully autonomously — no manual input required after setup.
<img width="910" height="639" alt="image" src="https://github.com/user-attachments/assets/90a9ea99-6973-4547-a880-a11ea0cecbbe" />
