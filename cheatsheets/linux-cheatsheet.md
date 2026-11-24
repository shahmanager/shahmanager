# Linux CLI and Administration Cheatsheet

System diagnostics and process control:
- `systemctl status <service>`
- `journalctl -u <service> -f -n 100`
- `htop` / `top -b -n 1`


## Practical Idioms and Recipes

Network and disk inspection:
- `ss -tulpn`
- `df -h` / `du -sh * | sort -h`
- `lsof -i :8080`
