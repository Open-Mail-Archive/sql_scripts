# SQL Scripts Changelog

## v2.0.1


**🌟 New features**:

- Enable full replication on all tables so that realtime updates for delete events include the full data in the payload, not just the id.

## v2.0.0

**💣 Breaking changes**:

- Changed id fields data types.


**🌟 New features**:

- Added `on delete cascade` to foreign keys
- Added Wipeout script.

##  v1.0.0

Initial release of sql scripts.