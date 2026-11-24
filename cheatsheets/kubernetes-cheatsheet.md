# Kubernetes kubectl Cheatsheet

Pod and deployment inspection:
- `kubectl get pods -A -o wide`
- `kubectl describe pod <name>`
- `kubectl logs -f <name> -c <container>`
