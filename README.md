Intro
=====
This is the (beginnings of) a PostGIS plugin for sequel.

It's closely related, but hopefully independent of the PostGISTable extensions
for rake (http://github.com/darrell/postgistable). *However* there is still
some code in that set of extensions that more properly belongs here. It will
migrate.

The ultimate goal of this is to be a full set of extensions for using PostGIS in Sequel.

How to use
==========
`Sequel::Model.plugin :postgis`

Requirements
------------

I do my testing in mainline 1.9.3 and PostGIS 2.0.x, and PostgreSQL 9.1.
However, I have no reason to think that 1.8.7 and PostGIS 1.5 will not work.

### Gems
* sequel (duh)
* pg
* logger
* rspec (if you want to write tests)

### Other
PostGIS (duh)

Caveats
=======

This is very much preliminary code. It is unlikely to be immediately useful to
you. However, it's hopefully not too far off.

Important TODOs
---------------
 * Needs more tests
 * Finish migrating code out of PostGISTable
