# -*- Mode: org -*-

* About software-catalog

software-catalog aims to be a catalog of software. Currently the goal is
standardization of names and linking to names in Debian repository, among
others.

* How to use this catalog

* How to contribute

** If you are a software publisher

1. Fork this project on Github [1].

2. Add an entry to ~table/software/data.yaml~ or alternatively add a YAML file
containing your entry to ~table/software/data/~.

3. Pull request.

* Organization of data

Most of data is in the form of 2-dimension tables. Table data is in ~table/~.
Each table information will be put in its own subdirectory under this. Table
data is usually in ~data.csv~ because CSV is a pretty universal format, or
~data.yaml~ or YAML files under ~data/~.

Text encoding is in utf-8.

Metadata is put in ~meta.yaml~.

* Structure of metadata

Metadata is written in Sah [2] schema.

** Metadata for table

Schema for table metadata follows ~table_spec~ specified in CPAN module
Perl Perinci::Sub::Gen::AccessTable [3].

* Style guide

** Naming of files, tables, columns

** ~readme.txt~ file

1. Use Org format [4].

2. Use 80 column margin.

3. Use ~TODO~ to mark todo items (things to do later).

** ~changes.txt~ file

1. Use Org format.

** Commit diff

** Commit message

* FAQ

* Links

[1] http://github.com/sharyanto/software-catalog
[2] http://metacpan.org/module/Sah
[3] http://metacpan.org/module/Perinci::Sub::Gen::AccessTable
[4] http://orgmode.org/
