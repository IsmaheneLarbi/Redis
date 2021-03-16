## Redis:
Saves key:value pairs on the RAM, can save on disk if size is important.
Used to save the cache version of a website such as cache_id:HTML code


## Syntax:

SET Key "Val"
GET Key 
SET user:123 "Name"
GET user:123
DEL user:123
INCR money:122
DECR money:122
TTL money
EXPIRE money num_seconds_til_xp

##  Create a list
