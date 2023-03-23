# Compile

Using [Chris Monson's](https://github.com/shiblon/latex-makefile) Makefile (requires `cvmfs`)

```bash
export PATH=/cvmfs/sft.cern.ch/lcg/external/texlive/latest/bin/x86_64-linux:$PATH
cd source 
make
```

To get a word count use

```bash
texcount -total -inc thesis.tex
```

You can use the [check repeats](https://github.com/rgrapenthin/util/blob/master/check_repeats) script to check for repeated words.

[Hunspell](http://hunspell.github.io/) is recommended as a spell checker.