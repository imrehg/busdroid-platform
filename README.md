BusDroid Platform
=================

Wordpress plug-in for the unified StartupBus platform to
manage location logging for all busses.

Functional requirements:

* add/remove buses (id, name)
* provide settings for BusDroid Android App (JSON, or otherwise)
* create/revoke authentication tokens for incoming updates
* receiving location updates from BusDroid
* saving location updates to database
* notify front-end on updates (optional)
* provide debug interface for location updates (optional)

This should be self-contained, and as simple as possible to
minimize maintenance between events.
