---
name: inspect-schema
description: Inspect database tables, schemas, and query surfaces when the user needs read-only database context.
version: 1.0.0
---

# Inspect Schema

Use this skill when a task needs safe, read-only database exploration.

## When to Use

- The user wants to inspect table structure or relationships
- A query needs schema context before being written
- The workflow should stay read-only and exploratory

## Instructions

1. Identify which dataset or table family matters most.
2. Use the MCP server in read-only mode.
3. Summarize relevant columns, keys, and relationships.
4. Call out any unknowns before suggesting a query.
