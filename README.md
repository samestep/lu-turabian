LU Turabian
===========

What
----

A [LaTeX] version of the [sample paper][sample] for [Turabian research papers at
Liberty University][guide].

Why
---

[Such a template][template] already exists [for the
School of Divinity][divinity], but as noted on the website and in the samples,
the two style guides differ. Mr. Surber's template differs from the History
department's sample in these respects:

- The title page is formatted differently. (similar to [#1][i1])
- Page numbering starts on the title page. (like [#2][i2] but a bit worse)
- The Table of Contents is labeled as such, rather than simply "Contents".
- The ToC entries aren't bold. ([#3][i3])
- Footnote numbers are full-size followed by a period, rather than superscript.
  ([#5][i5], but I do this too as discussed [here][differences])

In addition, while Mr. Surber's template is merely a template, this repository
houses a full copy of Liberty's sample Turabian paper, which means that you can
use it to figure out how to do a great number of things without consulting
external documentation.

I tried to be as faithful to the original sample as possible, but I wasn't able
to get everything quite perfect. See [`differences.md`][differences] for a (to
the best of my knowledge) comprehensive list of differences between this
document and the original.

How
---

Two options.

### [Overleaf]

1. [Create an account.][account]
2. Create a new blank project.
3. Upload [`refs.bib`][refs].
4. Copy the [`main.tex`][main] content.
5. Recompile.

### Local

1. [Install Git.][git]
2. [Install Latexmk.][latexmk]
3. `git clone https://github.com/samestep/lu-turabian.git`
4. `cd lu-turabian`
5. `latexmk -pdf`

[account]: https://www.overleaf.com/register
[differences]: differences.md
[divinity]: https://www.liberty.edu/divinity/index.cfm?PID=28160
[git]: https://git-scm.com/downloads
[guide]: https://www.liberty.edu/academics/casas/academicsuccess/index.cfm?PID=11954
[i1]: https://github.com/samestep/lu-turabian/issues/1
[i2]: https://github.com/samestep/lu-turabian/issues/2
[i3]: https://github.com/samestep/lu-turabian/issues/3
[i5]: https://github.com/samestep/lu-turabian/issues/5
[latex]: https://www.latex-project.org/
[latexmk]: https://mg.readthedocs.io/latexmk.html#installation
[main]: https://raw.githubusercontent.com/samestep/lu-turabian/master/main.tex
[overleaf]: https://www.overleaf.com/
[refs]: https://raw.githubusercontent.com/samestep/lu-turabian/master/refs.bib
[sample]: https://www.liberty.edu/media/1171/Turabian_-_Non-Divinity_-_Notes-Bibliography_Format.pdf
[template]: https://www.overleaf.com/latex/templates/lu-turabian-latex-template-with-user-guide/dpdyjndnjkgy
