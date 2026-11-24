# Bash Scripting Cheatsheet

Defensive shell scripting boilerplate:
- `set -euo pipefail`
- `IFS=$'\n\t'`
- `trap 'echo Error on line $LINENO' ERR`


## Practical Idioms and Recipes

Parameter expansion and loops:
- `${VAR:-default}` / `${VAR:?error if unset}`
- `for file in *.log; do [[ -f "$file" ]] || continue; done`
