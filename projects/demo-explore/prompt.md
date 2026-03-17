# Reproducible Prompt — Demo Explore

Paste the prompt below into yokusto to recreate this project from scratch.

## Prompt

> Here's a query I use:
> ```kql
> StormEvents | summarize count() by State | top 10 by count_
> ```
> Analyze this against https://help.kusto.windows.net, database Samples, and show me what else is interesting. Run the seed query, discover the full schema, and produce follow-up analyses covering: storm type breakdown by state, monthly trends, damage per event ranking, hourly patterns, and storm type diversity — then suggest next questions.

## Data Sources

- **Cluster:** `https://help.kusto.windows.net`
- **Database:** Samples
- **Table:** StormEvents
