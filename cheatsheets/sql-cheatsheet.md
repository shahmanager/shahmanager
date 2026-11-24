# SQL Query and Optimization Cheatsheet

Core SQL idioms and window functions:
- `ROW_NUMBER() OVER (PARTITION BY user_id ORDER BY created_at DESC)`
- `COALESCE(val, fallback)`
- `COUNT(DISTINCT col)`


## Practical Idioms and Recipes

Indexing and execution plan analysis:
- `CREATE INDEX CONCURRENTLY idx_users_email ON users(email);`
- `EXPLAIN (ANALYZE, BUFFERS) SELECT ...`
