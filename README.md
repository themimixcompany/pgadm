pgadm
=====


<a name="toc">Table of contents</a>
-----------------------------------

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Usage](#usage)
  + [Export](#export)
  + [Import](#import)
  + [Miscellany](#miscellany)


<a name="overview">Overview</a>
-------------------------------

Scripts for exporting and importing Postgres databases from Miki configuration.


<a name="dependencies">Dependencies</a>
---------------------------------------

- pg_dump
- pg_restore


<a name="usage">Usage</a>
-------------------------

### <a name="export">Export</a>

To export to the file `/tmp/dump.pg`, run:

    pgadm -Ef /tmp/dump.pg


### <a name="import">Import</a>

To import from the file `/tmp/dump.pg`, run:

    pgadm -If /tmp/dump.pg


### <a name="miscellany">Miscellany</a>

To display usage summary, run:

    pgadm --help
