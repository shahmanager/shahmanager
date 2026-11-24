# Docker Quick Reference

Essential Docker commands for container and image lifecycle management:
- `docker build -t app:latest .`
- `docker run -d -p 8080:8080 app:latest`
- `docker compose up -d`


## Practical Idioms and Recipes

Advanced inspection and cleanup:
- `docker system prune -af --volumes`
- `docker stats --no-stream`
- `docker inspect --format '{{.NetworkSettings.IPAddress}}' <id>`
