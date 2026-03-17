# Reproducible Prompt — Demo Visualize

Paste the prompt below into yokusto to recreate this project from scratch.

## Prompt

> Show me storm damage by state, event type, and month from https://help.kusto.windows.net, database Samples, table StormEvents — include deaths, injuries, property damage $, and crop damage $.
>
> Then build two more dashboards from the same cluster:
> 1. A sales analytics dashboard from the ContosoSales database — monthly revenue trend, top countries, product category breakdown, and margin analysis.
> 2. A storm seasonality dashboard — monthly and hourly event patterns, seasonal peaks by storm type, and weekend vs weekday comparison.
>
> Save all three dashboards in the same project folder with a shared `run_demos.py` script that regenerates them all.

## Data Sources

- **Cluster:** `https://help.kusto.windows.net`
- **Database (storms):** Samples → StormEvents
- **Database (sales):** ContosoSales
