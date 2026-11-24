# Bash Scripting Cheatsheet

Defensive shell scripting boilerplate:
- `set -euo pipefail`
- `IFS=$'\n\t'`
- `trap 'echo Error on line $LINENO' ERR`
