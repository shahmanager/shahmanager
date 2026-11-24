# SQL Query and Optimization Cheatsheet

Core SQL idioms and window functions:
- `ROW_NUMBER() OVER (PARTITION BY user_id ORDER BY created_at DESC)`
- `COALESCE(val, fallback)`
- `COUNT(DISTINCT col)`
