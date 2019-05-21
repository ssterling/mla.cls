Bugs
====

* Not really a bug, but specifying more than one of `mla7`, `mla8`
  or `mla8alt` will simply use the last one specified.
  Example: options `mla7,mla8alt` will use `mla8alt`, and
  `mla8,mla7` will use `mla7`.
  This is normal behavior in most classes, but I thought
  I ought to specify this somewhere before someone somehow
  gets confused.

Reporting
---------

Please report any bugs to the
[issue tracker](https://gitlab.com/ssterling/mlacls/issues).
