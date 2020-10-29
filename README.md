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

To export the database specified in `config.yml` to the file `dump`, run:

    pgadm -C config.yml -E dump


### <a name="import">Import</a>

To import the data from the file `dump` into the database specified in `config.yml`, run:

    pgadm -C config.yml -I dump


### <a name="miscellany">Miscellany</a>

To display usage summary, run:

    pgadm --help
