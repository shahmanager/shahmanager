# Kubernetes kubectl Cheatsheet

Pod and deployment inspection:
- `kubectl get pods -A -o wide`
- `kubectl describe pod <name>`
- `kubectl logs -f <name> -c <container>`


## Practical Idioms and Recipes

Debugging and rollout commands:
- `kubectl exec -it <pod> -- /bin/sh`
- `kubectl rollout restart deployment/<name>`
- `kubectl rollout undo deployment/<name>`
