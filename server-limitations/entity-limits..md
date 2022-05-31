# Entity limiter.

Every interval the server performs a search in every mob farm and removes exceeding mobs. Currently this interval is set to every three minutes and will broadcast a subtle message into the chat the amount of removed entities.

Entities that are tamed or named are excluded from counts.

### Distance

* This is the radius&#x20;

## Rules&#x20;

### Global

A global rule active for all groups of 30 entities or more.

Applies to entities types: `all`.

* Distance: 3
* Max amount: 30

### Farm Animals

A rule to cull large friendly mob farms.

Applies to entities types: `pig, cow, sheep, skeleton`.

* Distance: 5
* Max amount: 24

### Spawner Mobs

A rule to limit spawner grinders, with several mobs in the same block.

Applies to entities types: `zombie, skeleton, spider, cave spider`.

* Distance: 1
* Max: 12
