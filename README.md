mla.cls
=======

LaTeX class for MLA papers.

Abstract
--------

Whilst the TeX family of programs is widely used in the sciences
and academia overall, there seems to be a lack of support for
the humanities, which commonly adhere to MLA format for
student papers and reports.

Though there *are*
[MLA-style packages available](https://ctan.org/pkg/mla-paper),
none met the expectations of the author (who was mostly
just nit-picky about elegance in code).
So *voilà*, there now exists a proper `mla.cls`:
a simple, straightforward class for composing papers
almost perfectly adherent to the
[MLA style guide](https://style.mla.org/).

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
(If you're getting this package from [CTAN](https://ctan.org),
a file called `mla.pdf` should already be provided.)

For an example file, refer to `example.tex` and `example.bib`,
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

If there's something in [`TODO.md`](./TODO.md), it's likely
a high-priority want, right under bug fixes.

Bugs
----

Refer to [`BUGS.md`](./BUGS.md).
Please report any bugs to the
[issue tracker](https://gitlab.com/ssterling/mlacls/issues).
