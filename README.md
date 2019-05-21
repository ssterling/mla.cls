mla.cls
=======

LaTeX class for MLA papers.

Abstract
--------

In the United States, secondary and undergraduate students
are generally expected to adhere to the format prescribed by
the Modern Language Association (MLA) for typewritten essays,
research papers and writings.
Sadly, the tool of choice is usually Microsoft Word,
even amongst those fluent with TeX.

Though there *are* some templates and tools to aid in writing
in the MLA format using LaTeX, none fully met the expectations
of the author.
So *voilà*, there now exists an `mla.cls` proper:
a simple, straightforward class for composing papers almost
perfectly adherent to the MLA style guide.

Documentation
-------------

Documentation and source are combined into a
[`.dtx` file](https://texfaq.org/FAQ-dtx),
as is typical for LaTeX packages.
To read the documentation, run `mla.dtx` through LaTeX:
```console
$ pdflatex mla.dtx
$ gv mla.dtx
```
(If you're getting this package from [CTAN](https://ctan.org/pkg/mlacls),
a file called `mla.pdf` should already be provided.)

For an example file, refer to `mla-example.tex` and `mla-example.bib`,
or to the appendix in the documentation.

Installation
------------

Run `mla.ins` through LaTeX:
```console
$ latex mla.ins
```
Once finished, move the output `mla.cls` to your local
[`texmf` directory](https://texfaq.org/FAQ-privinst).

Authorship & licensing
----------------------

`mlacls` copyright 2019 Seth Price (ssterling AT firemail DOT cc).
Released under the
[LaTeX Project Public License v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/).

See [`CHANGELOG.md`](./CHANGELOG.md) for version history.

Contributing
------------

Submit a merge request on the
[GitLab repository](https://gitlab.com/ssterling/mlacls/).
I rarely look at the GitHub mirror.

Bugs
----

Refer to [`BUGS.md`](./BUGS.md).
Please report any bugs to the
[issue tracker](https://gitlab.com/ssterling/mlacls/issues).
