# LaTeX Style Files

These are my personal LaTeX style files<!--
-->—basically, what has accumulated over the years.
Buyers beware.

The basic structure is like this:

    styles
    ├── externalise.sty   # externalisation settings
    ├── style.sty         # the bulk of the style file: commands, packages, …
    └── tikzit.tikzstyles # arrow styles for tikzit

An example file is provided by means of [example.tex](./example.tex).

Typical usage in another project would be to include this repository as a git submodule and symlink `style` into the right place.

``` console
$ git submodule add https://github.com/slotthe/latex-styles
$ ln -s latex-styles/styles/ styles
```
