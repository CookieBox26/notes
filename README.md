# notes

### Compilation Requirement

You need XeLaTeX in TeX Live 2021 to compile TeX files in this repository.  
You also need the fonts used in each document.
```bash
$ xelatex -version
XeTeX 3.141592653-2.6-0.999993 (TeX Live 2021/W32TeX)
```

### Compilation with Git Bash

```bash
$ cd 20211114_hamilton
$ export TEXINPUTS="./;../sty/;"
$ xelatex main.tex
```

