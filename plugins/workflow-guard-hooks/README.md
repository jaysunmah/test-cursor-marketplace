# Workflow Guard Hooks

A Cursor plugin fixture that demonstrates the `hooks` optional manifest field.

## Included Components

- A plugin manifest with `"hooks": "hooks/hooks.json"`
- Hook definitions for `beforeShellExecution` and `afterFileEdit`
- Lightweight scripts that print guardrail-oriented messages

## Notes

This is intentionally a fixture plugin. The scripts are small and non-destructive so the plugin can be used for packaging and parser tests.
