# Changelog

## 0.6.0    UNRELEASED

* Restructure extension C code
* Add table/filter columns support for CTEs
* Extract views as tables from CREATE/REFRESH VIEW
* Refactor code using generic treewalker
* Introduce deparse method to turn trees into SQL again
* Introduce truncate method to smartly truncate based on less important query parts
* fingerprint: Normalize IN lists
* param_refs: Fix length attribute in result


## 0.5.0    2015-03-26

* Query fingerprinting
* Filter columns (aka columns referenced in a query's WHERE clause)
* Parameter references: Returns all $1/$2/etc like references in the query with their location
* Remove dependency on active_support


## 0.4.1    2014-12-18

* Fix compilation of C extension
* Fix gemspec


## 0.4.0    2014-12-18

* Speed up build time by only building necessary objects
* PostgreSQL 9.4 parser


See git commit log for previous releases.
