# Redis Data Structures and Commands

Key-value and hash operations:
- `SET key value EX 3600 NX`
- `HSET user:100 name 'Arya' role 'admin'`
- `HGETALL user:100`


## Practical Idioms and Recipes

Sorted sets and streams:
- `ZADD leaderboard 100 'player1'`
- `ZRANGE leaderboard 0 9 WITHSCORES REV`
- `XADD mystream * sensor 'temp' value 24.5`
