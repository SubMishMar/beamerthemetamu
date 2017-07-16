TAMU Slides Template
======================

This is a beamer theme designed for use in Texas A&M University.

Note that this template is NOT endorsed by the university. There is no
warranty implied.

Please refer to [this page](http://brandguide.tamu.edu/logos-downloads.html)
regarding the usage of the university logo.

Dependencies:
-------------

The template is based on beamer, so you should have beamer installed.

Installation:
-------------

Linux users can use the `Makefile` to install. Open a terminal and change to
the top directory of this package. Issue:

    make install

Other users can directly copy the files in the `theme/` directory of this
package into your `$TEXMFHOME/tex/latex/beamerthemetamu/` directory, where
`$TEXMFHOME` stands for your personal texmf tree directory. As with TeX Live,
it defaults to `$HOME/texmf` under Unix. For Windows (Vista and newer),
it is `C:\Users\<username>\texmf`.

Notes to MikTeX/CTeX users: there is not a default directory equal to
`$TEXMFHOME`, but you can use an arbitrary directory as your personal texmf
tree. Just set it up with the help of this guide[1], once and for all.
Remember to refresh FNDB after a fresh new install of this theme.

[1] http://tex.stackexchange.com/a/20121

After installation, you will get files such as
`$TEXMFHOME/tex/latex/beamerthemetamu/beamerthemetamu.sty`.

How to use:
-----------

You can use the sample file `beamerthemetamu.tex` to get started. Just
modify it (add your talk stuff) and then compile it using pdflatex or xelatex.
Note the sample file depends on the bib source file `beamerthemetamu-refs.bib`.
To output PDF file with correct citation info, you need to copy it along with
your tex file, or modify the tex file to use your own bib file, or just delete
all bib related stuff in the tex file.

License
-------

Copyright 2017 Alick Zhao <alick9188@gmail.com>


Unless otherwise noted in individual files, this work may be distributed
and/or modified

1. under the LaTeX Project Public License, version 1.3c or later, and/or
2. under the GNU Public License, version 2 or later.
