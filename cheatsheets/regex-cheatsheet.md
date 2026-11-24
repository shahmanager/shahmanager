# Regular Expressions Cheatsheet

Common regex patterns and lookarounds:
- `(?<=prefix)content` (positive lookbehind)
- `content(?=suffix)` (positive lookahead)
- `(?:non-capturing)`


## Practical Idioms and Recipes

Practical validation expressions:
- ISO 8601 Timestamps: `^\d{4}-\d{2}-\d{2}T\d{2}:\d{2}:\d{2}(?:\.\d+)?Z?$`
- UUID v4: `^[0-9a-f]{8}-[0-9a-f]{4}-4[0-9a-f]{3}-[89ab][0-9a-f]{3}-[0-9a-f]{12}$`
