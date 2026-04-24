# Code Style Guidelines

## General Rules

- Use descriptive variable names. Avoid single-letter names except for loop counters.
- Prefer `const` over `let`. Never use `var`.
- Keep functions short and focused — aim for under 30 lines.
- Add a brief comment above any non-obvious logic.

## Formatting

- Use 2-space indentation.
- Always use trailing commas in multi-line arrays and objects.
- Place opening braces on the same line as the statement.

## Error Handling

- Never swallow errors silently. Always log or re-throw.
- Use custom error classes for domain-specific failures.
