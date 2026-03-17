---
name: review-risky-automation
description: Review risky automation or shell workflows before execution when the user is about to run sensitive commands.
version: 1.0.0
---

# Review Risky Automation

Use this skill to add lightweight guardrails before destructive shell steps.

## When to Use

- The workflow involves risky shell commands
- The user is automating an operational checklist
- A safer fallback or rollback path should be identified first

## Instructions

1. Identify the risky step and its blast radius.
2. Suggest a safer dry run or narrower command if possible.
3. Recommend validation and rollback checkpoints.
4. Keep the guidance concise and action-oriented.
